# 使用与动态加载资源

| 修改日期            | 修改内容 | 所属编辑器版本 |
| ------------------- | -------- | -------------- |
| 2022 年 10 月 12 日 | 文档创建 | 通用           |
|                     |          |                |

**阅读本文大概需要 10 分钟**

## 使用与加载资源的方式及示例

### 1.1  获取场景中已经存在的对象

#### **函数：**

##### **getChildren() : Array`<GameObject>`**

获取所有子物体()

**推荐使用 asyncFind 替代**

```ts
let goList = this.gameObject.getChildren();
goList.forEach(element => {
    console.log(`${this.gameObject.name} | ${element.name}`);
});
```

##### 

##### **getChildByName(name: string) : GameObject**

根据名字获取子物体 ( 物体名字 )

```ts
let childrenObj = this.gameObject.getChildByName("MyChildrenName");
```

##### **getChildByGuid(guid: string) : GameObject**

根据 GUID 获取子物体 ( 物体 GUID )

```ts
let childrenObjByGUID = this.gameObject.getChildByGuid("MyChildrenGUID");
```

#### **静态函数：**

##### **find(guid: string) : GameObject**

查找当前物体 ( 物体的 GUID )

可查找所有继承自 Core.GameObject 的对象

```ts
//find GameObject
let goByfind = Core.GameObject.find("GameObjectGUID");

//find Other Object eg.
let myTrigger = Core.GameObject.find("TriggerObjGUID") as Gameplay.BoxTrigger;
```

##### **asyncFind(guid: string) : Promise`<GameObject>`**

异步查找当前物体 ( 物体的 GUID )

可查找所有继承自 Core.GameObject 的对象

```ts
@Core.Class
export default class GetObj extends Core.Script {
    
    protected async OnStart(): Promise`<void>` {

       let goByAsyfind = await Core.GameObject.asyncFind("GameObjectGUID");

    }
    
}
```

**使用异步加载时，需要 await 修饰符，且将异步修饰符（async）包含至函数**

##### **getGameObjectsByName(name: string) : Array`<GameObject>`**

通过名字查找所有物体 ( 物体名字 )

```ts
@Core.Class
export default class GetObj extends Core.Script {
    
    protected OnStart(): void {

       let goListByName = Core.GameObject.getGameObjectsByName("GameObjectsName");
       goListByName.forEach(element => {

           console.log(`${this.gameObject.name} | ${element.name} | ${element.guid}`);

       });

    }
    
}
```

##### **getGameObjectByName(name: string) : GameObject**

通过名字查找物体 ( 物体名字 )

**返回第一个查找到的对象，如有多个同名对象，随机返回一个**

```ts
let goByName = Core.GameObject.getGameObjectByName("GameObjectName");
```

##### **findGameObjectByTag(InTag: string) : Array`<GameObject>`**

通过自定义 Tag 获取 GameObject ( )

```ts
@Core.Class
export default class GetObj extends Core.Script {
    
    protected OnStart(): void {

       let goListByTag = Core.GameObject.findGameObjectByTag("GameObjectsTag");
       goListByTag.forEach(element => {

           console.log(`${this.gameObject.name} | ${element.name} | ${element.getTag()}`);

       });

    }
    
}
```

### 1.2 克隆场景中已经存在的对象

##### **Clone() : GameObject**

复制对象（返回对象 : GameObject）

```ts
let goClone = this.gameObject.Clone();
```

### 1.3 在场景中生成资源库内的对象

##### **SpawnGameObject(assetId: string, bInReplicates?: boolean) : GameObject**

根据 GUID 构造一个 GameObject ( 资源的 GUID , 是否同步 )

```ts
@Core.Class
export default class GetObj extends Core.Script {

    @Core.Property()
    preloadAssets = "AssetID,EffectAssetID";

    /** 当脚本被实例后，会在第一帧更新前调用此函数 */
    protected OnStart(): void {

        //Create GameObject
        let assetGameObject = Core.GameObject.SpawnGameObject("AssetID");
        
        //Create Other Object eg.
        let effectObj = Core.GameObject.SpawnGameObject("EffectAssetID") as Gameplay.EffectSystem;

    }

}
```

使用**SpawnGameObject**函数时，所需生成的资源 ID 需要 preload

使用方法如上，在脚本中添加即可

**    @Core.Property()**

**    preloadAssets = "AssetID,EffectAssetID";**

### [1.4 在场景中生成预制体（Prefab）对象](https://meta.feishu.cn/wiki/wikcnwUnCTbhvEDchl5oqeF89lf)

## 使用与加载资源方式的区别

最本质的区别就是**获取(Get)**和**新建(New)**

### 2.1  使用资源

**1.1**** 内所有函数的方式都是获取资源（Get）**即为**使用资源**

使用资源会将该对象的内存地址指向所使用的变量

不会产生新的内存消耗

### 2.2  加载资源

**1.2****、****1.3****、 ****1.4**** 内所有函数的方式都是新建资源（New）**即为**加载资源**

加载资源会向编辑器申请一块新的内存用来存储新的对象

无论是复制还是生成，都会产生新的内存消耗

建议将逻辑中需要频繁重复新建、销毁的对象做成对象池，避免内存的过多消耗

## 使用与加载资源时的注意事项

**通过父节点获取对象只能写在 Server 端，Client 端目前不维护父子节点关系**

**若逻辑需求一定要在客户端判断父子节点关系，可做成接口在服务端验证**

**频繁创建、销毁对象时最好做一个对象池管理（例如子弹）**

**以减少程序内存与执行效率的开销**

**获取到的所有资源对象在使用前请进行判空处理，防止代码跑火车**

**需要动态加载的资源（资源库中的资源），需****要先 preload（预加载），否则会无法创建**

@Core.Property()

preloadAssets = "资源 ID";

**补充：**

方法一：可通过 AssetUtil.asyncDownloadAsset 的方式将资源异步加载到工程中

方法二：可以将需要动态加载的资源拖拽到优先加载中进行标记（原理同 preload）

**同步与异步查找对象的使用方式建议（find & asyncFind）**

在代码执行过程中

若逻辑的时序性比较重要，则建议使用异步加载

若不重要则使用同步加载

**异步加载会使代码执行暂时阻塞，待加载完毕再执行剩余逻辑**

**异步加载案例：**

场景一跳转至场景二时，我们可以使用 UI 遮挡场景加载的过程

使用异步加载等待反馈，待场景内所有资源加载完毕，再取消 UI 遮挡

**同步加载案例：**

当我们需要同时初始化很多资源，且资源并非及时使用的时候

我们可以使用同步加载，方便程序同时加载多个资源，加快进度
