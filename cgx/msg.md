
## 消息总线

### 消息格式

```json
{
    "xid":"唯一编号",
    "date":"消息创建时间",
    "createAt":23423,/*创建时间戳*/
    "from":"消息来源",
    "to":"消息去向",
    "cc":"抄送",
    "expire":234123,/*过期时间戳*/
    "subject":"消息主题",
    "reply":false,/*是否要求回执*/
    "body":"消息正文",
    "addon":"附件",
    "mRead":false, /*已读标记*/
    "mAutoAddon":false, /*自动领取附件标记*/
    "mOpen":false /*已领附件标记*/
}
```


### 用户


