# SOL MEMORIAL WEAR｜羽球少年

原生 HTML、CSS、JavaScript 的單頁預購網站。

## 本機檢視

直接以瀏覽器開啟 `index.html` 即可預覽。正式發布前，請將 `index.html` 中的 `APPS_SCRIPT_URL` 替換為新接單 Apps Script Web App URL；placeholder 存在時，表單會明確顯示「接單系統準備中」並拒絕送出。

## 素材

`images/` 由素材負責人維護：

- `night-rally-front.jpg`、`night-rally-back.jpg`
- `first-light-front.jpg`、`first-light-back.png`

## 部署前檢查

1. 確認 Apps Script 寫入新 Sheet 的 `R:S` 欄位，且舊 `F:I` 保持空白。
2. 將 Sheet 與 Apps Script 時區設為 `Asia/Taipei`。
3. 以手機與桌面完成兩款、多尺寸、運費、驗證與重送測試。
4. 確認 Google Sheet 未公開含個資的訂單分頁。
