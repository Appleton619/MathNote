# MathNote 數學知識筆記庫

MathNote 是一個以繁體中文呈現的大學數學筆記網站，整理機率論、微積分與圖論的基本概念、公式及例題。

## 本機瀏覽
直接以瀏覽器開啟 \`index.html\` 即可。也可以在專案資料夾執行簡易靜態伺服器：

\`\`\`bash
python -m http.server 8000
\`\`\`

再開啟 \`http://localhost:8000\`。

## 專案結構
- \`AGENTS.md\`：AI 開發規範／員工手冊
- \`index.html\`：網站首頁
- \`subjects/\`：各科目網頁
- \`notes/\`：Markdown 筆記來源
- \`assets/\`：共用 CSS 與 JavaScript

## GitHub Pages 部署
1. 將整個專案推送到 GitHub Repository。
2. 進入 Repository 的 **Settings → Pages**。
3. 在 **Build and deployment** 選擇 **Deploy from a branch**。
4. Branch 選 \`main\`，資料夾選 \`/ (root)\`，按下 Save。
5. 等待 GitHub Pages 完成部署，網址通常為 \`https://你的帳號.github.io/Repository名稱/\`。

## 新增課程
請先閱讀 \`AGENTS.md\`。新增課程時，建立對應的 \`subjects/科目名稱.html\` 與 \`notes/科目名稱.md\`，並在首頁新增連結卡片，沿用既有樣式。
