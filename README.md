# 3D Interactive Christmas Tree (MediaPipe + Three.js) 🎄✨

[English](#english) | [中文](#chinese)

---

<a name="english"></a>
## English

A 3D interactive Christmas Tree web application controlled by hand gestures using AI.

**Created & Fine-tuned by Andy Chan with Google Gemini.**

### Features
*   **Lush Particle Tree:** A beautiful 3D tree made of thousands of glowing particles and gift boxes.
*   **AI Hand Control:** Uses **MediaPipe Hands** to track your hand movements via webcam.
    *   **Rotate:** Move your hand left/right to spin the tree.
    *   **Explode & Reveal:** Open your hand to make the tree "explode" and reveal a gallery of photo cards. Clench your fist to bring the tree back together.
*   **Atmosphere:** Falling snow, twinkling lights, and a starry background.

### How to Run
1.  Clone this repository.
2.  Because of browser security restrictions (CORS) regarding webcam and textures, you **must run this on a local server**.
    *   **VS Code:** Install the "Live Server" extension, right-click `index.html`, and select "Open with Live Server".
    *   **Python:** Run `python3 -m http.server` in the terminal and open `http://localhost:8000`.
3.  Allow camera access when prompted.

### Customization
You can replace the dummy images in `index.html` (look for the `imgPaths` array) with your own local image paths (e.g., `./img/photo1.jpg`) to display your own memories.

**License:** MIT. Feel free to fork, modify, and use it!

---

<a name="chinese"></a>
## Chinese (中文)

一個結合 AI 手勢控制的 3D 互動聖誕樹 Web App。

**由 Andy Chan 使用 Google Gemini 製作及調整。**

### 功能特色
*   **茂盛粒子樹**：由數千顆發光粒子與禮物盒組成的華麗 3D 聖誕樹。
*   **AI 手勢控制**：整合 **MediaPipe Hands** 偵測手部動作。
    *   **旋轉**：手掌左右移動可控制樹的自轉。
    *   **爆開展示**：張開手掌，聖誕樹會瞬間「爆開」，並飛出照片牆展示回憶；握拳則會自動收回變回聖誕樹。
*   **節日氛圍**：包含落雪、閃爍燈光與星空背景。

### 如何運行
1.  下載此專案。
2.  由於瀏覽器對 Webcam 和材質載入的安全性限制 (CORS)，**必須在本地伺服器 (Local Server) 環境下運行**。
    *   **VS Code**: 安裝 "Live Server" 插件，右鍵點擊 `index.html` 選擇 "Open with Live Server"。
    *   **Python**: 在終端機輸入 `python3 -m http.server`，然後打開 `http://localhost:8000`。
3.  開啟網頁後，請允許瀏覽器使用攝影機。

### 自定義
你可以修改 `index.html` 中的 `imgPaths` 陣列，將連結換成你自己的本地圖片路徑（例如 `./img/photo1.jpg`），展示屬於你的回憶。

**授權：** MIT。歡迎大家隨便改，隨便用！
