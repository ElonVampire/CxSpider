# WanPlus英雄联盟场次详细信息爬虫文档

> 当前爬虫已失效！！！

**爬虫类型**：单次运行爬虫

**爬虫依赖第三方模块**：crawlertool、bs4

**爬虫功能**：采集WanPlus英雄联盟指定场次的详细信息

* 目标Url(实际请求的Ajax)：https://www.wanplus.com/ajax/matchdetail/65029?_gtk=345357323

**爬虫参数**：

| 参数名   | 参数功能                                                |
| -------- | ------------------------------------------------------- |
| race_id  | 比赛ID（可通过WanPlus英雄联盟每日比赛列表爬虫采集）     |
| match_id | 场次ID（可通过WanPlus英雄联盟比赛包含场次列表爬虫采集） |

**爬虫返回结果数据**：

| 字段名       | 字段内容               |
| ------------ | ---------------------- |
| race_id      | 比赛ID                 |
| match_id     | 场次ID                 |
| match_detail | Json格式的场次详细信息 |

**创建时间**：2020.04.20

**修改时间**：2020.12.28