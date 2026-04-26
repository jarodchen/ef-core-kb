# EF Core 知识库

Entity Framework Core 系统化学习指南，涵盖从基础到企业级实践的完整知识体系。

## 🌐 在线访问

**[https://jarodchen.github.io/ef-core-kb/](https://jarodchen.github.io/ef-core-kb/)**

## 📚 知识体系

### 基础篇
- EF Core 概述与核心概念
- 快速入门指南
- 开发模式详解（Code First、Database First）

### 核心功能
- 实体关系映射（一对一、一对多、多对多）
- 查询与数据加载策略
- LINQ 查询优化
- 变更跟踪机制

### 高级主题
- 迁移与版本控制
- 性能优化技巧
- 并发控制
- 依赖注入与生命周期管理

### 企业级实践
- 仓储模式实现
- 单元测试策略
- 日志与调试
- 常见问题解决方案

## 🚀 本地开发

如需离线访问或本地预览：

```bash
# 直接打开 html/index.html 文件即可
# 或使用任意 HTTP 服务器

# 使用 Python
python -m http.server 8080

# 使用 Node.js
npx serve html
```

访问 `http://localhost:8080`

## 📁 项目结构

```
ef-core-kb/
├── html/                    # 静态网站文件
│   ├── index.html          # 首页
│   ├── assets/             # CSS、JS 资源
│   └── ...                 # 各章节 HTML 页面
├── .github/workflows/      # GitHub Actions 配置
└── README.md
```

## 🔧 技术栈

- **框架**: Entity Framework Core
- **数据库**: SQL Server, PostgreSQL, MySQL
- **构建工具**: VitePress
- **部署**: GitHub Pages + GitHub Actions

## 📖 适用人群

- .NET 开发者学习 EF Core
- 需要系统掌握 ORM 框架的工程师
- 寻求 EF Core 最佳实践的团队成员
- 准备技术面试的候选人

## 💡 特色

- **系统化**: 从基础到高级，循序渐进
- **实战导向**: 每个概念都有实际代码示例
- **性能关注**: 专门的优化章节和最佳实践
- **持续更新**: 跟随 EF Core 最新版本

## 🤝 贡献

欢迎提出建议和反馈！如有内容补充或错误修正，请提交 Issue 或 Pull Request。
