# HR管理系统

一个完整的企业级人力资源管理系统，包含仪表盘、组织架构、编制管理、员工管理、薪酬管理、绩效考核、考勤管理、请假管理等功能。

## 🎯 核心功能

- **仪表盘** - 实时数据统计与可视化分析
- **组织架构** - 部门树形结构管理
- **编制管理** - 岗位和编制配置
- **员工管理** - 员工信息完整维护
- **薪酬管理** - 薪资计算、发放和查询
- **绩效考核** - 员工绩效评估与反馈
- **考勤管理** - 打卡记录和统计分析
- **请假管理** - 假期申请与审批流程
- **系统后台** - 用户权限、日志、配置管理

## 🛠️ 技术栈

### 前端
- React 18 + TypeScript
- Ant Design (UI组件库)
- Redux + Redux Thunk (状态管理)
- Axios (HTTP客户端)
- ECharts (数据可视化)

### 后端
- Node.js + Express
- TypeScript
- Prisma (ORM)
- JWT (认证)
- Multer (文件上传)

### 数据库
- MySQL 8.0+
- Redis (缓存)

## 🚀 快速开始

### 使用Docker启动（推荐）

```bash
git clone https://github.com/WJ4899/hr-management-system.git
cd hr-management-system
docker-compose up -d
```

访问应用：
- 前端: http://localhost:3000
- 后端API: http://localhost:5000

### 本地开发

后端：
```bash
cd backend
npm install
npm run prisma:generate
npm run prisma:migrate
npm run dev
```

前端：
```bash
cd frontend
npm install
npm start
```

## 📚 文档

- [架构设计](./docs/ARCHITECTURE.md)
- [开发指南](./docs/DEVELOPMENT.md)

## 👤 默认账户

- 用户名: admin
- 密码: admin123

## 📄 许可证

MIT License