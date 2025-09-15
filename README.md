# Newsletter AI Agent Frontend

这是一个基于Next.js的AI通讯生成器前端项目。

## 功能特点

- 使用Next.js 14 App Router
- TypeScript支持
- Tailwind CSS样式
- 响应式设计
- 与FastAPI后端集成

## 开发环境设置

1. 克隆仓库：
```bash
git clone https://github.com/LuLu1016/newsletter-ai-agent-frontend.git
cd newsletter-ai-agent-frontend
```

2. 安装依赖：
```bash
npm install
```

3. 配置环境变量：
```bash
cp .env.example .env.local
```
然后编辑 `.env.local` 文件，设置必要的环境变量。

4. 启动开发服务器：
```bash
npm run dev
```

访问 [http://localhost:3000](http://localhost:3000) 查看应用。

## 部署说明

### Vercel部署

1. Fork这个仓库到你的GitHub账号
2. 在Vercel上创建新项目
3. 导入你fork的仓库
4. 设置环境变量：
   - `NEXT_PUBLIC_API_URL`: 后端API的URL
   - 其他必要的环境变量
5. 部署！

## 项目结构

```
src/
  ├── app/          # App Router页面和布局
  ├── components/   # 可重用组件
  ├── lib/         # 工具函数和配置
  └── styles/      # 全局样式
```

## 开发指南

- 使用 `npm run build` 构建生产版本
- 使用 `npm run lint` 运行代码检查
- 使用 `npm run test` 运行测试（如果已配置）

## 贡献指南

1. Fork本仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的改动 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个Pull Request