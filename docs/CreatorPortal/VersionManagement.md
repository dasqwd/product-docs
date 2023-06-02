# 游戏版本管理

::: tip 阅读本文大概需要15分钟

本文将帮助您上手游戏版本管理功能，包含版本ABTest、手动上下线。

::: 

![img](https://arkimg.ark.online/1684028257005-124.webp)

您每次点击发布&更新，便会形成一个游戏版本，可在【我的游戏】-【版本管理】查看每个游戏的版本列表。

## 版本管理

### 游戏发布设置

创作者中心发布游戏时，需要勾选发布的是**立即上线**还是**手动上线。**

![img](https://arkimg.ark.online/1684028257005-125.webp)

- **立即上线**：审核通过后会显示【上线】状态，表示该版本已经发布到233乐园；
- **手动上线**：审核通过后会显示【等待发布】状态，可以配置版本实验或按照自己想要的时间手动点击上线；

![img](https://arkimg.ark.online/1684028257005-126.webp)

若该版本开启了版本实验，则会显示【灰度测试中】，详见[游戏版本实验](https://docs.ark.online/CreatorPortal/VersionManagement.html#版本实验)

### 如何下线游戏

![img](https://arkimg.ark.online/1684028257005-127.webp)

点击目前上线的版本（除版本实验外，一个游戏仅会存在一个上线版本），即可下线游戏；

## 版本实验

版本实验是为了方便创作者有效迭代游戏，可通过游戏启动时分发不同的游戏版本，进行版本实验，但进行实验的游戏版本必须要发布于同一个编辑器引擎。

### 开启版本实验

![img](https://arkimg.ark.online/1684028257005-128.webp)

审核通过后，【版本列表】可以看到游戏状态，存在一个【上线】+ 一个【等待发布】，即可开启实验。

::: warning 实验过程中，是否可以添加新的版本？

- 不可以！实验过程中，为了实验准确性，该游戏不可以有新版本上线或下线，会提示你先去关闭实验，关闭实验就可以正常操作游戏下线了；
- 如果这个游戏正在实验中，再发布一个立即上线的版本，审核通过后也不会立即上线，是**等待发布**的状态，需要实验关闭后，再去手动操作上线；

::: 

![img](https://arkimg.ark.online/1684028257005-129.webp)

可以通过【游戏服务】-【[版本实验](https://portal.ark.online/#/admin/ab-test-list)】查看当前游戏的实验列表并对实验进行操作。

### 设置版本实验

实验信息包含要做实验的游戏、实验名称、实验描述、实验时长等，其中最关键的是选择核心指标。

> 核心指标帮助判定实验是否符合预期的效果，只有能计算置信水平的指标，才能用作核心指标。

![img](https://arkimg.ark.online/1684028257005-130.webp)

::: danger **实验过程中的核心指标选什么？**

建议根据本次实验的目的设置核心指标，鉴于指标本身属性，仅部分指标可以设置为核心指标。例如性能相关，就可以设置平均帧率、延迟作为核心指标；若想以玩家行为作为核心指标，就可以设置人均游戏次数。

::: 

实验参数主要是设置要进行实验的版本、流量分配，设置完点击调试实验。

![img](https://arkimg.ark.online/1684028257005-131.webp)

调试成功后，会来到实验列表页面，调试中的实验可以去修改实验配置，点击开始实验，设置的版本开始下发。

![img](https://arkimg.ark.online/1684028257005-132.webp)

实验开启后，在游戏列表页面，再看自己原来的两个版本，【等待发布】的版本会变成【灰度测试中】

### **查看实验报告**

实验报告提供游戏版本迭代依据，可查看实验报告后决策上线哪个游戏版本。

![img](https://arkimg.ark.online/1684028257005-133.webp)

实验开始后会在次日早上九点更新数据报告，点击查看报告即可查看实验数据。

![img](https://arkimg.ark.online/1684028257005-134.webp)

其中包含实验不同版本的用户进组情况占比、版本说明，以及实验设置里核心指标的置信程度。

![img](https://arkimg.ark.online/1684028257006-135.webp)

也可以继续查看实验版本的其他实验指标、新用户&活跃用户的留存情况。

![img](https://arkimg.ark.online/1684028257006-136.webp)

实验结束后，游戏分发会回到实验开始前，即原来是1.1.8是上线版本，那么结束实验这个版本还会是全量在线，需要根据实验的结果，调整版本的上下线。