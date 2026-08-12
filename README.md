# invoice-progress-tracker
發票進度追蹤系統第 12 版完整可遷移原始碼

## v12 更新
- 新增 Google Drive／JSON 備份還原功能
- 還原前驗證 JSON 格式與客戶筆數，並要求確認覆蓋
- 新增「清除所有資料」按鈕與「確認清除嗎？」二次確認
- 保留 Cloudflare D1 共用資料庫與 Excel 匯入／匯出功能

> 此封包只包含原始碼與資料庫結構，不包含線上客戶資料、憑證或正式環境 secrets。
