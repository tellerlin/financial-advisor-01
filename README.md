# 理财师智能顾问平台

专业的**保险产品推荐系统**,帮助理财师快速生成个性化理财方案。系统基于客户需求和风险偏好,自动匹配最优保险产品组合。

- [**查看演示**](您的演示链接)

![系统截图预览](您的截图链接)

# 项目介绍

**理财师智能顾问平台**采用现代化技术栈,提供直观的界面设计,帮助理财师提高工作效率。系统自动化生成客户报告,大幅简化理财师的日常工作流程。

一期项目主要聚焦于储蓄险产品推荐。

# 主要功能

- **产品数据库** - 收集并维护香港市场储蓄险产品数据
- **客户信息管理** - 记录客户基本信息、预算和风险偏好
- **智能匹配引擎** - 根据客户需求自动推荐最优产品组合
- **报告生成器** - 一键生成专业的理财建议报告
- **响应式设计** - 完美适配桌面端和移动端显示

# 技术架构

- **前端**: 基于 Cloudflare Pages 
- **后端**: Cloudflare Workers
- **数据库**: 
  - 生产环境: Cloudflare D1
  - 开发环境: SQLite (与D1保持同构)

# 安装说明

## 环境要求:
- NodeJs (>= 16.0.0)
- SQLite3 

## 开发环境配置:

1. 克隆代码仓库
```bash
git clone [仓库地址]
```

2. 安装依赖
```bash 
npm install
```

3. 初始化本地数据库
```bash
npm run init-db
```

4. 启动开发服务器
```bash
npm run dev
```

## 生产环境部署

1. 构建生产版本
```bash
npm run build
```

2. 部署到Cloudflare Pages
```bash
npm run deploy
```

# 项目结构

- `/app/components` - React组件
- `/app/pages` - 页面组件
- `/app/services` - 业务逻辑服务
- `/database` - 数据库模型和迁移文件
- `/workers` - Cloudflare Workers代码

# 开发团队

[您的信息]

# 技术栈

- React 
- Cloudflare Pages
- Cloudflare Workers
- Cloudflare D1
- SQLite
- [其他依赖...]
