# 指标概念迁移

GrowingIO系统中页面级维度作为维度的图表和报表中，如果碰到下述指标，指标名称按照以下方式进行迁移

1. 访问量 **⇒ **进入量
2. 访问用户人均访问次数 **⇒ **访问用户人均进入次数
3. 平均访问时长（分钟）**⇒ **平均进入时长（分钟）
4. 每次访问页面浏览量 **⇒ **每次进入页面浏览量

## 示例1

如果使用了页面作为维度，访问量和访问用户量作为指标时，则按照如下方法进行自动迁移：

![](../../../.gitbook/assets/transition1.png)

在页面级维度的报表中，访问量将迁移为使用进入量，计算算法不变。同时GrowingIO提供一个新的访问量指标，这个访问量指标被页面级维度分解时指标的含义为：对当前页面级维度的当前元素有过页面浏览（一次或多次，至少一次）的访问的次数。

