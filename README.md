# doll_trip 🌸

帶娃出門·記錄日常 — 為台灣 Z 世代設計的曬娃儀式平台 prototype。

**[👉 Live demo](https://everydayadventuredev.github.io/doll-trip/)**

## 這是什麼

doll_trip 是服務「帶角色出門記錄日常」儀式（推し活 / ぬい撮り / 帶娃出門）的 vertical-niche 平台原型。

核心 wedge 是 IG / Threads / X 做不到的事：以 `Character × Location × Moment` 為主鍵的結構化跨地區探索——例如「鏡音リン 在台灣被 N 位推主帶去過 M 個地點」、「KAMI 神社咖啡有哪些 IP 來過」這種雙向 join 的查詢。

## 主流程

1. **我的紀錄**（首頁）：你的娃 row + 新打卡 CTA + 你的紀錄 + 今日推薦 + 徽章
2. **➕ 新打卡**：上傳曬娃照、選角色（含「+ 新增你的娃」上傳自己的娃）、選地點（含 GPS mock）、選 vibe、AI 修圖 toggle、發布
3. **探索**：跨城提示、熱門角色、友善地點、社群打卡

## prototype 限制

- 純前端 mock（無後端、無 auth、無 AI）
- 單一 `index.html`、零本地依賴（CDN：Tailwind、Alpine.js、Google Fonts）
- 所有資料為 mock data；新增的娃娃和打卡僅存在 session
- 隨機照片來自 Flickr 公開 API（首次載入會略慢）

## 試一下

1. 點 [Live demo](https://everydayadventuredev.github.io/doll-trip/)
2. 我的紀錄 hero → 點 **「+ 加入娃」** 上傳一張你娃娃的照片
3. 點底部 **➕** → 上傳曬娃照（你的娃會浮在右下角）→ 發布
4. 看你發布的紀錄出現在第一張 → 切「探索」看 cross-discovery

## 給回饋

歡迎開 issue 或直接 DM 作者。對「帶娃出門 / 推し活 / 小卡擺拍」有興趣的台灣朋友，特別歡迎使用體驗反饋。

---

Generated 2026-04-30 · iterating with Claude Code
