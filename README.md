# 紫微斗數線上排盤系統

雙擊 `index.html` 即可使用(不需要伺服器)。

| 檔案 | 內容 |
|---|---|
| index.html | 頁面與表單 |
| css/style.css | 樣式 |
| js/data.js | 常數、亮度表、十二神名稱 |
| js/lunar_table.js | 農曆資料表 1900–2030 |
| js/lunar.js | 國曆/農曆互換 |
| js/engine.js | 排盤引擎(命宮、五行局、星曜、四化、十二神、大小限、流運) |
| js/reading_data.js | 宮義、星曜象意、四化、讀盤步驟(解說用文字資料) |
| js/reading.js | 產生解說結構(三方四正、空宮借星、四化) |
| js/render.js | 盤面繪製 |
| js/render_reading.js | 命盤下方解說區繪製 |
| js/export.js | 12 行純文字檔(全部資訊 / 只存星曜) |
| js/app.js | 表單互動 |
| test/test_reference.js | 以範例盤驗證:`node test/test_reference.js` |
