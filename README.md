# Mon Parcours｜法日雙語自學網站

這是以《法日雙語自學專案_總綱.md》為基礎的第一版靜態網站。

## 本地使用

直接用瀏覽器開啟 `index.html`。建議正式使用時透過 HTTPS 網址部署。

## 部署方式 A：GitHub Pages

1. 登入 GitHub，新增 Public 或 Private repository（例如 `mon-parcours`）。
2. 將 `index.html` 上傳至 repository 根目錄並提交。
3. 前往 Settings → Pages → Build and deployment，Source 選 Deploy from a branch；Branch 選 `main`，資料夾選 `/ (root)`。
4. 儲存後等待部署完成，GitHub 會在 Pages 設定頁提供網站網址，一般格式為 `https://你的帳號.github.io/mon-parcours/`。

## 部署方式 B：Netlify Drop

1. 登入 Netlify。
2. 找到新增站點／手動部署入口（Netlify Drop），拖入解壓後包含 `index.html` 的網站資料夾。
3. 網站部署成功後，使用 Netlify 提供的網址開啟。

## 資料保護與限制

- 本版以瀏覽器 `localStorage` 儲存任務、筆記和測驗紀錄。不同瀏覽器／裝置不會自動同步。
- 在網站「資源與設定」中可匯出 JSON 備份，再於另一裝置匯入。強烈建議每週備份一次。
- 清除瀏覽器網站資料會刪除沒有備份的進度。
- 靜態網站沒有登入保護；若希望私人存取，需要後續加上驗證／存取控制。
- **不要將教材 PDF 直接上傳到公開部署的網站**，尤其在沒有公開散布授權的情況下。
- 週日 AI 家教第一版以「複製啟動指令，在 ChatGPT 使用」實現；站內示例選擇題不等同 ChatGPT 互動家教與語音測試。
- 2026-12-13 後的第二階段尚未安排。

## 技術

純 HTML/CSS/JavaScript，零建置依賴，適合 GitHub Pages、Netlify 等靜態託管。
