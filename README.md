# 进击的 RSS
进击的 RSS 是一个 RSS 订阅工具，它会在每天中午 12 点采集昨天中午 12：00 到今天中午 12：00 指定的 RSS 链接产生的新的文章，并通过 tg bot 推送至指定的频道。

## 项目使用姿势

### TG Bot 创建
添加 `@BotFather` 机器人，注册一个 bot，记录下 bot 的 token  

### TG Channel 创建
创建一个 Channel，添加之前创建的 bot 为管理员，添加方式：  
点击频道右上角的`管理频道 - 管理员 - 添加管理员`，搜索你创建的 bot 名称，将其添加为管理员即可，发送消息的权限必须赋予，其他权限可选。  

[点此登陆](https://web.telegram.org) 网页版 telegram。点击你刚才创建的频道，链接格式类似 `https://web.telegram.org/#/im?p=cxxx_ppp` ，`-110xxx` 为你的频道 ID，记下它，之后要用到。  

### github 配置
克隆本仓库，在仓库的 `Settings-Secrets` 新增两个字段 `BOTTOKEN` 和 `CHANNELID`，他们的值分别是你的 bot token 和频道 ID。


### RSS 源添加
