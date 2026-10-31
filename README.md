# naicheng-ref

這裡放三個獨立靜態站的完整鏡像，只供參考研究，不是原創內容。

## 來源與權利

- 內容與權利都屬原作者 **陳乃誠（大乃老師）**，GitHub [`hk6429`](https://github.com/hk6429)。
- 各站權利說明以原作者的 [`naicheng-works/rights.html`](naicheng-works/rights.html) 為準。
- 如原作者要求下架，會立即移除。

| 資料夾 | 原站 | 內容 |
|---|---|---|
| `naicheng-works-island/` | https://naicheng-works-island.pages.dev | 大乃作品島：112 件作品的 3D 島嶼地圖（three.js），含文字導覽與作品總覽 |
| `naicheng-island/` | https://naicheng-island.pages.dev | 陳乃誠島：個人介紹的 3D 島嶼（three.js） |
| `naicheng-works/` | https://naicheng-works.pages.dev | 大乃學習工具箱：作品入口的文書版，含 112 張截圖、112 張 QR、作品資料 `data/sites.js` 與權利頁 |

## 與原站的差異

- 原站的 GoatCounter 到訪統計會把流量送進原作者帳號。兩個島嶼站改成只在原正式網域觸發；工具箱站直接移除統計腳本。
- 工具箱的 `404.html` 原本用絕對路徑，改成相對路徑，放在子路徑下也能正常顯示。
- 兩個島嶼站的作品截圖與 QR 仍從原站 `naicheng-works.pages.dev/assets/` 載入，沒有改指向本 repo 的副本。
- 其餘檔案維持原樣。三站都是純相對路徑，沒有建置步驟。

## GitHub Pages 網址

在 Settings → Pages 選 `main` / `(root)` 後：

- https://mikabeneton33-hub.github.io/naicheng-ref/naicheng-works-island/
- https://mikabeneton33-hub.github.io/naicheng-ref/naicheng-island/
- https://mikabeneton33-hub.github.io/naicheng-ref/naicheng-works/

根目錄的 `.nojekyll` 讓 Pages 原樣提供檔案，不經過 Jekyll 處理。
