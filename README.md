# 刷題貓服務資訊網站

GitHub Pages 純靜態網站，無建置步驟、JavaScript、外部字型或分析工具。

## 頁面

- `index.html`：服務資訊首頁。
- `privacy.html`：隱私權政策。
- `terms.html`：使用條款。
- `style.css`：共用響應式樣式。
- `.nojekyll`：以靜態檔案直接發布。

## 發布狀態

2026-11-06 起為正式內容：最後更新日期與生效日期為 2026-11-06，已移除草稿提示、`〔…〕` 欄位與 `noindex, nofollow`。

文案來源：App repository 的 `docs/product/privacy_policy.md` 與 `docs/product/terms_of_service.md`。修改文案時同步兩邊內容。

## GitHub Pages 設定

推送後，在 repository 的 Settings → Pages，選擇 Deploy from a branch，分支 `main`、目錄 `/ (root)`。預期網址如下，實際發布狀態以 GitHub Pages 回報為準：

- https://kaiserBoot.github.io/shuati-cat-web/
- https://kaiserBoot.github.io/shuati-cat-web/privacy.html
- https://kaiserBoot.github.io/shuati-cat-web/terms.html

## 本機預覽

在本目錄執行 `python3 -m http.server 8000`，開啟 http://localhost:8000/。
