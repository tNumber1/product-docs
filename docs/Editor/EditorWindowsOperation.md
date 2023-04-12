# 主编辑器各窗口操作

**本文涉及到的东西较多，建议用户分模块查看**

**本文概述了编辑器各个窗口的常规操作**

## 什么是编辑器窗口

从界面上来看，编辑器的界面由各个窗口共同组成；

从功能上来看，每个窗口都承担了部分编辑器的功能，只有熟悉各窗口的操作以及功能，才能使用制作出精美的游戏。

## 编辑器窗口都包含什么

- 编辑器窗口由顶部页签、菜单栏、工具栏、资源库、主视口、对象管理器、工程内容、属性面板八个部分组成。

![](https://cdn.233xyx.com/1681295515083_975.jpg)

## 如何合理利用/使用编辑器各个窗口

#### 通用规则

##### 页签化

- 除菜单栏、顶部页签、工具栏之外，其余五个窗口支持页签化
- 入口：以本地资源库为例，点击图中左上方小黄角，出现本地资源库页签

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnG0m0tukGXs7Pnz5L3zkeF7.png)

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnbBBhj8LGZYH0HFvgiiGqlf.png)

- 页签化后即可拖拽窗口至编辑器中各种位置，也可以单独拖拽成一个独立窗口

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn24NpEKA3rYfR8GPERSbrqh.png)

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn9aNnRNUOOwnGJjD4rEP62c.png)

- 若想隐藏选项卡，右键页签，点击“隐藏选项卡”即可
- 右键同时支持关闭、关闭右方选项卡、关闭其他选项卡操作

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnWWHAc89Awkk4Zn0qovfReb.png)

- 若想恢复至初始设置，点击菜单栏——视图——恢复默认设置即可

#### 顶部页签

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnKvaOIR12SC2UKsVsf0xMGe.png)

- 顶部页签与前文所述页签规则不同，无法将两者拖拽至同一级别下
- 默认存在主编辑器页签，并不可关闭
- 可以将**子编辑器**拖拽至顶部页签区域，使子编辑器页签化

#### 菜单栏

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnLlGw0snv32hx4RUxylXdmh.png)

##### 工程

- 工程菜单提供了一系列工程相关的操作；用户可以在此进行工程的新建、打开、备份、游戏管理等

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn16IifDL3vyzlWuJMsVXZah.png)

##### 视图

- 控制各个窗口的显示与否，通过多选框操作

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnmiJE5Q1lnsl7UT2TE2ov3d.png)

##### 帮助

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnQC9c93IsAdy62Wz2GdInBc.png)

- 更新公告：查看此版本的更新内容
- API 文档：查看各个 API 的使用方法
- 官方教程：查看官方提供的各方面教程
- 产品手册：查看编辑器各个模块、名词的作用和用法

##### 撤销&恢复

- 常规的撤销恢复操作，快捷键：ctrl+z、ctrl+y

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnBJznYyXU2t5BacpJbh0uUc.png)

#### 工具栏

##### 绘制模式

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnnJqqEH7Al2V9afJFtWXg2W.png)

- 见[绘制模式](https://meta.feishu.cn/wiki/wikcnP6XaIl2ZZU8EXIYsiaBvDg)文档

##### transform 工具

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnHWhEB4gVUlw1Sbky973Fch.png)

- 左侧三个按钮分别是移动（W）、旋转（E）、缩放（R），可以在此选择需要调整哪一个属性，也可以在主视口中通过快捷键操作
- 最右侧图标 + 数值含义是在**所选**的 transform 工具下，执行的最小单位（下图为移动的单位）

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnoJoHhR0uznpiilaTnEPYTG.png)

- 单击网格图标，可选择是否启用此功能；若不启用，则按**系统默认最小单位**执行操作命令**（该单位远小于下拉框中提供的单位）**

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnrJMFKqfc4dCFH3Fct0Kzjc.png)

##### 世界/本地轴向

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnoOfKI8AMvNlaJDtd3MHLPd.png)

- 点击该图标，可切换主视口所使用的世界/本地轴向
- 世界轴向：进行移动和旋转时，始终按照世界坐标进行，不随着物体的旋转而变化
- 本地轴向：进行移动和旋转时，以所选物体为参考系进行

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnDel2XKjXTxXaWmrDEJgTdE.png)

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn8N8sYUjN1K8ssV8gXojpQb.png)

##### 新建

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn5P9rCGfC9owOES92vlhnRb.png)

- 点击新建脚本，会在工程内容中新增一个脚本文件，并置于重命名状态
- 点击新建预制体，会在工程内容中新增一个预制体文件，并置于重命名状态，并且主视口与对象管理器将会自动进入该预制体的编辑状态
- 点击新建 UI，会在工程内容中新增一个 UI 文件，并置于重命名状态
- 点击新建角色，将打开角色编辑器

##### 运行

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn5PcLOl9ZDGDhMsB9qV4aDh.png)

- 点击运行左侧图标，在本地运行游戏
- 点击运行右侧下拉图标，打开运行设置界面

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnPRbXBV1faehYwg0X5gcETb.png)

- 运行时会按照运行设置的条件运行
- 端口：运行时的端口号，同一端口的玩家将进入服务器分配的同一空间中**（目前本地运行暂不支持多端口运行）**
- 单机模式：勾选该模式后，玩家数量只能为 1，无法与他人联机
- 玩家数量：**非单机模式下可选**，决定本地运行时的玩家人数
- 起始位置：可选择是以场景中默认出生点运行（F5）还是以当前实际摄像机位置运行（F6）

##### 显示

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcna9Cy989owIZF00JHHBh8If.png)

- 寻路区域可视：在主视口中是否可以看见“寻路区域”逻辑对象显示的具体**绿色**区域

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnUnypxYaOys7kC60OuyNlhg.png)

- 隐藏图标和线框：在主视口中是否可以看见图标和线框；快捷键：V

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnIKorGRnET5nZuMKNXhJtWf.png)

- 聊天区域可视：**在编辑阶段（非发布后）**是否在主视口中隐藏聊天区域（聊天区域为平台提供的通用聊天功能，在游戏发布至平台后会默认生成）

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnlQcb0p8rMBGhEcxGqd9Whc.png)

##### 分辨率

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnnsjyuNSjEfh8LRnTvgFVRd.png)

- 控制当前主视口/运行时的分辨率，用以本地调试
- 主视口平铺：场景填充满当前的主视口大小

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnQblgC3hOfbWPJFywKbZDRc.png)

- 底部新增按钮可以自定义分辨率，点击后出现自定义面板，可填写自定义分辨率的名称，尺寸信息

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn0GxwXWFMlNWelUIJwl8Yoe.png)

- 新建成功后，单击即可切换；点击右侧的删除图标（悬浮才显示），可删除该自定义分辨率

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnxb5im0yZIcDHCJLy7CwiJb.png)

- 设备显示设置：决定是主视口画面横屏还是竖屏，下图是 1920x1080 分辨率横屏和竖屏的图示

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnZqvZOxbBuHH0RE1AVNTjRg.png)

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnkInsXmbpqf44CDF15Kveqb.png)

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnHZIfP1L2KpXfrj7itig96b.png)

##### 摄像机

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnR30zOXV1N0VRwJ1ne9Wl7s.png)

- 通过滑块设置当前摄像机移动的速度和加速/减速比例
- 正常速度：主视口按下鼠标右键 +WASD 时，镜头移动的速度
- 加倍速率：主视口按下鼠标右键 +WASD+Shift 时，镜头加速的倍率；如值为 2 则是两倍正常速度
- 减速比例：主视口按下鼠标右键 +WASD+ Ctrl 时，镜头速度占正常速度的比例；如值为 0.1 则只有正常速度的 1/10

##### 设置

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnvBgUVvsA3XXV4116ab7sQf.png)

- 世界设置：设置世界场景的一些属性与玩家的一些属性，详情见[编辑器各设置](https://meta.feishu.cn/wiki/wikcnny98WrhiCiUaREV1W6pufe)
- 编辑器设置：设置编辑器相关的一些属性，详情见[编辑器各设置](https://meta.feishu.cn/wiki/wikcnny98WrhiCiUaREV1W6pufe)

##### 碰撞盒

- 开关：工具栏中碰撞盒功能

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn2qGSr0qdCrHjLx8nYcnFpe.png)

- 对齐规则

  - 包围盒边对齐

    - 拖动对象移动时，当包围盒某一边与其他对象的包围盒边对齐，对齐的包围盒边显示黄色
    - 对齐时增加判断，鼠标继续拖动一定距离时对象解除包围盒边对齐，可以继续移动

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnbpR8X621tJXgG1PEAIC56b.png)

- 包围盒表面对齐

  - 拖动对象移动时，当包围盒某一面与其他对象包围盒表面对齐，对齐的包围盒表面显示黄色
  - 对齐时增加判断，鼠标继续拖动一定距离时对象解除包围盒表面对齐，可以继续移动

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnu2JUHrQR46ka06bNfgOMZg.png)

##### 对齐工具

- 功能入口：工具栏——对齐工具

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnZ8TpCISwkfw9T74dEqlZFh.png)

- 打开后默认显示在属性面板

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnkJoM2EuoyL3occ9wjwzyxe.png)

- 使用

  - 模式：按所选轴的最大/居中/最小进行对齐

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnSM55P5JTEM2LBWbCUcRdDg.png)

```ts
- 对齐轴：按世界/本地坐标进行对齐，坐标轴可进行多选
```

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn4dNlzQJU3DieDAWfHl50Wb.png)

```ts
- 参考系：
```

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnPQO1mQrtDkQ0753ZUagMfq.png)

```ts
  - 选择范围：按照所选对象形成的包围盒进行对齐

  - 活跃对象：默认为最后一个选择的对象，以此对象为参考系

    - 勾选此项后，可通过左键修改活跃对象，活跃对象的边框颜色为橙色
```

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnYi28ez5mTHS0z0XNLxsRhd.png)

```ts
- 对齐：当所有选项均被选择后，对齐按钮高亮，鼠标hover至对齐工具面板中，主视口显示对齐轴/面/点
```

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnJbWcx8pQ4XwprzkBR8QPzO.png)

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnhpQCZDQaZ9RXXzHpSFCm6b.png)

-

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnS3zf4LhGNbDjz0DhDe45pd.png)

-

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnetoe5lhZXZWYgcLC1coSBh.png)

-

##### 本地化

[游戏语言本地化](https://meta.feishu.cn/wiki/wikcnTPgS5c4aEGRJjorJqbHlvb)

#### 本地资源库

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnTYuSh41rawFEO5aIGazffh.png)

- 本地资源库提供了各种资源用以搭建各式各样的场景
- 左侧 tab 切换分别是美术资源、游戏功能对象、收藏、历史记录、预制体

  - 逻辑资源：有某种通用能力的对象，用以实现游戏逻辑

    - 目录级别：逻辑资源——资源类型
  - 美术资源：用以搭建游戏世界

    - 目录级别：美术资源——资源类型——主题
  - 历史记录：记录最后使用的 100 个资源

    - 目录级别：历史记录——资源类型——主题
    - 信息存在本地，用户下次打开时的记录与之前一致
  - 预制体：包含复杂结构的对象组合

    - 目录级别：预制体——主题
  - 收藏功能暂未开放

##### 资源下载与预览

- 编辑器中的资源**存在云端**。需要**点击资源**进行下载
- 点击下载完成的资源缩略图右上角放大镜，出现预览窗口对资源进行预览，静态模型、特效、动画支持**视口预览**

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnN3IOQulKioAEqEnMc4aCfd.png)

1. 预览窗口相关：
2. 预览窗口中标签显示规则变化，隐藏了之前用以模糊搜索的**搜索标签**，新增**显示标签**，点击显示标签，可在资源库进行同类标签的搜索（暂时显示标签还未进行配置，配置后可看到各资源对应的显示标签）
3. 隐藏了未配置注释的注释属性
4. 支持通过方向键切换预览资源
5. 对于音效、动画等可以播放的资源，播放入口如下图所示

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnxETZuTEGC8tGT4rUNPZ3Rd.png)

- 每次进入工程时，会花费几秒的时间从服务器拉取资源的相关信息，用以资源的展示、筛选和搜索操作

##### 资源使用

- 不同的资源有不同的使用方式，详情请参考资源相关手册
- 右键资源可以复制资源 ID 和名称，方便在脚本中引用

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnMXxwgcXOmIf4XfBe87fjPf.png)

##### 筛选相关

- 支持对资源的**风格**和**分类**进行筛选
- 风格的筛选通过下拉框选择，支持多选，结果取**并集**
- 不同的资源类型有不同的风格，在同一类型下切换主题时，筛选不会清空

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnL0JI5oy2VX5zrDOcL804bh.png)

- 分类的筛选通过标签选择，支持多选，未显示完的标签可通过下拉按钮展开，结果取**并集**

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnko4H5zv1tovjN1kzWx9bUc.png)

- 分类筛选将对所选标签进行排列，取消某分类标签筛选时，该标签回归之原来位置

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnl0ggwAhwaIeSIItrdit8Ac.png)

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnVWNM36sTMv2417FaY9KCMc.png)

- 风格与分类筛选条件之间取**交集**
- 在切换**同一资源类型的不同主题**时，风格的筛选条件会被保留，分类的筛选条件会被移除
- 支持搜索后进行筛选

##### 搜索相关

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcngOPXaOUeOnEFfPSUpJ7Uzd.png)

- 可以通过资源名称、资源 ID、资源标签进行模糊搜索
- 结束搜索状态时，会初始化导航目录，并清空当前的分类筛选，但风格筛选会在下次进入搜索前的目录时保留

##### 其他

- 资源导航右侧支持拖动以调整区域大小

  - 拖拽存在宽度最小值与最大值，最小值一行显示四个资源，最大值显示两个资源

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnkty7k2COKxty3k1ryeHzge.png)

- 资源导航支持快捷收起/展开

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnLC0o8uYV63PJCr8Vek9yHA.png)

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnMKgLsopng8YxqD0dkrKGKc.png)

- 游戏功能对象支持通过 tips 跳转至对应产品手册

  - 鼠标悬浮至功能对象时，按住 alt 后可点击蓝色字体，从而跳转至对应手册

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnESnsILbC82Gv9X3gLfjdag.png)

#### 主视口

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcntJCC8Gdef0b29vWVoXvHag.png)

- 主视口用以搭建丰富多彩的游戏世界

##### 选择对象

- 选择对象的方式有三种，分别是主视口点选、主视口框选、对象管理器点选

  - 主视口点选：鼠标左键点击主视口中的对象即可选中，鼠标左键 +ctrl 多选对象
  - 主视口框选：按住鼠标左键拖拽即可在界面中实现框选，可框选多个对象
  - 对象管理器点选：鼠标左键点击对象管理器中的对象可以选中，鼠标左键 +ctrl 多选对象

##### 摄像机操作

- 拖拽鼠标右键，可旋转摄像机（摄像机位置保持不变）
- 滚轮滚动，可移动摄像机（摄像机朝向保持不变）
- WASD+ 鼠标右键，可移动摄像机并调整摄像机朝向（摄像机位置与朝向均改变）

##### transform 工具

- 移动：选中对象后按 W 可切换至移动模式，鼠标左键拖拽对应坐标轴即可完成物体的移动

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn2fl2QbIVTlof4upSUyOMKc.png)

- 拖拽时可选择多个坐标轴
- 对象可多选
- 除移动坐标轴之外，鼠标左键按住物体锚点拖拽也可以移动对象，并且与 transform 模式无关

  - 使用该操作时，静态模型对象在靠近时将会自动吸附至另一静态模型对象上
- 在对主视口对象进行移动时，按住 shift 键可以锁定摄像机与对象之间的相对位置
- 旋转：选中对象后按 E 可切换至旋转模式，鼠标左键旋转视口中的旋转轴即可完成物体的旋转

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnS31cSLeS2etGq6gQHgyi2d.png)

- 旋转时只能选择一个坐标轴
- 对象可多选，**但多选时将基于包围盒几何中心旋转，而非对象锚点**
- 缩放：选中对象后按 R 可切换至缩放模式，鼠标左键拖拽对应缩放轴即可完成物体的缩放

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn2iLzApXWANCAvf7zdfvPGh.png)

- 缩放时可选择多个坐标轴
- 对象可多选
- 缩放按物体当前长宽高的比值进行等比缩放
- 单边缩放（**仅静态模型可以使用**）：如图中所示六个点，分别是上下、左右、前后；鼠标左键拖拽这六个点，可实现单边缩放的效果

##### 主视口右键菜单

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnPHc3qnW9Xv7FWcV8llbXMe.png)

- 只有当选中某一对象时，主视口中的右键功能才可使用（粘贴除外）
- 复制、粘贴等基本操作此处不再说明
- 从对象某方观察

  - 将摄像机移动至该对象的某一个方位，方便从该方位观察此对象

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnobo82c2jBZOtwozMnVh8Hf.png)

- 对象聚焦

  - 进入对象聚焦状态后，右键旋转摄像机角度时，摄像机将**围绕对象**进行旋转，方便从不同方位观察对象的细节
  - 可通过快捷键 F，或主视口右键菜单中的“对象聚焦”，或者双击对象管理器中的某个对象进入对象聚焦状态
- 移动对象至摄像机所在位置

  - 将此对象移动至当前摄像机的位置，使得摄像机与当前对象锚点重合，修改的是对象的**位置**
- 旋转对象至摄像机所对朝向

  - 将此对象旋转至当前摄像机的朝向，修改的是对象的**旋转角度**
- 向下吸附

  - 将此对象向地面吸附，规则为**以包围盒触碰至地面为准**
  - 若对象的包围盒已经和地面接触或者处于地面**下方，**则该操作无效

##### 视图选择器

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnq9Mhzro2tfqxGMpMSUMNCe.png)

- 基础面（6 个）：包含前、后、左、右、上、下
- 角面（8 个）：相邻三面所夹的角面，包含前上左、前上右、前下左、前下右、后上左、后上右、后下左、后下右
- 单击视图选择器的某个**基础面/角面**，将旋转摄像机的位置和方向，将视图切换至该面
- 按住鼠标左键，可拖拽视图选择器在主视口的位置

##### 场景/预制体模式

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnpQoXeuLaL6sODaxPhjwoBe.png)

- 主视口分为两种编辑模式，场景模式与预制体模式
- 场景模式下，编辑的是**游戏场景**
- 预制体模式下，编辑的是**某一预制体**
- 预制体模式下编辑预制体后，可点击工程内容中的保存按钮或切换至场景模式保存预制体

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcntvAgwUK9NjIjidiH4L4Hig.png)

- 当双击预制体文件或者新建预制体时，上图中的切换按钮将会出现，单击即可模式切换；也可以通过主视口右上角关闭按钮关闭预制体编辑界面

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcntKtojyJyCJoKGE7Ck44Ujf.png)

#### 工程内容

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnXkyb9xwX4bn7FMiO31Pigc.png)

- 工程内容目的是管理与编辑此工程使用的文件
- 左侧目录为文件类型分类，不同分类的功能有所区别，同时左侧也是导航区域，可通过左侧导航快捷访问**文件夹路径**

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn952MNg4ED23joNEn2oaHoe.png)

- 左侧目录同时支持文件夹的右键菜单操作，下面会说明各类型下文件夹的功能

##### 平铺/列表模式

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnhqzs7oCACvd9yKOCtf5PSg.png)

- 新增排列方式的选择

  - 功能入口为在工程内容页右上角图标，左侧为列表方式显示，右侧为平铺方式显示
  - 排列方式信息存储至本地

##### 快捷路径访问

- 左上角提供快捷路径访问功能，点击对应文件夹，将跳转至该文件夹下

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn8r0l3wW3Aug8tm3Hvedn5d.png)

##### 搜索功能

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnQxuH5TBkEBpicFeOnMvlxd.png)

- 基于当前选中的目录**包含同级向下搜索**
- 搜索规则为按名称模糊搜索
- 切换左侧文件分类时，搜索关键词不会进行清除

##### 预览功能

- 平铺模式：hover 至文件时，图标右上角出现预览入口

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnpZtvR6Sd39wPborM3PrJHe.png)

- 列表模式：hover 至文件时，该行最右侧出现预览入口

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnms1WbgUAz31y6JTyKzm1Af.png)

- 点击此按钮，打开预览窗口，预览窗口以单独窗口存在，可拖拽至屏幕内任何位置

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnBbkehFXmDtxOXQOvP0Uqlc.png)

- 脚本预览：提供 GUID、名称的复制按钮，并显示脚本详细信息

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnFX3bR7ndT3igeA0Jz3Eyxe.png)

- 预制体预览：提供 GUID、名称的复制按钮，并显示预制体结构，支持视口预览

  - 预制体结构树支持展开与收起节点
  - 视口预览：类同于主视口摄像机操作，可更好的观察此资源

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnh6G0w4wcOSodNt0nwFQUMd.png)

- UI 文件预览：提供 GUID、名称的复制按钮

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnCS7VvMEwYQPUHxPUww2sDc.png)

- 角色文件预览：提供 GUID、名称的复制按钮，以及预览视口

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn7XFUfeW7VkUKhKOW69EHUd.png)

##### 脚本

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn7lRDztjMNVPyerALgtT4lC.png)

- 左侧导航栏切换至脚本时，右侧提供新建脚本、新建 UI 脚本、导入脚本按钮
- 新建脚本：点击此按钮，在**当前目录下**新建一个脚本
- 新建 UI 脚本：点击此按钮，在**当前目录下**新建一个 UI 脚本
- 导入脚本：点击打开 windows 资源管理器，在当前目录下导入脚本文件

  - 只允许导入 ts 格式的文件
  - 导入时支持多选
- 脚本文件的使用

  - 将脚本文件拖拽至主视口或对象管理器中即可生效
  - 具体挂载层级和脚本里代码逻辑有关
- 右键菜单——右键脚本文件

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnneX3ojMDR79vZe1apd2Xod.png)

- 复制、粘贴等基本操作此处不再说明
- 选择最近引用对象

  - 工程内容中的文件与对象管理器中的同一对象是**引用关系**（如拖拽一个脚本至对象管理器内，对象管理器中的脚本对象实际上是引用的工程内容里的脚本文件）
  - 同一脚本文件可能被引用多次，故此功能为在**对象管理器中选中最近一次引用的对象**
- 编辑

  - 点击编辑后（或者双击脚本文件），将自动打开 VScode，编辑脚本
  - 若没有 VScode，请用户自行前往 VS 官网下载
- 导出

  - 点击导出后，打开 windows 资源管理器，存储脚本文件，主要目的是**不同工程复用脚本**
- 刷新

  - 更新脚本信息至最新（在 VS 中编辑后需要点保存）
- 右键菜单——右键空白区域

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnWy3mm96g0DSZ0x4wmnWuzh.png)

- 刷新、粘贴功能此处不进行说明
- 创建文件夹

  - 在当前目录创建一个文件夹
  - 可以将不同脚本拖入不同文件夹中，方便管理
- 右键菜单——右键文件夹

  - 一些基本的操作，此处不进行说明

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnzOsVMKyO1QhCRMvlBZRm7c.png)

##### 预制体

- 预制体在工程内容中以文件夹形式存在

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnHoHeFwQd6a73ftbp3zqeLh.png)

- 该文件夹包含了一个预制体文件，一个脚本文件夹与 UI 文件夹

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnOnx9xUTLY1LWOQSfWGyEDe.png)

- 双击**预制体文件**，主视口进入预制体编辑状态

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnwQqa5KxwKhoQrLJVKsjFcf.png)

```ts
- **修改后**，工程内容预制体界面出现保存按钮
```

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnZ59MhxS37NjatpO7cIfOVf.png)

- 预制体的右键功能与脚本大体一致，不同的点如下

  - 预制体界面不支持创建文件夹
  - 预制体文件夹中的脚本与 UI 文件夹**不支持删除、重命名、粘贴操作**
  - 预制体文件夹支持导出功能，方便**对于整个预制体进行复用**
- 预制体的使用

  - 将**预制体文件（非文件夹）**拖入主视口或对象管理器中即可生效
- 预制体详细功能请参考预制体使用手册[预制体功能说明](https://meta.feishu.cn/wiki/wikcnwUnCTbhvEDchl5oqeF89lf)

##### UI 文件

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnzZok93zOBd0ar5I7dQA3Oz.png)

- UI 文件界面提供新建 UI 按钮，点击后在**当前目录下**新建一个 UI 文件
- 文件夹操作与脚本一致
- 右键 UI 文件，功能与脚本基本一致，唯一区别是编辑（双击）UI 文件时，将自动拉起**UI 编辑器**
- UI 文件的使用

  - 将 UI 文件拖入主视口或对象管理器中即可生效
- UI 编辑器相关使用请参考 UI 编辑器手册

##### 角色

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnygrru6Bh41iQNSckamL1Nk.png)

- 角色界面提供新建形象与导入角色形象数据按钮
- 点击新建形象（或者双击角色数据文件），拉起**角色编辑器**
- 点击导入角色形象数据，拉起 windows 资源管理器，可选择之前导出的角色数据，主要目的也是为了不同工程**数据复用**
- 文件夹操作与脚本一致
- 右键角色数据文件功能与脚本一致，唯一区别是编辑（双击）角色数据时，将自动拉起**角色编辑器**
- 角色数据的使用

  - 可拖入主视口或对象管理器中**以单独的角色数据存在**
  - 角色数据目的是修改角色形象，若想用于角色身上（如把一件衣服穿在人身上），**需要在角色编辑器中使用或在脚本中调用对应****API**，具体请参考角色编辑器手册

##### 材质

- 材质文件与其他文件不同，需要具体的材质资源支持。材质文件为描述文件（prefab 也是描述文件），描述的是该材质资源的参数配置
- 欲自定义材质，首先需要到属性面板中找到材质属性，并点击编辑材质按钮

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnyBuVZul08kRUUqkiofn68b.png)

- 点击按钮后，会基于该材质资源，在工程内容中新建一份材质文件

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn9R9Hms6Y0LQilLroNOZYDb.png)

- 双击材质文件，可以编辑该材质的属性，以及该材质使用的贴图资源
- 修改后，点击保存，将保存该材质的参数设置

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn07dkh6SK9EGpyjOHXpTXTb.png)

#### 输出窗口

- 输出窗口用以查看日志

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnuAtPHJm6WWApxevgL1Z7YT.png)

- 输出窗口分为服务端，客户端 1/2/3/4，通过菜单栏——视图决定是否显示

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnvDwIHg9fiaNwxKcZl1lL3a.png)

- 日志级别分为信息、警告、错误、输出，通过下拉选择

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnDmhDOBaMT05QqhYbRfV2uh.png)

- 右键操作

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcni4WmpeLsKrhW8abKDJUHyg.png)

- 提供清空日志、复制、打开日志目录操作

#### 对象管理器

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnNvJb97jaeD3eIYvyACnyUc.png)

- 对象管理器用以管理场景中使用的各类对象
- 根目录分别是世界、对象、寻路区域、优先加载，每个区域对应的含义不同

  - 世界下对象：不可删除，场景中必须存在的对象，如摄像机、天空盒等
  - 对象下对象：一般的对象，也是构建游戏世界的主要部分
  - 寻路区域下对象：只允许挂载“寻路区域”“寻路区域修饰”逻辑对象以及脚本
  - 优先加载下对象：放入此区域的对象将在启动游戏时加载，加载完成后才会进入游戏

##### 挂载操作

- 将对象置于某对象的子级：拖拽对象至另一对象上

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnQZAFJlWjjiwHckF2IZ258f.png)

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnLQnktWNPfcnEpL7BWZbC8d.png)

- 将对象置于某对象的平级：拖拽对象至两对象之间的横线上，同时也可用于平级移动

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnDTFTec9kVABDvwBzQpDEof.png)

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnhUL3Ct1mZ9765wbap4JJph.png)

##### 全部展开/全部收起功能

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnehjEAkffhgZJfc2RY1852b.png)

- 只有**根目录“对象”**有此功能
- 点击此按钮，“对象”下的所有树状结构分支将全部展开/全部收起

##### 搜索功能

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn1y4mBZqCf6hEC3LmDJtNEd.png)

- 支持对各对象的**名称与 GUID**进行模糊搜索
- 搜索状态下选中对象后，退出搜索状态时仍可以定位至该对象（若多选则定位至最后一个选中的对象）

##### 筛选功能

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn03zoH1xjlCnTuJswrgqldb.png)

- 支持对对象的静态状态、网络状态、视口展示、视口锁定、文件属性进行筛选
- 筛选后的选项通过标签形式展现，点击标签清除按钮可删除该标签

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnsjNPFqqGqvxXjvwHIAy0Sh.png)

- 筛选结果**同一条件与不同条件之间均取并集**

##### 对象右侧网络、锁定、显示属性

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnCxxgXlFrN4tkGGelENYpzf.png)

- 锁定/隐藏按钮显示逻辑

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnJV6z6OZqJbZ9ZLO2c7NQh2.png)

- 锁定/隐藏按钮处于“已锁定”或“已隐藏”状态下时，按钮正常显示在对象管理器中
- 锁定/隐藏按钮处于“未锁定”或“未隐藏”状态下时，需鼠标悬停对象上才显示对应按钮
- 网络状态：点击图中“S&C”按钮，展开网络状态的选择

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnaHCFMSbQLQfi8yS2EDjrRg.png)

- 该属性也可以在属性面板中进行设置
- 锁定状态：点击锁定按钮，切换锁定/未锁定状态

  - 锁定的对象在主视口中不可选中，只有在对象管理器中选中该对象，并在主视口显示红色框

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnr0tDFCUQIXguMMMYyCm0Qh.png)

- 显隐状态：点击显隐状态按钮，切换显示/隐藏按钮

  - 隐藏的对象在主视口中不可见

##### 场景/预制体模式

- 和主视口一样，对象管理器也分场景/预制体模式
- 在进入预制体编辑状态后，对象管理器中将显示该预制体的结构，而不再是世界场景；和主视口同步

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnGnUv4Pn2jiJsO1mWI9fldb.png)

##### 右键菜单

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnub9VoNiXRtffxrP7Th3pCc.png)

- **不同根目录、文件类型**的右键菜单功能所提供的**功能范围不同**，**但功能种类基本一致**；下面说明一些常用的功能
- 基本操作此处不再进行说明
- 添加至优先加载对象

  - 将所选对象添加至优先加载区域中
- 粘贴和粘贴至

  - 粘贴：粘贴到选中对象的**同级**（未选中对象时粘贴到根目录“对象”子级）
  - 粘贴至：粘贴到选中对象**子级**
- 创建文件夹&&包含选中创建文件夹

  - 创建文件夹：在选中对象的**子级**创建文件夹
  - 包含选中创建文件夹：文件夹创建在选中对象的**同级**，选中对象变为文件夹的**子级**
- 创建合并对象&&包含选中创建合并对象

  - 只有静态模型才能合并，合并对象可以**优化运行时的性能**（多个 mesh 变一个 mesh）
  - 选中一个对象时或者“对象”根目录时，可以在该对象的子级创建一个空的合并对象，用户可以往空合并对象中拖拽静态模型
  - 选中一个或多个对象时，可以包含选中的这些对象创建一个合并对象，相当于把这些对象进行了合并
  - 右键合并对象，可解除合并

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnQ5ocY3zAJ7rvzwXHP0ShMf.png)

- 创建游戏功能对象

  - 仅在单选时可用，多选时不可用
  - 在该对象的**子级**创建一个指定的功能对象，方便对该对象处理游戏逻辑

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnldsx96zCpLnhXiMkUXhfKe.png)

- 对象聚焦：功能与主视口相同
- 定位来源

  - 背景：**对象管理器中的对象实际上是引用对象，本身只是一个引用关系，而不是数据本身**
  - 将对象的数据来源置于选中状态（**来源一般是资源库与工程内容**）
  - 如从资源库拖拽一个资源至主视口，定位来源按钮可直接定位至资源库该资源的位置，并置于选中状态
  - 若数据来源消失，则对象管理器中的对象将会变成红色，此时此对象已经没有意义

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnw0lwP65OPBFO0sWn6el8yg.png)

- 生成为预制体

  - 将选中的对象生成为预制体，并在工程内容中新建此预制体
- 预制体对象相关

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnD4VNfpAAaLeUjAYB1UyIuf.png)

- 预制体对象与常规对象功能有所区别，主要新增了图中所示三个功能
- 编辑预制体

  - 主视口与对象管理器均进入预制体编辑模式，对该预制体进行编辑
- 以预制体引用对象更新预制体

  - 未进入编辑状态时编辑预制体，如直接在对象管理器中修改预制体的树状结构时（**这时预制体在对象管理器中会变成黄色，此时预制体从普通状态进入实例状态**），使用此功能可以保存预制体的修改

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnt5jbOmWp2YHPPpTaJzlh9S.png)

- 重置预制体

  - 使预制体从实例状态变为普通状态（紫色变黄色），即撤回本次实例状态下在对象管理器中对此预制体结构的修改
- 另存为新预制体

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnRGK3veGoaz4mkYJnT4HW9d.png)

```ts
- 在预制体**进入实例状态后**，该选项出现

- 将此在对象管理器中修改过的预制体另存为一个新预制体，工程内容将新增此预制体，对象管理器中原预制体也同步更新为此新预制体
```

#### 属性面板

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnNzJb0qbIHbjxLHXxHhiYYf.png)

- 属性面板用以**预览资源信息和修改对象属性**
- 预览功能之前已经分别在本地资源库和工程内容中讲过，故下面主要说明修改对象属性相关操作

##### 搜索功能

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn4pbivzvA9rId27GcyMVQUh.png)

- 支持对**属性名称**进行**中/英文**的模糊搜索

##### 基础属性

- 名称、tag、网络状态、动静态、GUID 个属性统一归类于“基础属性”

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnXaagEhK5LMP02q60T1FLAc.png)

##### 数值修改

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnsFxzYeEWEBJiRehtaa4kzf.png)

- 数值基本都通过图中所示控件进行修改
- 按住输入框左右滑动可修改数值，也可以单击后直接输入
- 对于材质属性而言，编辑材质属性时，需要先自定义材质方可修改（生成一份材质描述文件至工程内容中）
- 当此材质资源引用了工程内容中的文件时，使用该材质的属性才可以在属性面板进行修改

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnaDIju8OwzoZrEFQeryXmd9.png)

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnMw5AQpNzUh45Nlo8wZMXUe.png)

##### 重置按钮

- 几乎所有属性都支持重置，修改属性后重置按钮会出现
- 重置会将此属性重置为**系统默认初始值**

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnCHhQ9VodRT5EQTuPoV5QVg.png)

##### 取色器

- 点击图中的颜色区域，打开取色器

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnMG9ICYB1bfQ8YGaKbDJEag.png)

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnnV81F3jybV4B184sTQQflf.png)

- 颜色修改操作

  - 取色器提供 RGBA 和 HSV**两种色彩模型，**一般来说，用户只需要调整 RGBA 或者 HSV 这两种色彩模型中的一个即可
  - 方式一：修改 RGBA 与 HSV 数值，可按住拖拽或者双击输入
  - 方式二：直接输入 16 进制颜色码
  - 方式三：单击或按住拖拽取色盘

    - 除了图中的圆形取色盘，点击下图按钮，可以切换至方形取色盘，用户可以根据自己的习惯进行选择

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn17bdTC3rLzUpghoStZls3f.png)

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcn0DtJ0hgxYdku9LMuyiUqjc.png)

- 新旧颜色对比

  - 旧颜色是指当前此颜色属性使用的颜色，新颜色是当前取色盘里的颜色，目的是**方便对比**

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnibDZvuGfRFflC9oWltCfhe.png)

- 自定义颜色

  - 用户可以将颜色从右侧“新旧颜色”**拖拽**至取色器顶部进行保存，**方便复用**

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnuV7xN4YFqKjYJnDC7BXr0d.png)

##### 吸管

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnP8yLCNhBG9ke70wYUivjve.png)

- 部分对象存在吸管控件，常见的如物理约束，也可以在脚本中定义吸管

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnxSmeVvd1z8u3OvsFLjna5e.png)

- 操作方式：单击图中吸管图标后，在主视口点击对象即可；同时还可以直接将对象从对象管理器中拖拽入框中
- 对于已吸取的对象支持定位功能，方便找到所吸取的对象在对象管理器中的位置
- 吸管下的框禁止输入，若想清空吸管对象，点击吸管按钮旁的重置按钮即可

##### 资源选择控件

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnDBHyjODC84UNbp3fn4gTuQ.png)

- 该控件目的是**用资源库/工程内容中的资源替换当前使用的资源**
- 操作方式：拖拽本地资源库/工程内容中相同类型的资源，可实现资源的使用；具体详情请用户查阅资源相关手册

##### 加减组件

- 点击右侧新增按钮，可新增该属性对应的结构体
- 点击某一结构体右侧的删除按钮，可删除该结构体

![](https://wstatic-a1.233leyuan.com/productdocs/static/boxcnBxpPDMJAudxgkrE6waBo2c.png)

##### 其他控件

- 除了上述几个控件之外，属性面板中还有一些常见的控件，如单选框、下拉框、文本输入框，操作简单，此处不再说明
