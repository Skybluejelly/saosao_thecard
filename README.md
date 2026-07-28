# 扫扫：内老大前端

`saosao_neilao-v0.1.1` 是扫扫大前端角色卡的当前公开测试版。该版修复了 CDN 环境下开局向导和正式前端无法连接酒馆桥接的问题。

## 下载

- [下载扫扫_v0.1.1.json](https://github.com/Skybluejelly/saosao_thecard/raw/refs/tags/saosao_neilao-v0.1.1/扫扫_v0.1.1.json)

## 使用

1. 在已安装酒馆助手的 SillyTavern 中导入 `扫扫_v0.1.1.json`。
2. 新建聊天并打开第一条消息中的开局向导。
3. 完成开局设定后进入扫扫大前端。

前端、宿主脚本和 MVU 变量结构均由卡内固定版本的 CDN 地址加载，不需要在本机运行预览服务器。每个聊天使用独立的聊天世界书保存开局、社区状态和 NPC 资料。

## 发布内容

- `扫扫_v0.1.1.json`：可导入的 V3 JSON 角色卡。
- `dist/扫扫/index.html`：正式大前端。
- `dist/扫扫/开局设定/index.html`：开局向导。
- `dist/扫扫/角色卡/脚本`：变量结构与酒馆桥接脚本。

## 版本

- 卡版本：`0.1.1`
- Git tag：`saosao_neilao-v0.1.1`
