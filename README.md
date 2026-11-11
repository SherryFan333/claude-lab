# Sherry｜接案作品集 Landing Page

一個單頁式（Landing Page）個人接案作品集網站，以星空夜色為視覺主題，展示品牌文案、網站設計與內容企劃的服務與作品。

## 網站功能

- **導覽列（Nav）**：固定於頂部的導覽列，可快速跳轉至各區塊，並支援平滑捲動。
- **主視覺（Hero）**：品牌標語與簡介，搭配淡入動畫效果。
- **精選作品（Work）**：以卡片呈現作品案例，例如：
  - 拾光咖啡品牌故事
  - 漫遊誌旅行部落格
  - 星語永續選物電子報
- **聯絡區塊（Contact）**：「有個想法？我們聊聊吧」，引導訪客與我聯繫。
- **星空背景**：以純 CSS 漸層繪製的星空與光暈背景，延續個人品牌風格。
- **捲動顯示動畫**：區塊捲動進入畫面時以淡入方式呈現。
- **RWD 響應式設計**：針對平板與手機版優化排版，避免橫向捲動，小螢幕也能舒適瀏覽。

## 使用技術

- **HTML5**：語意化標籤（`<section>`、`<nav>` 等）建構頁面結構。
- **CSS3**：
  - CSS 變數（Custom Properties）管理色彩與字型
  - `radial-gradient` / `linear-gradient` 繪製星空背景
  - Flexbox / Grid 版面配置
  - `@media` 媒體查詢實現 RWD 響應式設計
  - 過場與淡入動畫
- **Google Fonts**：Inter、Noto Sans TC、Noto Serif TC
- 少量原生 JavaScript 處理捲動進場動畫（無任何框架或建置工具）

## 如何用瀏覽器開啟

本專案為純靜態網頁，不需要安裝任何套件或伺服器。

**方法一：直接開啟檔案**

1. 下載或 clone 本專案：
   ```bash
   git clone https://github.com/SherryFan333/claude-lab.git
   ```
2. 進入 `claude-lab` 資料夾。
3. 對 `index.html` 按兩下，即可用預設瀏覽器開啟；或將檔案拖曳到 Chrome / Edge / Firefox / Safari 視窗中。

**方法二：使用 VS Code Live Server（選用）**

1. 用 VS Code 開啟專案資料夾。
2. 安裝 Live Server 擴充套件。
3. 在 `index.html` 上按右鍵 →「Open with Live Server」，存檔後頁面會自動重新整理。

> 提示：若要檢視手機版效果，可在瀏覽器按 `F12` 開啟開發者工具，切換至裝置模擬模式（Toggle device toolbar）。

## 檔案結構

```
claude-lab/
├── index.html   # Landing Page 主頁（HTML + CSS）
├── note.txt     # 筆記檔
└── README.md    # 專案說明
```
