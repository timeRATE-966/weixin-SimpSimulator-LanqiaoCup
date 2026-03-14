# 版本历史 · Changelog

> 记录"舔狗模拟器"从草稿到参赛作品的完整迭代过程。  
> Documents the full iteration from drafts to the competition submission.

---

## v1.3（最终参赛版 / Final Competition Version）→ `../chat.html`

**新增 / Added**
- 两段时间戳同时动态更新（当前时间 & 当前时间 −20 min）  
  Two dynamic timestamps: current time & current time minus 20 minutes
- 输入框预填"删好了叫我"，强化剧情代入感  
  Input pre-filled with "删好了叫我" for stronger narrative immersion

**改进 / Improved**
- 首次发送延迟从 2000ms 缩短至 1750ms，节奏更自然  
  First-send delay reduced from 2000ms to 1750ms for smoother pacing

---

## v1.2 → `chat1.2.html`

**新增 / Added**
- 完整预置对话（拍了拍 + 图片消息 + 文字气泡）  
  Full pre-set conversation: pat action, image messages, and text bubbles
- 沸羊羊（发送方）/ 美羊羊（接收方）头像正式上线  
  Asterix (sender) / Asterix's girlfriend (receiver) avatars introduced
- 首次发送触发"好友验证"提示 + 延迟回应图片  
  First send triggers friend-verification notice + delayed reply image
- 消息气泡旁附带红色感叹号（被拉黑核心效果）  
  Red warning icon next to every sent bubble (the "blocked" core effect)
- 聊天背景图（知乎壁纸）  
  Chat background image added

---

## v1.1 → `chat1.html`

**新增 / Added**
- 消息列表内嵌预置内容，不再纯动态生成  
  Pre-set message content embedded in HTML structure

---

## v1.0 → `聊天页面.html` / `chat__废稿2.html`

**初始版本 / Initial Version**
- 基本聊天界面（输入框 + 发送按钮 + 消息列表）  
  Basic chat UI: input box, send button, message list
- 通过 `prompt()` 获取用户名  
  Username collected via `prompt()`
- 纯动态生成消息，无预置内容  
  Fully dynamic messages, no pre-set content

---

## 废稿 / Drafts

| 文件 / File | 说明 / Notes |
|---|---|
| `参考1.html` | 早期布局参考 / Early layout reference |
| `聊天div参考.html` | div 结构草稿 / div structure draft |
| `聊天页面(女神版)__废稿1.html` | 女神视角废稿 / Abandoned "goddess perspective" draft |
| `chat__废稿2.html` | v1.0 过渡废稿 / v1.0 transition draft |
