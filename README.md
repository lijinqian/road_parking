# 简介
路边停车收费平台包含数据采集系统、车主用户系统、运营管理系统、收费员辅助系统和数据展示系统。前端接入地磁、低位视频杆、高位像机、数据大屏、车位诱导屏、手持PDA等设备，后端服务对数据进行清洗、整理并转化成停车订单，以订单数据为核心，向各子系统输出数据。


该项目已迁移到https://gitee.com/lijinqian/road-park?_from=gitee_search

# 软件技术栈
maven架构，springmvc + spring + mybatis + mysql + dubbo + druid， redis缓存，管理后台前端html+js+css，微信小程序原生代码，android原生代码。

# 系统功能
| 序号  | 系统  | 简介  |
|---|---|---|
| 1  |  运营管理系统 | B/S架构、支持各主流浏览器。功能包括登录、权限管理、基础数据管理，实时监控、看板视图、订单管理、停车场管理、收费价格表设置、优惠活动、参数配置、文档管理、反馈处理、设备管理、分区、道路、停车场管理、运营管理、统计分析、收费员管理等  |
| 2  |  用户小程序（微信） | 内嵌于微信的微应用，无需下载，跨平台，低门槛使用。功能包括用户授权注册，车位查询、导航、停车缴费（车牌付、ETC支付、微信支付、扫码付、现金支付）、钱包充值、车牌管理、停车订单查询、建议反馈、申诉、发票申请等  |
|  3 | 运营辅助系统  |  在PDA设备上运行的Android应用，辅助现场收费员处理现场问题、收费、创建停车单、异常上报、欠费追缴、发票发放 |
|  4 |  数据采集系统 | 接入地磁、低位视频杆、高位视频杆、出入口闸机等设备，采集车位、车辆车牌信息  |
|  5 |  设备控制系统 | 向设备发送控制指令（视频杆拍照、闸机开关闸、车位开闭锁、诱导屏信息输出、车位指示灯控制） |
|  6 |  微停车系统（微信公众号） | 向用户推送入场、离场、消费、欠费、反馈回复模板消息、提供便捷停车缴费功能和停车订单查询等功能。  |
|  7 |  停车诱导系统 | 管理诱导设备信息，支持道路分叉口电子屏上输出实时车位信息和道路导向  |
|  8 |  开放网关系统 | 与交巡警系统、智慧城市系统、税务系统、征信系统对接，遵循接口规范，进行数据传输、推送  |
|  9 |  数据大屏系统 | 提供停车可视化，停车数据如空置率、周转率、营收等一目了然，给领导决策提供便利。  |
|  10 |  周报系统 | 对上周停车数据的汇总，对于有疑问的停车及时申诉  |
