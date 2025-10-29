# 💪 健身動作介紹 Fitness Video App

這是一個使用 **Flask** 建立的健身教學影片查詢網站。  
使用者可以搜尋常見健身動作，並直接觀看對應的 YouTube 示範影片。

---

## 🚀 網站特色

- 🎥 內建多個訓練動作影片（胸、背、手臂、腿、肩）
- 🔍 可輸入關鍵字搜尋動作
- 💻 前端使用簡潔的 HTML + CSS，行動裝置也能使用
- ☁️ 可一鍵部署到 Render 雲端平台

---

## 📂 專案結構

```
fitness-video-app/
├── app.py               # Flask 主程式
├── requirements.txt     # 套件需求
├── Procfile             # Render 啟動設定
└── runtime.txt          # Python 版本指定
```

---

## 🧩 本地執行方式

1. 安裝必要套件：
   ```bash
   pip install -r requirements.txt
   ```

2. 啟動伺服器：
   ```bash
   python app.py
   ```

3. 在瀏覽器開啟：
   ```
   http://127.0.0.1:10000/
   ```

---

## 🌐 部署到 Render

1. 登入 [https://render.com](https://render.com)
2. 點擊「New → Web Service」
3. 連接 GitHub 並選擇本專案
4. 設定如下：
   - Build Command：`pip install -r requirements.txt`
   - Start Command：`python app.py`
   - Region：`Singapore (Asia)`
5. 點「Create Web Service」  
6. 部署完成後會自動產生公開網址，例如：
   ```
   https://fitness-video-app.onrender.com
   ```

---

## 🖼️ 網站畫面預覽
> 💡（可自行補上截圖，例如首頁與搜尋功能）

| 首頁畫面 | 搜尋動作 |
|-----------|-----------|
| ![首頁](images/home.png) | ![搜尋](images/search.png) |

---

## 🧑‍💻 作者
由 ChatGPT + Flask 製作。  
示範主題：**健身動作介紹系統**  
版本：`v1.0`

---
