# CLAUDE.md

## 项目概述

本项目是 **Agentic-AI 系统实战**项目，旨在构建强大的 AI Agent 系统。

## 技术栈

### 后端
- **语言**: Python
- **框架**: FastAPI
- **依赖管理**: uv

### 前端
- **框架**: Next.js

### 数据库
- **关系数据库**: PostgreSQL
- **缓存数据库**: Redis

### 部署
- **本地部署**: Docker Compose 一键部署

## 项目结构

```
agentic-ai/
├── backend/          # 后端代码 (Python + FastAPI)
├── frontend/         # 前端代码 (Next.js)
├── docker-compose.yml
└── README.md
```

## 开发指南

### 环境要求
- Python 3.11+
- Node.js 18+
- Docker & Docker Compose

### 常用命令

```bash
# 后端开发
cd backend
uv sync                    # 安装依赖
uv run uvicorn app.main:app --reload   # 启动开发服务器

# 前端开发
cd frontend
npm install               # 安装依赖
npm run dev               # 启动开发服务器

# Docker 部署
docker-compose up -d       # 启动所有服务
docker-compose down        # 停止所有服务
docker-compose logs -f     # 查看日志
```

## 代码规范

- Python 遵循 PEP 8 规范
- 使用类型注解提高代码可读性
- API 接口遵循 RESTful 设计原则
