# WeChat ChatBot

## English

### Functions

* Automatically respond to messages containing keywords.
  * Ability to add / remove responses within messaging service.
* Automatically messages administrator when receiving a question (any message with a question mark).
  * Administrator response will be relayed back to the user.

### How to Use

1. [Clone repository.](https://github.com/junhecui/chatbot)
2. Set environment variables and connect to a SQL Database.
3. `npm install`
   * If program does not function correctly, try individually installing `wechaty`, `wechaty-puppet-wechat4u`, `qrcode-terminal`, `mysql`, `mysql2`.
4. Scan QR code with WeChat account user desires the bot to function on.
5. The bot will be ready to function.

### Instructions for Adding Keywords / Responses

When the program is running:

* `!add \<keyword> \<response>` will add a keyword paired with a response message to the database.
* `!editKeyword \<index> \<keyword>` will add new keywords paired with the response message at that specific index.
* `!editResponse \<index> \<response>` will change the response message at that specific index.
* `!remove \<index>` will remove the keyword - response pairing at that index.
* `!remove \<index> \<keyword>` will remove the specific keyword at that index.

## 简体中文

### 功能

* 自动回复包含关键字的消息。
  * 能够在消息服务中添加/删除回复。
* 收到问题时（任何带问号的消息）自动向管理员发送消息。
  * 管理员的回复将被转发给用户。

### 使用方法

1. [克隆仓库。](https://github.com/junhecui/chatbot)
2. 设置环境变量并连接到SQL数据库。
3. 运行 `npm install`
   * 如果程序运行不正常，尝试分别安装wechaty, wechaty-puppet-wechat4u, qrcode-terminal, mysql, mysql2。
4. 使用希望机器人运行的微信账号扫描二维码。
5. 机器人将准备就绪。

### 添加关键字/回复的说明

程序运行时：

* `!add <关键字> <回复>` 将添加一个关键字和一个回复消息到数据库。
* `!editKeyword <索引> <关键字>` 将在特定索引处添加新的关键字并配对相应的回复消息。
* `!editResponse <索引> <回复>` 将更改特定索引处的回复消息。
* `!remove <索引>` 将移除特定索引处的关键字-回复对。
* `!remove <索引> <关键字>` 将移除特定索引处的特定关键字。
