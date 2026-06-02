# 📒 工作事件簿（work-log）

> 🍀 Tarshar 2026 工作坊 的其中一個專案

這個資料夾是「工作事件簿」的家：把每一個做過的專案做成一則紀錄，左側目錄可點選切換、右側看內容。

🔗 **線上觀看：** https://tarshar4242.github.io/ai-kaiji-luzhou/work-log/

## 這個資料夾裝了什麼

| 檔案 | 用途 |
|---|---|
| `index.html` | 工作事件簿本體：左側目錄、右側 iframe 顯示內容 |
| `01-ai-assistant-team.html` | 第 01 則事件 — 一人工作室・AI 助理團隊 |

之後的事件就是 `02-xxx.html`、`03-xxx.html` … 一直往下加。

## 怎麼新增一則事件

1. 把新的 HTML 放進這個資料夾，命名 `NN-名稱.html`（例如 `02-line-bot.html`）。
2. 打開 `index.html`，找到左側目錄的 `<nav id="nav">`，複製一段現有的 `<a class="item">`，改成新的編號、標題、說明，並把 `href` 與 `data-src` 指向你的新檔名。
3. 推上 GitHub，GitHub Pages 約 1～2 分鐘自動更新，網址不變。

> 不想自己動手也可以：直接把 HTML 交給小D教練的 Claude，說「加到工作事件簿」，會自動放好、接上目錄並上線。

---

<sub>© Learn AI with Tarshar．教學用途，歡迎參考引用，使用時請註明出處。</sub>
