# 瀏覽器端 AI 風格視覺工具（Browser-Only AI-Style Visual Tools）

這是一個**完全在瀏覽器中運作的前端專案**，展示如何在 **沒有後端、沒有伺服器、沒有 API** 的情況下，打造出具有 **AI 體驗感** 的現代化視覺工具。

本專案僅使用 **HTML5、CSS、JavaScript 與 Canvas**，可直接部署於 **GitHub Pages** 或任何靜態網站主機。

---

## ✨ 這個專案是什麼？

本專案是一個多頁面的純前端應用，包含以下工具：

### 🖼 Image Frame Tool（圖片加框工具）
- 上傳圖片
- 自動置中與排版文字
- 套用簡潔的裝飾邊框
- 匯出為 PNG 圖檔

### 🧠 Text Visualizer（文字視覺化 Demo）
- 將純文字轉換成視覺化排版
- 自動字級計算與置中配置
- 適合做為 AI UX / Canvas 示範

### 🧭 Tool Selector（工具選擇首頁）
- 作為入口頁面，導向各個工具

雖然介面與行為看起來像「AI 應用」，但實際上 **完全沒有使用機器學習或雲端服務**，所有「智慧感」都來自瀏覽器端的邏輯設計。

---

## 🧠 運作原理（瀏覽器執行）

本專案 **100% 在瀏覽器中執行**：

- ❌ 沒有後端
- ❌ 沒有伺服器
- ❌ 沒有資料庫
- ❌ 沒有 build step
- ❌ 沒有 Node.js
- ❌ 沒有任何前端框架

### 使用技術

- **HTML5**：頁面結構
- **CSS3**：版面配置、字型與響應式設計
- **Vanilla JavaScript**：應用邏輯與狀態管理
- **Canvas API**：圖片繪製、合成與匯出

### 模擬「AI 感」的設計方式

透過輕量化的前端演算法，模擬智慧行為：

- 文字自動置中與平衡
- 依畫布寬度自動調整字級
- 內建勵志文字預設
- 隨機風格與視覺建議
- 智慧化的預設排版

所有運算都在本機完成，**使用者資料不會離開瀏覽器**。

---

## 📁 專案結構

/
├── index.html # 工具選擇首頁
├── frame.html # 圖片加框工具
├── text-visualizer.html # 文字視覺化 Demo
└── README.md

每個 HTML 檔案皆為**完全獨立、可直接開啟**的靜態頁面（內含 CSS 與 JS）。

---

## 🚀 部署方式（GitHub Pages）

此專案特別為 **GitHub Pages** 與靜態主機設計。

### GitHub Pages 部署步驟

1. 建立一個新的 GitHub Repository
2. 將以下檔案放在 repository 根目錄：
   - `index.html`
   - `frame.html`
   - `text-visualizer.html`
3. Commit 並 push 至 `main`（或 `master`）分支
4. 進入 GitHub：
   - **Settings → Pages**
   - Source 選擇 `Deploy from a branch`
   - Branch 選擇 `main`
   - Folder 選擇 `/ (root)`
5. 儲存並等待部署完成

完成後即可透過以下網址存取：

https://<你的 GitHub 使用者名稱>.github.io/<repository 名稱>/

---

## 🔗 線上 Demo

GitHub Pages Demo（請自行替換）：

https://<your-username>.github.io/<your-repo-name>/

---

## 🎯 適用場景

- 前端技術展示
- AI UX 體驗模擬
- Canvas / Browser API 教學
- Hackathon Prototype
- 重視隱私的工具
- 零基礎架構成本的 Demo 專案

---

## 📄 授權

MIT License  
可自由使用、修改與散佈。

---

## 🧩 專案理念

> 不一定需要複雜的後端與 AI 模型，  
> 善用瀏覽器原生能力，也能打造「看起來很聰明」的產品體驗。

---

若你希望進一步擴充（共用樣式、動畫、狀態保存、多工具整合等），  
此專案是一個非常乾淨、可長期演進的基礎。
