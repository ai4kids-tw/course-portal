# AI4Kids 我的課表

老師與家長查看自己課表的前端頁面，在 LINE 內開啟（LIFF）。

- **後端**：Google Apps Script（`parent-comms-integration` 專案）
- **資料**：排課系統試算表，由後端讀取
- **身分**：LINE 登入取得 userId，後端查「聯絡人對照表」決定角色

## 安全前提

這個 repo 是公開的，所以：

- **不放任何金鑰、學員資料、聯絡資料**
- LIFF ID 與 GAS Web App 網址不是機密，可以放
- 所有資料都經後端取得；後端只回傳呼叫者本人的課次，不回傳 email 或電話

## 部署

推到 `main` 即由 GitHub Pages 自動發布。
