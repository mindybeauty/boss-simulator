# 主管對話模擬器 / Boss Conversation Simulator

職場對話模擬遊戲 — 用 Claude API 演主管、練升職。

## 線上試玩

👉 **https://mindybeauty.github.io/boss-simulator/**

## 玩法

1. 選一個主管原型（或自訂你真實的主管）
2. 選任務（週一晨會 → 週五約談，5 關串成一週）
3. 對話、看主管反應、靠對話發現主管的隱藏喜好與雷點
4. 撐到通關 = 升職；五關全破 = 全週通關

## AI 模式（強烈建議）

純規則版能玩,但主管會像機器人。接 Claude API 後人格立刻立體。

1. 到 [console.anthropic.com](https://console.anthropic.com) 拿你自己的 API Key
2. 開遊戲、按 ✨ AI 版
3. 貼上 key、按「測試連線」
4. 開始模擬

> ⚠️ Key 只存在你瀏覽器的 localStorage,不會傳到任何伺服器。
> 但**別把 key 貼進公開文件或 chat 視窗**。

## 成本

- Haiku 4.5（預設）:每回合約 0.001 USD,一整關約台幣 1-2 元
- Sonnet 4.6（更會演戲）:每回合約 0.005 USD,一整關約台幣 5 元

## 模式

- 🎯 **任務模式**:5 關串成「上班週」,有明確 mission 與回合上限
- 🗨️ **沙盒模式**:自由聊,好感度 100 升職、0 打入冷宮

## 主管原型

- 👔 老派威權型（摩羯)
- 🎨 文青設計總監（雙魚)
- 🤝 政治家業務 VP（獅子)
- 📊 重數據工程師型（處女)
- 😊 老好人裝甲型（天蠍)
- ✏️ 自訂主管（輸入你真實主管的設定來練實戰)

## 技術

- 純前端 HTML（沒有後端）
- Claude API 直連（browser fetch + `anthropic-dangerous-direct-browser-access`)
- localStorage 存進度、自訂主管、API key

## 開發者

Made with Claude Code by [@mindybeauty](https://github.com/mindybeauty)
