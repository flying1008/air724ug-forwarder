# Air724UG 短信转发 & 来电通知 & 语音信箱

## 项目介绍及使用教程

https://mizore.notion.site/air724ug-forwarder-227b5a41fa5f4be1bdd356275a31d277

默认支持websocket实时发送消息。如实际不支持时，请修改main.lua中websocket_enabled值。

通过gotify 发送消息时，需设置title为“sms”，（将gotify的app创建名称设置为"sms"时，在推送信息时，title可以不填写。默认为"sms"）

信息格式为：接收号码#信息内容。

如:10086#102

18888888888#你好

这里的#支持中英文。

gotify的配置，详见config.lua

