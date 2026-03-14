# 舔狗模拟器 · weixin-SimpSimulator-LanqiaoCup

> 🐶 本项目通过100%纯野生代码证明：舔狗不得house但能得奖（蓝桥杯限定版）
>
> 🐶 This project proves with 100% handcrafted code: simps don't get the girl, but they can win a prize (Lanqiao Cup Edition).

---

## 项目简介 · About

一个仿微信聊天界面的网页小品，灵感来源于真实的互联网生活体验。  
用户扮演"舔狗"本狗，向心仪的"女神小美"发送消息——然而无论你发什么，消息旁边都会出现一个红色感叹号。因为，她把你拉黑了。

A tongue-in-cheek WeChat chat simulator born from real internet life.  
You play the role of the "simp", sending messages to your crush "Goddess Xiaomei" — but every single message you send comes with a red warning icon. Because she blocked you.

- **发送者头像 / Sender avatar**：沸羊羊（Asterix） 🐏  
- **接收者头像 / Receiver avatar**：美羊羊（Weslie） 🐑  
- **核心效果 / Core mechanic**：每条消息附带红色感叹号，象征被拉黑  
  Every sent message carries a red `!` icon — the "blocked" effect

---

## 功能特性 · Features

- 🖼️ 仿微信聊天界面，气泡样式、头像、背景图高度还原  
  WeChat-style chat UI with authentic bubbles, avatars, and background
- ⏰ 动态时间戳，自动显示当前时间  
  Dynamic timestamps auto-updated to current time on load
- 💬 预置剧情对话（拍了拍 + 图片消息 + 文字气泡）  
  Pre-set narrative conversation: pat action, image messages, text bubbles
- ⚠️ 首次发送触发"好友验证"提示，并延迟出现表情回应  
  First message triggers a friend-verification notice, followed by a delayed emoji reply
- 🔴 所有发出的消息旁均附带红色感叹号（被拉黑核心效果）  
  All outgoing messages display a red warning icon (the blocked effect)
- ⌨️ 支持 Enter 键发送  
  Supports sending messages with the Enter key

---

## 快速启动 · Quick Start

### 方式一：直接打开（无需服务器）· Option A: Open directly (no server needed)

直接用浏览器打开 `chat.html` 即可体验。  
Simply open `chat.html` in any browser.

### 方式二：Node.js 本地服务器 · Option B: Node.js local server

```bash
# 安装依赖 / Install dependencies
npm install

# 启动服务器 / Start server
node server.js
```

然后访问 / Then visit：[http://localhost:10000/chat](http://localhost:10000/chat)

也可双击 `(双击启动)舔狗模拟器.bat` 一键启动（Windows）。  
Or double-click `(双击启动)舔狗模拟器.bat` for one-click launch (Windows).

---

## 项目结构 · Project Structure

```
weixin-SimpSimulator-LanqiaoCup/
├── chat.html                   # 主界面（v1.3 最终版）/ Main page (v1.3 final)
├── server.js                   # Express 静态服务器 / Express static server
├── package.json
├── (双击启动)舔狗模拟器.bat     # Windows 一键启动脚本 / Windows launcher
├── images/
│   ├── head1.png               # 发送者头像：沸羊羊 / Sender avatar: Asterix
│   ├── head2.jpg               # 接收者头像：美羊羊 / Receiver avatar: Weslie
│   ├── img1.png                # 预置图片消息 1 / Pre-set image message 1
│   ├── img2.jpg                # 预置图片消息 2 / Pre-set image message 2
│   ├── img3.png                # 延迟回应图片 / Delayed reply image
│   └── warning mark.png        # 红色感叹号图标 / Red warning icon
└── other/
    ├── CHANGELOG.md            # 版本迭代记录 / Version history
    ├── chat1.html              # v1.1 历史版本 / v1.1 historical version
    ├── chat1.2.html            # v1.2 历史版本 / v1.2 historical version
    ├── chat1.3.html            # v1.3 历史版本（归档）/ v1.3 archived draft
    └── ...                     # 其他草稿 / Other drafts
```

---

## 技术栈 · Tech Stack

| 技术 / Tech | 说明 / Notes |
|---|---|
| HTML / CSS | 纯手写，无框架 / Handcrafted, no framework |
| Vanilla JavaScript | 原生 JS，无依赖 / Pure JS, zero dependencies |
| Node.js + Express | 可选本地服务器 / Optional local server |
| Socket.IO | 已引入备用，暂未启用 / Included but not yet active |

---

## 版本历史 · Changelog

详见 [`other/CHANGELOG.md`](./other/CHANGELOG.md)

See [`other/CHANGELOG.md`](./other/CHANGELOG.md) for full version history.

---

## 开发背景 · Background

大一上学期备战蓝桥杯 Web 赛道时的练手作品。  
选题源于对"舔狗文化"的观察与调侃——用一个仿微信界面把这种尴尬处境可视化，红色感叹号是整个作品的灵魂。

Built as a practice project during the first semester of freshman year while preparing for the Lanqiao Cup Web track.  
The concept came from observing and poking fun at "simp culture" online — visualizing that awkward situation through a WeChat-style interface. The red warning icon is the soul of the whole piece.

---

## License

MIT
