# Deskgram 2 受众收集

![Audience Parser Main](assets/screenshots/collect-audience__main__zh.png)

受众收集是 Deskgram 2 中用于从 Telegram 群组、聊天和相关来源整理用户基础的模块。它帮助你把后续私信、邀请和订阅场景需要的受众数据准备成可继续使用的结构。

[Deskgram 2 中文总览](https://github.com/Deskgram-2/deskgram-2-telegram-automation-zh) | [官网](https://deskgram2.com/) | [Telegram Bot](https://t.me/DG2welcomebot) | [Web Preview](https://deskgram2.com/web-preview)

## 模块简介

| 参数 | 内容 |
|---|---|
| 核心任务 | 从 Telegram 群组和聊天收集用户 |
| 收集对象 | 群成员、聊天活跃用户或其他相关来源 |
| 适用场景 | 私信触达、邀请流程、受众整理 |
| 关键价值 | 在执行前先拿到结构化受众基础 |
| 关联模块 | 私信群发、批量订阅 |

## 模块能力

- 从 Telegram 群组和聊天中收集用户；
- 对结果应用过滤条件；
- 输出适合后续流程使用的受众基础；
- 为私信、邀请或订阅流程提供前置数据；
- 保留日志和执行结果。

## 快速开始

1. 选择来源群组、聊天或目标范围。
2. 配置过滤规则。
3. 运行收集流程并检查结果。
4. 将整理好的基础继续用于私信群发或批量订阅。

## 收集之后可以怎么走

- [私信群发](https://github.com/Deskgram-2/telegram-direct-messaging-deskgram-zh)，如果这批受众要进入私聊触达。
- [邀请模块](https://github.com/Deskgram-2/telegram-invite-tool-deskgram-zh)，如果这批基础将用于频道或群组增长。
- [账号面板](https://github.com/Deskgram-2/telegram-account-manager-deskgram-zh)，如果还需要整理执行账号层。
- [批量订阅](https://github.com/Deskgram-2/telegram-join-groups-deskgram-zh)，如果下一个阶段需要先准备环境。

## 界面亮点

### 主界面

![Audience Parser Main Screen](assets/screenshots/collect-audience__main__zh.png)

### 过滤规则

![Audience Filters](assets/screenshots/collect-audience__filters__zh.png)

### 日志与结果

![Audience Logs](assets/screenshots/collect-audience__logs__zh.png)

## 适合在什么情况下使用

- 当后续工作流依赖可用的用户基础；
- 当你需要先收集再触达，而不是直接发送；
- 当你希望把受众整理和执行模块分开；
- 当多个场景需要复用同一批受众数据。

## 相比手动整理更方便的地方

| 手动方式 | Deskgram 2 受众收集 |
|---|---|
| 受众信息零散且难整理 | 模块输出结构化基础 |
| 过滤过程不稳定 | 过滤规则可重复使用 |
| 后续流程衔接麻烦 | 能直接连接到私信或订阅模块 |
| 重复收集效率低 | 工作流更适合持续使用 |

## 相关仓库

- [Deskgram 2 中文总览](https://github.com/Deskgram-2/deskgram-2-telegram-automation-zh)
- [私信群发](https://github.com/Deskgram-2/telegram-direct-messaging-deskgram-zh)
- [批量订阅](https://github.com/Deskgram-2/telegram-join-groups-deskgram-zh)
- [邀请模块](https://github.com/Deskgram-2/telegram-invite-tool-deskgram-zh)
- [账号面板](https://github.com/Deskgram-2/telegram-account-manager-deskgram-zh)

## FAQ

### 收集完成后最自然的下一步是什么？

通常是进入私信群发或邀请场景。

### 这个模块只适合营销吗？

不只如此。只要后续流程依赖受众基础，它就有价值。
