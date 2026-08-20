# 𓃥 白六飛鳥訊息吊飾 3D (Bird Mobile Message Presenter)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.style=for-the-badge)

**𓃥 白六飛鳥訊息吊飾** 是一個基於 Three.js 打造的 3D 機械動力學互動裝置。本專案模擬木雕飛鳥連動懸吊機構，結合了動態拍翼動畫、自動 180 度翻轉雙面告示紙條，以及 URL 網址參數訊息傳遞功能，非常適合用於展示祝賀語、短語訊息或網頁藝術展示。

---

## ✨ 專案亮點 (Key Features)

- 🦅 **精準機械動態結構 (Kinematic Rigging)**：
  - 模擬真實手拉懸吊機構，帶動對稱翅膀進行物理連動拍打（Flapping Animation）。
  - 鳥身、喙部與羽翼採用輕薄等高削薄結構設計（Extrude Geometry），展現優雅精緻的木雕質感。
- 📜 **雙面動態告示紙條 (180° Flip Canvas Message)**：
  - 運用 HTML Canvas2D 即時動態生成雙面高解析度質感紙條 Texture。
  - 告示紙條每 3 秒自動進行平滑的 180 度 Y 軸翻轉（Cubic Easing），輪播顯示下一則訊息。
- 🔗 **URL 參數傳送與分享 (URL Message Sharing)**：
  - 支援從網址直接載入帶有自訂訊息的參數（例如 `?msg=訊息1,訊息2` 或 `?m=...`）。
  - 控制面板內建 **「🔗 複製訊息網址連結」** 按鈕，點擊即可自動編碼並生成分享網址至剪貼簿。
- ⚙️ **互動控制面板與拆解模式 (Interactive UI & Explode View)**：
  - **吊飾展示模式 (Hang Mode)**：呈現完整懸吊拍打與紙條輪播效果。
  - **組裝拆解模式 (Explode View)**：可將翅膀、鳥身與尾羽向外拆解展示內部連動結構。
  - **自訂樣式**：提供中文字體（標楷體、微軟正黑體、新細明體）、文字顏色、紙條底色與手拉拍打頻率調節。

---

## 🚀 快速開始 (Quick Start)

本專案為單一網頁程式（Single-file Web App），無須安裝任何建置工具或後端服務。

1. **下載專案**：
   ```bash
   git clone [https://github.com/your-username/bird-mobile-3d.git](https://github.com/your-username/bird-mobile-3d.git)
   cd bird-mobile-3d
