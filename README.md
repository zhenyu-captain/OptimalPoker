# OptimalPoker Pro 文档网站

这是一个基于 Vue 3 和 Vite 构建的单页文档网站，用于展示 OptimalPoker Pro 产品的功能和使用说明。

## 功能特性

- 📚 完整的8个功能模块文档整合在单一页面
- 🎨 现代化的响应式设计，全屏自适应布局
- 🚀 基于 Vue 3 + Vite 的快速开发体验
- 📱 移动端友好的界面
- 🖼️ 集成产品截图展示
- 🌐 原始英文文档内容，保持专业性

## 文档结构

1. **Range Construction** - Intelligent Range Construction & Analysis
2. **Board Setup** - Postflop Equity Distribution and Strategy Evaluation
3. **Tree Configuration** - Comprehensive Customization from Stack Depth to Advanced Betting Rules
4. **Bunching Effect** - Bringing Solvers Closer to Real Gameplay with Folded-Range Simulation
5. **Run Solver** - Efficient Execution, Precise Control
6. **File Operations** - One-Click Reuse of Configurations and Results
7. **Results Classic** - Comprehensive Strategy Insights with Interactive Tables
8. **Results Pro** - Professional Enhanced Results Viewer with Multi-Tab Support

## 开发环境

### 安装依赖

```bash
npm install
```

### 启动开发服务器

```bash
npm run dev
```

### 构建生产版本

```bash
npm run build
```

### 预览生产版本

```bash
npm run preview
```

## 项目结构

```
src/
├── views/              # 页面组件
│   └── Home.vue        # 主页面（包含所有文档内容）
├── router/             # 路由配置
│   └── index.js        # 简化路由，只有首页
├── App.vue            # 主应用组件
└── main.js            # 应用入口

public/
└── Product_Website_Introduction/  # 产品文档图片资源
    ├── 1-range/
    ├── 2-Board/
    ├── 3-Tree_Configuration/
    ├── 4-Bunching/
    ├── 5-Run_Solver/
    ├── 6-File_Operations/
    ├── 7-Results_Classic/
    └── 8-Results_Pro/
```

## 技术栈

- **Vue 3** - 渐进式 JavaScript 框架
- **Vite** - 下一代前端构建工具
- **Vue Router 4** - Vue.js 官方路由管理器
- **CSS3** - 现代样式设计

## 访问地址

开发环境：http://localhost:5173

## 自定义配置

如需修改文档内容，请编辑 `src/views/Home.vue` 文件。

所有8个功能模块的文档内容都整合在单一页面中，采用卡片式布局，每个模块包含：
- 功能标题和编号
- 功能描述
- 详细特性列表
- 相关产品截图

页面采用响应式设计，自动适应不同屏幕尺寸。

## 许可证

MIT License