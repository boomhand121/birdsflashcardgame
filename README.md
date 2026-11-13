# 香港雀鳥 Flash Card 遊戲

網頁設計及相片來源：LEUNG CHUN PONG

包含 25 張雀鳥圖卡、翻卡學習、局部特徵挑戰、相片配對、特徵選擇題、中英文名稱朗讀、搜尋、隨機排序，以及作者新增圖卡和匯出遊戲功能。

## 存放於 GitHub

1. 解壓縮 ZIP。
2. 把此資料夾內的所有檔案放到 GitHub 儲存庫根目錄，讓 `index.html` 直接位於根目錄。請保留 `assets` 資料夾及 `.nojekyll`。
3. 提交變更。網站不需安裝套件或建置。

## 啟用 GitHub Pages

在儲存庫的 Settings → Pages → Build and deployment：

- Source 選擇 **Deploy from a branch**。
- Branch 選擇存放檔案的分支（通常為 `main`），資料夾選擇 **/ (root)**。
- 儲存後，等待 GitHub Pages 完成發佈，並使用該頁顯示的網站網址。

官方說明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 本機使用

可直接開啟 `index.html` 遊玩。若要使用「匯出整套遊戲」，請在本機啟動靜態伺服器，例如在此目錄執行 `python3 -m http.server 8000`，再開啟 http://localhost:8000 。亦可直接使用本次附帶的單檔 HTML 版本。

## 作者工具與語音

- 按「作者工具」新增相片、中英文名稱及特徵，亦可點選局部特徵位置。
- 新增資料只儲存在目前瀏覽器，不會自動寫入 GitHub。請使用「匯出整套遊戲」備份及分享。
- 廣東話朗讀需要裝置已安裝香港粵語聲線；英語及廣東話可用性取決於裝置和瀏覽器。
- 左右方向鍵切換圖卡，空白鍵翻卡。

## 檔案

- `index.html`：網頁入口。
- `style.css`：版面及樣式。
- `app.js`：遊戲和作者工具。
- `birds.js`：25 張圖卡的資料及局部放大位置。
- `assets/`：全部 25 張相片。
- `credits.txt`：相片來源資料。
- `.nojekyll`：GitHub Pages 靜態網站設定。

相片保留原有來源及水印；本下載包未另行授予相片使用權。
