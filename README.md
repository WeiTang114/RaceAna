# Racana - 賽車分析工具

一個跨平台的網頁應用程式，專為真實賽車手和模擬器賽車手設計，用於分析自己和對手的錄影並改進技術。

## 主要功能

### 🎥 雙影片播放
- **左側視窗**：載入自己的本地影片或 YouTube 影片
- **右側視窗**：載入專家的本地影片或 YouTube 影片
- 支援同步播放和獨立播放模式

### ⏯️ 播放控制
- 同步播放：兩個影片同時播放/暫停
- 獨立播放：每個影片可以單獨控制
- 時間軸控制：精確跳轉到指定時間點

### 🏷️ 標籤系統
- 在影片中標記重要時刻（如：1, 2, 3, 4, 5）
- 快速跳轉到標記的時間點
- 管理多個標籤點

### 📊 分析功能
- 並排比較兩個影片
- 分析動作和速度差異
- 找出改進空間

## 技術架構

- **前端框架**：React 18 + TypeScript
- **樣式**：Tailwind CSS
- **影片播放**：React Player
- **圖標**：Lucide React
- **建置工具**：Vite

## 安裝和運行

### 前置需求
- Node.js 16+ 
- npm 或 yarn

### 安裝依賴
```bash
npm install
```

### 開發模式
```bash
npm run dev
```

應用程式將在 `http://localhost:3000` 啟動

### 建置生產版本
```bash
npm run build
```

## 使用說明

### 1. 載入影片
- 在左側輸入框輸入自己的影片路徑或 YouTube 網址
- 在右側輸入框輸入專家的影片路徑或 YouTube 網址
- 點擊「載入」按鈕

### 2. 播放控制
- 使用播放/暫停按鈕控制影片
- 切換同步模式或獨立模式
- 使用時間軸快速跳轉

### 3. 標籤管理
- 在播放過程中點擊「新增標籤」
- 輸入標籤名稱（如：1, 2, 3...）
- 使用「跳轉」按鈕快速回到標記點
- 使用「刪除」按鈕移除不需要的標籤

### 4. 分析比較
- 並排觀看兩個影片
- 比較相同時間點的動作差異
- 找出技術改進點

## 支援的影片格式

### 本地檔案
- MP4, AVI, MOV, MKV 等常見格式
- 支援相對路徑和絕對路徑

### 線上影片
- YouTube 影片
- 支援完整 URL 和短網址

## 開發者資訊

這個專案使用現代的前端技術棧，提供良好的開發體驗：

- **TypeScript**：提供類型安全
- **ESLint**：程式碼品質檢查
- **Tailwind CSS**：快速樣式開發
- **Vite**：快速的開發和建置工具

## 授權

MIT License 
