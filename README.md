# AI-TestPlatform
自用备份：RainaAI自动化测试平台
功能：UI自动化、接口自动化，后续可扩展蓝牙BLE自动化测试

## 环境依赖
- Docker
- Python
- Node.js

## 部署
```bash
# 一键启动
docker compose up -d --build
访问地址：[http://127.0.0.1:3000](http://127.0.0.1:3000)
账号：admin /admin123
## 后端单独启动

```
cd backend
uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```

## 前端单独启动

```
cd frontend
npm install
npm run dev
```
