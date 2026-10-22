# Rubi’s Cluttered Corner

網站：[chiarubi-728.github.io](https://chiarubi-728.github.io/)

個人專案首頁整合卡蒂狗・風速狗圖鑑、App 與 PSN Game Catalog。App 先保留卡片與「尚未開放」停用按鈕，之後再提供使用或下載入口。

## 專案入口

- [卡蒂狗・風速狗圖鑑](https://chiarubi-728.github.io/PTCG-Growlithe-Catalog/)
- App：先顯示不可點擊的「尚未開放」按鈕，之後再提供公開使用或下載網址。
- [PSN Game Catalog](https://chiarubi-728.github.io/PSN_Game_Catalog/)

## 政策與 OAuth

總站 privacy.html 與 terms.html 分別說明首頁、圖鑑及 PSN Game Catalog，App 仍是停用入口。首頁只顯示資料用途摘要；PSN 的詳細資料揭露完整收錄於總站政策，原遊戲庫專屬政策頁保留。Google 資料用途明確限定 PSN Game Catalog。

- [總站隱私權政策](https://chiarubi-728.github.io/privacy.html)
- [總站使用條款](https://chiarubi-728.github.io/terms.html)
- [PSN 應用程式介紹](https://chiarubi-728.github.io/PSN_Game_Catalog/about.html)
- [PSN 隱私權政策](https://chiarubi-728.github.io/PSN_Game_Catalog/privacy.html)
- [PSN 服務說明](https://chiarubi-728.github.io/PSN_Game_Catalog/terms.html)

Google 品牌設定若使用總站首頁，隱私權政策可填 https://chiarubi-728.github.io/privacy.html ，使用條款填 https://chiarubi-728.github.io/terms.html ，以和首頁的主要政策連結一致；主控台需由擁有者儲存並依提示提交。

通用首頁名稱是個人專案品牌，不自動更換各 App 的名稱或 Google OAuth 品牌。Google 專案的首頁與政策設定由擁有者處理；PSN 專屬介紹頁持續保留，可用於清楚識別該應用程式。

首頁沿用同網域現有介紹頁的 Search Console 驗證 meta。發布首頁不代表已完成網域所有權或 OAuth 品牌驗證。

## 視覺風格

米色背景、淺橘按鈕與深棕文字；採較大的留白、細邊框及專案卡片。參考圖鑑的暖色感，但不沿用圖鑑的列表與操作介面。各專案分別以暖橘、灰綠、灰藍作小範圍點綴。

## 維護與發布

### 共用標誌

米色底、淺橘圓角方塊、深棕 R 與兩個角落框線。依已選定的圖案整理成可縮放的 SVG，PNG 由向量稿匯出；瀏覽器小圖示另外去除外圍米色留白，讓方塊填滿圖示、圓角外透明。

- `assets/rubi-corner.svg`：首頁標誌。
- `assets/favicon.svg`：去除留白、圓角外透明的瀏覽器圖示。
- `assets/favicon-32.png`：32 × 32 透明圓角瀏覽器圖示，與 favicon.svg 構圖相同。
- `assets/apple-touch-icon.png`：180 × 180 加到主畫面圖示。
- `assets/logo-512.png`：512 × 512 一般用途。
- `assets/google-logo-120.png`：120 × 120 Google 品牌設定用 PNG。

Google 標誌格式依 [官方說明](https://support.google.com/cloud/answer/15549049) 準備；此網站發布不會自動更換 Google Console 中的標誌，仍由擁有者上傳。各 App 的名稱及授權設定維持各自管理。

直接編輯 index.html 與 style.css；GitHub Pages 從 main 分支根目錄發布，.nojekyll 停用 Jekyll。沒有登入程式、不讀寫 Drive，也不自動導向登入頁。遊戲庫原網址、Client ID、JavaScript 來源與使用者存檔由原工具管理。

新增入口前確認名稱、用途及公開網址，避免連到私人專案。一般公開專案使用說明與政策應連到各專案的正式版本。


## 政策維護

總站政策中 PSN 章節依 PSN_Game_Catalog 在 4f8e23c 版本的正式政策完整整理。遊戲庫的資料處理方式改變時，需同步更新總站與專屬政策，避免內容不一致。維護者聯絡使用公開 GitHub 問題回報，不將私人信箱寫入網站。
