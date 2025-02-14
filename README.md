# Telegram-Crawler-Manager
A telegram application that manages forwarded channel content

📂 Telegram-Crawler-Manager
 ├── 📂 backend            # FastAPI 后端
 │   ├── main.py           # FastAPI 入口
 │   ├── models.py         # SQLAlchemy 数据模型
 │   ├── routes.py         # API 路由
 │   ├── telethon_client.py # Telethon 监听逻辑
 │   ├── auth.py           # JWT + Google Authenticator
 │   ├── worker.py         # Celery 任务管理
 ├── 📂 frontend           # React + Tailwind 前端
 │   ├── pages             # 页面组件
 │   ├── components        # 组件库
 │   ├── services          # API 请求封装
 ├── 📂 database           # 数据存储
 ├── Dockerfile            # 容器化部署
 ├── requirements.txt      # 依赖文件
 └── README.md             # 文档


 --------------------Project directory structure
