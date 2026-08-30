# my-classroom-tools — 我的班級工具總專案

## 對話開始時請先讀
進度與最近更動都在 Obsidian：`2ndbrain/my-classroom-tools/工作筆記.md`

## 關於我
- 國小五年級數學老師
- 程式初學者：說明用繁體中文、短句、白話
- 每次只處理一件事，不要一次給太多步驟

## 工作模式
- **加新工具**：說「我想做一個 XXX 工具」→ 建 `tools/<工具名>/` 子資料夾、引導跟著 EP10 影片做
- **結束工作**：說「**收工**」→ 自動 commit + push + 更新 Obsidian 工作筆記
- **接續工作**：說「**開工**」或「讀工作筆記、告訴我上次做到哪」

## 工作桌 + 三個家
- 📋 GDrive 工作桌：`我的雲端硬碟/my-classroom-tools/`（自動跨電腦同步）
- 🐙 GitHub repo：https://github.com/cb10220219/my-classroom-tools （public，網頁的家）
- 📘 Obsidian 駕駛艙：`2ndbrain/my-classroom-tools/工作筆記.md`（想法的家）
- 🔥 Firebase 專案：（待決定，資料的家）

## 分工原則
- **檔案內容**：Claude 直接寫
- **上傳 / 刪除**：Claude 給指令，老師在 Mac 終端機貼上執行
  （Claude 沒有 GitHub 憑證，也沒有刪除權限）

## 工具清單
（之後加新工具時會自動更新）
- （尚無）

## 工作注意事項
- 學生資料一律去識別化（只用座號 + 班級代號）
- commit 訊息要寫清楚做了什麼 + 為什麼
- `.claude/` 絕不 commit（可能含 token）
- API Key 不要寫死在 HTML（Firebase Config 例外，那設計可公開）
- 收工前說「收工」讓 Claude 同步三方
