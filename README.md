# Aaron Chou — Resume

單檔靜態履歷。**https://simplyboys.github.io/resume/**

零依賴、零 build step、零外部資源。列印（Ctrl+P）出來是 A4 一張。

## 這份檔案跟原稿的關係

原稿在私有 vault：`projects/2026-06-job-search/履歷-v8-精簡版.html`。
這裡的 `index.html` **只在 `<head>` 有三處增補**，`<body>` 與原稿逐字相同：

1. `viewport` / `color-scheme` / `description` 三個 meta
2. `<title>` 拿掉版號（訪客不需要看到 v8）
3. 一段 `@media screen` 與 `@media screen and (max-width: 640px)`

原稿那段 A4 樣式（8.1pt 是給紙的）**原封不動**，螢幕樣式只在 `screen` 覆寫
⇒ 列印結果與原稿一致。

**同步方式**：原稿改版時，把 `<body>…</body>` 之間整段換掉即可，`<head>` 不要動。
