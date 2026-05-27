# 台東紀錄片包場放映

《傳奇女伶高菊花》×《甘露水》 包場活動報名網頁

## 檔案說明

| 檔案 | 說明 |
|------|------|
| `index.html` | 主網頁（含報名表單） |
| `film_gaojuhua.jpg` | 傳奇女伶高菊花海報 |
| `film_ganlushu.webp` | 甘露水海報 |

## 啟用 Google Sheets 後台

1. 前往 [script.google.com](https://script.google.com) 新增專案
2. 貼入 `index.html` 底部 `<pre>` 框內的 Apps Script 程式碼
3. 建立 Google Spreadsheet，將其 ID 填入 `SHEET_ID`
4. 部署為 Web 應用程式（執行身分：我，存取：所有人）
5. 複製 Web App 網址，貼入 `index.html` 底部的 `SCRIPT_URL_A` 與 `SCRIPT_URL_B`

## 啟用 GitHub Pages

Repo → Settings → Pages → Source 選 `main` 分支 → 根目錄 `/`  
幾分鐘後即可透過 `https://你的帳號.github.io/repo名稱/` 訪問。
