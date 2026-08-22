# SOL MEMORIAL WEAR｜羽球少年

原生 HTML、CSS、JavaScript 的單頁預購網站。

## 本機檢視

直接以瀏覽器開啟 `index.html` 即可預覽。網站已連接新接單 Apps Script Web App。

## 素材

`images/` 由素材負責人維護：

- `night-rally-front.jpg`、`night-rally-back.jpg`
- `first-light-front.jpg`、`first-light-back.png`

## 已完成的接單設定

1. Apps Script 已設定為新接單流程：新版圖樣資料寫入 `R:S`，舊 `F:I` 欄位保持空白。
2. Google Sheet 與 Apps Script 時區均為 `Asia/Taipei`。
3. 購物車僅以本機儲存保留商品版本、尺寸與數量；姓名、手機、LINE ID、門市與同意狀態不寫入本機儲存。
4. 後端會驗證白名單規格、honeypot、格式與數量，並實施單一手機短時限流、每日接單上限及防重送。
5. 訂單個資分頁不公開；公開網站與版本庫不保存 Google Sheet 個資、付款帳號或敏感設定。
6. 付款資訊於訂單送出後由主辦聯繫提供；7-11 店到店訂單須提供門市名稱與店號。
