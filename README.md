<div align="center">

# 🐶 舔狗模拟器 · Simp Simulator

> **🐶 本项目通过100%纯野生代码证明：舔狗不得house但能得奖（蓝桥杯限定版）**
>
> *This project proves with 100% handcrafted code: simps don't get the girl, but they can win a prize. (Lanqiao Cup Edition)*

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](./LICENSE)
[![WeChat Style](https://img.shields.io/badge/Style-WeChat-07C160?style=flat-square&logo=wechat&logoColor=white)](https://github.com/timeRATE-966/weixin-SimpSimulator-LanqiaoCup)
[![Lanqiao Cup](https://img.shields.io/badge/Contest-蓝桥杯-blue?style=flat-square)](https://www.lanqiao.cn/)
[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-222?style=flat-square&logo=github)](https://timerate-966.github.io/weixin-SimpSimulator-LanqiaoCup/)

</div>

**🌐 在线演示 · Live Demo：[https://timerate-966.github.io/weixin-SimpSimulator-LanqiaoCup/](https://timerate-966.github.io/weixin-SimpSimulator-LanqiaoCup/)**

---

## 📖 项目简介 · About

一个仿微信聊天界面的网页小品，灵感来源于真实的互联网"舔狗"体验。  
用户扮演"舔狗"本狗，向心仪的"女神小美"发送消息——然而无论你发什么，消息旁边都会出现一个红色感叹号。**因为，她把你拉黑了。**

A tongue-in-cheek WeChat chat simulator inspired by real internet "simp" culture.  
You play the simp, sending messages to your crush "Goddess Xiaomei" — but every message you send comes with a red warning icon. **Because she blocked you.**

| 角色 / Role | 头像 / Avatar | 说明 / Notes |
|:---:|:---:|:---|
| 发送者 / Sender | 沸羊羊 🐏 | 你（舔狗本狗）/ You (the simp) |
| 接收者 / Receiver | 美羊羊 🐑 | 女神小美 / Goddess Xiaomei |

---

## ✨ 功能特性 · Features

- 🖼️ **仿微信 UI**：气泡样式、头像圆角、聊天背景图，高度还原微信风格  
  WeChat-style chat UI with authentic bubbles, rounded avatars, and background
- ⏰ **动态时间戳**：页面加载时自动更新为当前时间（两段时间节点）  
  Dynamic timestamps auto-updated to real current time on load
- 💬 **预置剧情对话**：拍了拍、图片消息、文字气泡，有完整叙事  
  Pre-set narrative: pat action, image messages, text bubbles with a full storyline
- ⚠️ **首次发送触发好友验证提示**，并在 1.75 秒后延迟出现表情回应  
  First message triggers friend-verification notice + delayed emoji reply after 1.75s
- 🔴 **核心效果：被拉黑**——所有发出消息均附带红色感叹号  
  Core mechanic: every outgoing message displays a red `!` warning icon (blocked effect)
- ⌨️ 支持 **Enter 键**发送消息  
  Supports sending messages via the **Enter key**

---

## 🚀 快速启动 · Quick Start

> 💡 **无需任何配置，直接在线体验** → [timerate-966.github.io/weixin-SimpSimulator-LanqiaoCup](https://timerate-966.github.io/weixin-SimpSimulator-LanqiaoCup/)  
> *No setup needed — just click the link above to try it live.*

### 方式一：直接打开（推荐）· Option A: Open directly (recommended)

```bash
# 克隆仓库 / Clone the repo
git clone https://github.com/timeRATE-966/weixin-SimpSimulator-LanqiaoCup.git

# 直接用浏览器打开 / Open in browser
open chat.html   # macOS
start chat.html  # Windows
```

或直接双击 `chat.html` 即可，**无需任何依赖**。  
Or just double-click `chat.html` — **zero dependencies required**.

### 方式二：Node.js 本地服务器 · Option B: Node.js local server

```bash
# 安装依赖 / Install dependencies
npm install

# 启动服务器 / Start server
node server.js
```

访问 / Visit → **http://localhost:10000/chat**

> Windows 用户也可双击 `(双击启动)舔狗模拟器.bat` 一键启动。  
> Windows users can also double-click `(双击启动)舔狗模拟器.bat` for one-click launch.

---

## 📁 项目结构 · Project Structure

```
weixin-SimpSimulator-LanqiaoCup/
├── index.html                   # 🔀 GitHub Pages 入口（重定向至 chat.html）/ Pages entry redirect
├── chat.html                    # 🌟 主界面（v1.3 最终版）/ Main page (v1.3 final)
├── server.js                    # Express 静态文件服务器 / Express static server
├── package.json                 # 项目依赖 / Project dependencies
├── (双击启动)舔狗模拟器.bat      # Windows 一键启动 / Windows one-click launcher
├── .gitignore
├── LICENSE
├── images/
│   ├── head1.png                # 发送者头像：沸羊羊 / Sender: Asterix 🐏
│   ├── head2.jpg                # 接收者头像：美羊羊 / Receiver: Weslie 🐑
│   ├── img1.png                 # 预置图片消息 1 / Pre-set image message 1
│   ├── img2.jpg                 # 预置图片消息 2 / Pre-set image message 2
│   ├── img3.png                 # 延迟回应贴图 / Delayed sticker reply
│   └── warning mark.png         # 🔴 红色感叹号 / Red warning icon
└── other/
    ├── CHANGELOG.md             # 版本迭代记录 / Full version history
    ├── chat1.html               # v1.1 历史版本 / v1.1
    ├── chat1.2.html             # v1.2 历史版本 / v1.2
    ├── chat1.3.html             # v1.3 草稿归档 / v1.3 archived draft
    └── ...                      # 其他开发草稿 / Other dev drafts
```

---

## 🛠️ 技术栈 · Tech Stack

| 技术 / Tech | 用途 / Usage |
|:---|:---|
| HTML5 + CSS3 | 界面结构与样式，纯手写零框架 / UI structure & styles, handcrafted, no framework |
| Vanilla JavaScript | 消息交互逻辑，零依赖 / Message interaction logic, zero dependencies |
| Node.js + Express | 可选本地静态文件服务器 / Optional local static file server |
| Socket.IO | 已引入备用，暂未启用 / Included as reserve, not yet active |

---

## 📜 版本历史 · Changelog

详见 [`other/CHANGELOG.md`](./other/CHANGELOG.md)

| 版本 | 主要变更 |
|:---:|:---|
| **v1.3** ✅ | 双时间戳动态更新、预填输入框、首次发送延迟优化至 1.75s |
| v1.2 | 完整预置对话、沸羊羊/美羊羊头像、被拉黑红色感叹号效果 |
| v1.1 | 消息列表内嵌预置内容 |
| v1.0 | 基础聊天 UI，纯动态消息，`prompt()` 获取用户名 |

---

## 🏷️ 推荐 Topics 标签 · Suggested Repository Topics

`html` `css` `javascript` `wechat` `chat-ui` `weixin` `lanqiao-cup` `beginner` `frontend` `simulator` `vanilla-js`

> 可在仓库页面右上角「About」→「Topics」处添加，有助于搜索发现。  
> Add these in repo **About → Topics** to improve discoverability.

---

## 🎓 开发背景 · Background

大一上学期备战**蓝桥杯 Web 赛道**时的练手作品。  
选题源于对"舔狗文化"的观察与调侃——用一个仿微信界面把这种尴尬处境可视化。  
红色感叹号是整个作品的灵魂，是对"发出去的消息石沉大海"这一互联网经典体验的具象化。

Built as a practice project during freshman year while preparing for the **Lanqiao Cup Web track**.  
The concept came from observing and poking fun at "simp culture" online — visualizing that awkward situation through a WeChat-style interface.  
The red warning icon is the soul of the piece — a tangible representation of the classic internet experience: messages sent into the void.

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).

---

<div align="center">

*📝 本 README 由 [Claw](https://github.com/openclaw/openclaw) AI 辅助生成，内容经作者审阅确认。*  
*📝 This README was generated with assistance from [Claw](https://github.com/openclaw/openclaw) AI and reviewed by the author.*

<br/>

如果这个项目让你会心一笑，欢迎点个 ⭐  
*If this made you smile, a ⭐ would be appreciated.*

</div>
