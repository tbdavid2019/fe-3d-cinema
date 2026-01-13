# Cyberpunk 3D Particle Interaction System
(賽博龐克 3D 粒子互動系統)

右手控制文字/Catch，左手控制 Nebula/Physics，雙手 Open 召喚大火球


這是一個基於 WebGL 與電腦視覺技術的單頁式網頁應用程式。透過 Webcam 捕捉手部動作，即時與畫面中的 12,000 個 3D 粒子進行互動。

![Style](https://img.shields.io/badge/Style-Cyberpunk-00ffff)
![Tech](https://img.shields.io/badge/Tech-Three.js%20%7C%20MediaPipe-purple)

## ✨ 特色功能

*   **沉浸式視覺**：深黑色背景搭配霓虹粒子，結合即時攝影機濾鏡效果。
*   **高效能渲染**：使用 Three.js 驅動 12,000 個獨立運算的粒子。
*   **AI 手部追蹤**：整合 Google MediaPipe Hands，實現精準的指尖追蹤與手勢辨識。
*   **物理模擬**：粒子具有斥力、吸力與流體波動效果。

## 🎮 操作指南

請確保您的電腦有攝影機，並允許瀏覽器存取權限。

### ✋ 左手 (指令控制)
控制粒子排列成不同的文字或形狀：

| 手勢 | 顯示文字/模式 | 顏色 |
| :--- | :--- | :--- |
| **1 指** | `Hello` | 🟦 霓虹藍 (Neon Blue) |
| **2 指** | `David888` | 🟨 霓虹黃 (Neon Yellow) |
| **3 指** | `我愛你` | 🟥 霓虹粉 (Neon Pink) |
| **4 指** | `再見` | 🟩 霓虹綠 (Neon Green) |
| **5 指 (張開)** | **Catch Mode (捕捉模式)**<br>粒子會被吸附到左手掌心 | 🟦 藍色 (Blue) |

### 🤚 右手 (物理互動)
與粒子進行物理層面的互動：

*   **食指指尖**：產生強力斥力場，推開周圍的粒子。
*   **5 指 (張開)**：觸發 **Nebula Mode (星雲模式)**。
    *   粒子會散佈至全螢幕。
    *   手掌移動時會產生類似水波紋 (Ripple) 的干擾效果。

### 🌟 雙手組合技 (Ultimate Combo)
當 **左手張開 (Catch)** 且 **右手張開 (Nebula)** 同時發生時：

*   **特效**：粒子會瞬間匯聚到左手上方。
*   **形態**：形成一顆旋轉的、帶有黑色紋理的 **3D 能量籃球**。
*   **動態**：球體會隨時間旋轉、跳動，並呈現心跳般的收縮效果。

## 🚀 如何執行

1.  直接用瀏覽器 (Chrome/Edge/Safari) 開啟 `index2.html`。
2.  允許網頁使用攝影機。
3.  站在鏡頭前，舉起雙手開始互動！

## 🛠️ 技術棧

*   **HTML5 / CSS3**
*   **JavaScript (ES6+)**
*   **[Three.js](https://threejs.org/)** - 3D 渲染引擎
*   **[MediaPipe Hands](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker)** - 手部偵測與追蹤

## 📝 備註
*   本專案將攝影機畫面做了水平鏡像翻轉，以符合直覺的鏡子體驗。
*   建議在光線充足的環境下使用，以獲得最佳的手部追蹤效果。
