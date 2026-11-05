# HW07 專案 Prompt 說明｜高雄橋頭糖廠報導

## 使用的 Vibe Coding 指令

請以我提供的 `index(1).html` 作為內容基礎，製作一個介紹「高雄橋頭糖廠：百年糖業記憶」的響應式報導網站。

### 設計與技術要求

1. 保留原始報導的主題、段落、參觀特色、參觀順序、比較表、圖片、影音、地圖、參觀提醒及資料來源。
2. 網站採用藍綠色系，呈現文化、歷史與環境的感受。
3. 使用語意化 HTML5 結構，包括 `header`、`nav`、`main`、`article`、`section`、`aside`、`figure`、`footer`。
4. HTML 只負責內容與結構；所有自訂樣式集中放在 `css/hw07.css`。
5. HTML 不可使用 `<style>`、`style="..."`、`@import`、CSS 框架、`!important` 或自行撰寫 JavaScript。
6. 使用 `<link rel="stylesheet" href="css/hw07.css">` 載入外部 CSS。
7. CSS 使用 12 欄 Grid System 配置側邊導覽與主要內容，並在平板、手機尺寸調整版面。
8. 手機版必須可閱讀完整資訊；表格可在自己的容器內水平捲動，圖片、影片及地圖不可超出螢幕。
9. 保留頁內導覽、回到頁首、鍵盤焦點提示、圖片替代文字與外部連結安全屬性。
10. 加入 title、description、author、keywords、robots 與 Open Graph 等 SEO 資訊。
11. 圖片放在 `images/` 資料夾，並使用相對路徑。
12. 不為了視覺效果刪減原始報導內容。

## 專案檔案結構

```text
bridgehead_hw07/
├── index.html
├── css/
│   └── hw07.css
├── images/
│   └── bridgehead-factory.svg
└── PROMPT.md
```

## 發佈方式

1. 將整個 `bridgehead_hw07` 資料夾上傳至 GitHub Repository。
2. 在 Vercel 選擇該 GitHub Repository，Framework Preset 選擇 Other，Build Command 留空，Output Directory 設為 `.`（或依 Vercel 畫面提示設定）。
3. 部署完成後，測試首頁、CSS、圖片、頁內導覽、YouTube 與 Google 地圖。
4. 將 GitHub Repository 網址、InfinityFree 首頁網址及 Vercel 部署網址填入作業繳交欄位。

> 注意：本專案檔案已整理完成；GitHub、InfinityFree 與 Vercel 的帳號操作及正式網址，需由作者登入自己的帳號完成，不能用未建立的網址代替。
