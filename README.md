# Card & TW ＆ Game 品牌入口

公開網址：<https://howard118008y-commits.github.io/>

本儲存庫是 GitHub Pages 帳號主站；遊戲仍位於 [toonhub-island-duel](https://howard118008y-commits.github.io/toonhub-island-duel/)，不改變既有遊戲路徑。

## 部署

將本目錄發布至 `howard118008y-commits/howard118008y-commits.github.io`，GitHub Pages 使用 `main` 分支根目錄。網站為靜態 HTML，無建置步驟。`.nojekyll` 保留原始檔案。

## 搜尋設定

- `index.html` 提供可讀品牌介紹、遊戲與指南連結、自我 canonical、Open Graph、Twitter Card、根目錄 `WebSite` 結構資料及 Search Console 驗證標籤。
- 圖標與分享圖引用遊戲專案內 `brand/` 的固定網址，避免兩套品牌圖案不同步。Search Console 驗證標籤由已登入帳號的官方介面取得，需保留。
- `robots.txt` 只允許擷取並公布 sitemap；不封鎖此 hostname 的任何其他專案。
- `sitemap.xml` 是 sitemap index，分別連向僅含根首頁的 `root-sitemap.xml` 及遊戲專案 sitemap。
- Google favicon 與 site name 以 hostname 為單位；本設定可能成為此 hostname 所有專案的共用搜尋圖標與站名。瀏覽器的分頁圖標仍依各頁設定。
- Google 是否顯示圖標、收錄網址或選用品牌名稱由搜尋系統決定；部署和提交不等於收錄。

官方參考：[favicon](https://developers.google.com/search/docs/appearance/favicon-in-search)、[site name](https://developers.google.com/search/docs/appearance/site-names)、[robots.txt](https://developers.google.com/crawling/docs/robots-txt/create-robots-txt)。
