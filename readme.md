# 綠空漫泡，綠川漾沫｜城市綠洲專題報導

本專案為臺中舊城區雙生綠洲專題介紹網頁，聚焦「綠空鐵道」與「綠川水岸」，透過「城市綠洲慢活美學」的核心定位，探討百年鐵道遺構與水岸生態復育的歷史記憶與當代流變，展現舊城新生的獨特風貌。

## 專案功能特色
- **SEO 最佳化**：包含完整的 Meta 標籤、Open Graph 社交協議與語意化 HTML5 標記（header, nav, aside, main, article, section, footer）。
- **RWD 響應式佈局**：支援手機、平板與桌上型電腦，影片與地圖採 16:9 自適應縮放，確保手持裝置能完整顯示所有資訊。
- **CSS Grid 系統**：實作拿鐵暖色調與溫潤背景之雙欄側邊導覽（固定側邊欄 + 主內容區）與格線系統。
- **檔案模組化切割**：CSS 樣式表獨立抽離至 `css/hw07.css`，圖片資源統籌管理於 `images/` 資料夾。
- **導覽列與側邊欄架構**：整合頂部導覽列與固定式側邊欄目錄，實現流暢的單頁錨點切換與導覽體驗。

---

## Vibe Coding 指令紀錄 (Prompts Log)

本專案運用 Vibe Coding 模式，透過明確架構、情緒調性與技術邊界進行人機協同開發。以下為生成此專案的核心提示詞紀錄：

### Prompt 1：專案架構與基礎骨幹建立
> **Prompt:**  
> 「請扮演資深前端工程師。我正在製作網頁作業，主題是針對臺中舊城區綠空鐵道與綠川的專題企劃《綠空漫泡，綠川漾沫》。  
> 請幫我規劃一個靜態網頁，規範要求：  
> 1. 具備頂端導覽列（nav）與固定側邊欄（aside）目錄。  
> 2. 具有完整的 SEO Meta 標籤（含 Title, Description, Keywords, Open Graph）。  
> 3. 採用語意化 HTML5 標籤（header, main, article, section, footer）。」

### Prompt 2：CSS Grid 系統與 RWD 跨裝置適配
> **Prompt:**  
> 「請為上述專題撰寫完整的 `css/hw07.css` 外部樣式表，滿足以下要求：  
> 1. 版面採用雙欄結構（左側固定側邊欄 + 右側主內容），並使用 CSS Grid（`grid-template-columns: 280px 1fr`）實作排版。  
> 2. 影片與地圖區塊需設定自適應 RWD 比例，確保在手機等小螢幕上不會破版。  
> 3. 使用 Media Queries 設定斷點（850px），在行動裝置自動轉為單欄並調整導覽列排版。」

### Prompt 3：嵌入專題多媒體與內容精修
> **Prompt:**  
> 「請在 HTML 內加入專題對應的 YouTube 介紹影片 iframe 與 Google Maps 位置地圖嵌入碼，並設定正確的寬高與 `loading="lazy"` 屬性。同時補齊景點比較表格、走讀小提醒與資料來源等完整結構。」

### Prompt 4：外部 CSS 切分與樣式規範對齊
> **Prompt:**  
> 「請將所有的內嵌樣式及 style 元素完全移除，確保 HTML 只透過 `<link rel="stylesheet" href="css/hw07.css">` 載入外部樣式。維持原本溫潤的拿鐵暖色調與卡片陰影圓角，確保排版風格專業一致。」

### Prompt 5：雲端部署與專案檔案完整性檢查
> **Prompt:**  
> 「請指導我如何將專案部署至 GitHub、Vercel 以及 InfinityFree。同時幫我整理一份包含 Vibe Coding 指令紀錄與專案連結的 `README.md` 自述檔。」

---

## 專案部署連結

1. **Prompt 說明檔 (GitHub)**：  
   `https://github.com/你的GitHub帳號/你的專案名稱/blob/main/README.md`
2. **InfinityFree 部署網址**：  
   `https://jiaci.freehosting.dev/hw1111__D1446375.html`
3. **Vercel 部署網址**：  
   `https://你的專案名稱.vercel.app`
