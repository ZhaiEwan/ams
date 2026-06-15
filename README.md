# AMS

一个 monorepo 项目，包含前端和后端服务。

## 项目结构

```
ams/
├── ams-client/    # React + Vite + TypeScript 前端
├── ams-server/    # Rust 后端
├── package.json   # 根目录 npm workspaces 配置
└── README.md
```

## 前置要求

- Node.js >= 18
- Rust >= 1.70
- npm >= 9

## 快速开始

### 安装依赖

```bash
npm install
```

### 开发

```bash
# 启动所有服务
npm run dev

# 或者单独启动
cd ams-client && npm run dev
cd ams-server && cargo run
```

### 构建

```bash
npm run build
```

### 代码检查

```bash
npm run lint
npm run format
npm run typecheck
```
