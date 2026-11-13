# 待辦事項 Docker 版

## 專案介紹
這是一個用 Docker 包裝的待辦事項網站，使用 Flask 打造。

## 檔案說明
- `app.py`：Flask 後端程式
- `templates/index.html`：前端網頁
- `Dockerfile`：Docker 映像檔定義
- `docker-compose.yml`：Docker Compose 設定
- `requirements.txt`：Python 套件清單

## 如何使用

### 1. 一般執行（不用 Docker）
```bash
pip install -r requirements.txt
python app.py

