# 大阪＆九州旅遊行程網站

純靜態網站（單一 `index.html`），不需要安裝任何套件。

## 用 GitHub Pages 上線
1. 在 GitHub 建立新 repository（例如 `japan-trip`），設為 Public。
2. 把 `index.html` 和 `README.md` 上傳到 repository 根目錄（Add file → Upload files）。
3. 到 Settings → Pages，Source 選 `Deploy from a branch`，Branch 選 `main`、資料夾選 `/ (root)`，按 Save。
4. 約一分鐘後，網址會是 `https://你的帳號.github.io/japan-trip/`。

## 修改內容
- 行程：`D` 陣列，格式為 `圖示|名稱|備註`。
- 天氣座標：`LOC`；附近景點：`NEAR`；行李：`PACK`；退稅：`TAX`。
- 天氣使用 Open-Meteo（免金鑰）。預報只涵蓋約16天內，之後會顯示去年同日的天氣當參考。
