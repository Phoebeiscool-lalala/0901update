# 东南亚劳动法规智能监控平台

AI 驱动的东南亚劳动法规监控系统，覆盖 3 个国家（新加坡、马来西亚、泰国）。

## 功能特点

- **交互式地图**：基于 GeoJSON 的可视化，使用 Leaflet.js
- **多语言支持**：中文 / 英文 / 西班牙语界面
- **智能筛选**：按国家、法规类型、生效年份、关键词搜索
- **深色模式**：完整的深色/浅色主题切换
- **响应式设计**：支持桌面和平板设备
- **AI 助手**：内置 MiChat AI 问答、翻译、分析功能
- **业务详情**：马来西亚法规含结构化缴费费率、计算公式、资格条件

## 法规覆盖

| 国家 | 法规数 | 涵盖领域 |
|------|--------|----------|
| 🇲🇾 马来西亚 | 16 | EPF/SOCSO/EIS/HRDF 缴费、年假/病假/产假/陪产假、加班费、解雇补偿、个税 |
| 🇸🇬 新加坡 | 1 | 雇佣法（渐进式工资模式） |
| 🇹🇭 泰国 | 1 | 劳动保护法（家政工人） |

## 项目结构

```
├── index.html               # 主入口（自包含：HTML + 内联 CSS/JS + 数据）
├── data/
│   └── laws.json            # 法规数据库（18 条法规，3 个国家）
└── README.md
```

> **注意**：`src/` 目录下的 `main.css` 和 `app.js` 是历史遗留文件，当前未被引用。所有样式和逻辑均内联在 `index.html` 中。

## 快速开始

直接在浏览器中打开 `index.html` 即可使用。

## 部署

### GitHub Pages（推荐）

1. 访问仓库设置页面：Settings → Pages
2. **Source**：选择 **Deploy from a branch**
3. **Branch**：选择 **main**
4. **文件夹**：选择 **/ (root)**
5. 点击 **Save**

部署后访问：`https://phoebeiscool-lalala.github.io/0901update/`

### Netlify

将仓库根文件夹拖放到 [Netlify Drop](https://app.netlify.com/drop)。

## 数据格式

法规数据内联在 `index.html` 的 `INLINE_DATA` 常量中，同步存储于 `data/laws.json`。每条记录包含：

| 字段 | 说明 |
|------|------|
| `id` / `country` / `countryCode` / `flag` | 基本标识 |
| `law` / `lawZh` / `lawEs` | 三语法规名称 |
| `primaryCategory` / `secondaryCategory` | 法规类目与细分类目 |
| `summary` / `summaryZh` / `summaryEs` | 三语法规摘要 |
| `effectiveDate` / `effectiveDateStatus` | 生效时间及确认状态 |
| `changes` / `changesZh` / `changesEs` | 核心变更（三语） |
| `hrImpact` | HR 影响评估 |
| `businessFields` | 业务详情（马来西亚法规专属：缴费费率、计算公式、资格条件等） |

## 分类系统

### 一级分类（Primary Category）

- 法定缴费类 Social Security / Statutory Funds
- 休假类 Leave
- 工时与加班 Working Time & Overtime
- 离职与遣散 Termination & Severance
- 个税 Income Tax

## 技术栈

- **前端**：原生 HTML/CSS/JS（无框架依赖）
- **地图**：Leaflet.js（异步加载，CDN 不可用时优雅降级）
- **数据**：静态 JSON（无需后端）
- **样式**：CSS 自定义属性（支持主题切换）

## 许可证

MIT
