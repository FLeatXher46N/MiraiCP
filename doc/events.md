# 事件列表 #
这些内容可以在`MiraiCP\kotlin\src\main\kotlin\Config.kt`看到
| 事件名称 | 函数名称         | 参数内容                                                       |
|---------|-----------------|----------------------------------------------------------------|
| 插件启用 | onEnable         | None                                                          |
| 插件结束 | onDisable        | None                                                          |
| 群聊消息 | GroupMessage     | groupid: Long, senderid: Long, message: String, type: Int = 1 |
| 私聊消息 | PrivateMessage   | senderid: Long, message: String, type: Int = 2                |
| 好友申请 | NewFriendRequest | friendid: Long, message: String, type: Int = 4                |
| 群聊邀请 | GroupInvite      | groupid: Long, invitorid: Long, type: Int = 3                 |
| 新群成员加入 | MemberJoin       | groupid: Long, memberid: Long, invitorid: Long, jointype: Int, type: Int = 5,                 |
