# 抟知 ToKnow · 个人知识资产化系统

> 把零散的灵感，抟成完整的你。
> Shape your sparks into a self.

[![Version](https://img.shields.io/badge/version-V15.6-b8654a)](https://github.com/Damia/toknow)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Demo](https://img.shields.io/badge/demo-online-blue)](https://tunknow-toknow.vercel.app)

**抟知 ToKnow** 是一个基于办公小浣熊的个人知识资产化系统，面向科研者、内容创作者与高灵感人群，把散落在论文、网页、收藏夹、摘抄与日常观察中的碎片信息，转化为可检索、可分析、可复用、可发布的个人知识资产。

---

## 🌐 在线体验

**直接打开链接即可使用：** <https://tunknow-toknow.vercel.app>

或者下载 `index.html` 双击打开（单文件 · 零依赖 · 离线可用）。

---

## ✨ 核心特性

| 模块 | 描述 |
|---|---|
| 📂 **灵感典藏** | 19 字段标准卡片 · 瀑布流 · 4 维度筛选 · 支持 Excel/CSV/JSON 上传 |
| 🧠 **知识画像** | 高频关键词 / 主题簇 / 跨领域 / 沉睡复活 / 6 大方向 |
| 🎯 **发展方向** | 6 大长期方向 + 12 个联想角度 |
| ✨ **生成成果工作台** | 三档草稿（200/800/2000 字）+ 6 真实可点击动作 + 4 平台样例 |
| 📚 **待生成库** | localStorage 持久化收藏 |
| 👤 **我的** | 登录 / 游客模式 · 完整创作画像 |

---

## 🚀 一键部署到 Vercel

### 方式 1：网页拖拽（最快 · 推荐）

1. Fork 本仓库到你的 GitHub 账号
2. 打开 <https://vercel.com> → Sign Up with GitHub
3. New Project → Import Git Repository → 选择本仓库
4. Deploy（30 秒）→ 获得 `https://your-name.vercel.app`

### 方式 2：CLI 一行命令

```bash
npm install -g vercel
git clone https://github.com/Damia/toknow.git
cd toknow
vercel
```

### 方式 3：GitHub Pages（不需要 Vercel 账号）

1. 仓库 → Settings → Pages
2. Source: `main` branch · root
3. 等 1-2 分钟 → `https://your-name.github.io/toknow`

---

## 📂 仓库结构

```
toknow/
├── README.md              ← 本文件
├── LICENSE                ← MIT 协议
├── .gitignore             ← Git 忽略规则
├── vercel.json            ← Vercel 部署配置
├── index.html             ← 主入口（单文件 HTML · 244 KB）
└── docs/                  ← 完整项目文档
    ├── 01-闪电演讲.docx
    ├── 02-产品说明文档.docx
    ├── 03-技术说明文档.docx
    ├── 04-演示PPT.pptx
    └── data/
        └── 原始数据库.xlsx
```

---

## 🛠 技术栈

- **前端**：原生 HTML5 + ES6 JavaScript + CSS3
- **零依赖**：核心功能无任何外部 CDN
- **数据**：内嵌 JSON 数组（43 条样本）+ 支持用户上传 Excel/CSV/JSON 替换
- **持久化**：localStorage（筛选状态 / 待生成库 / 登录态）
- **字体**：方正小标宋 → Songti SC → SimSun 回退
- **文件大小**：~244 KB（gzip 后 ~55 KB）

---

## 🎬 演示视频

3 分钟完整链路演示：

| 时间 | 内容 |
|---|---|
| 0:00-0:20 | 开场钩子 + 痛点 |
| 0:20-0:50 | 登录 / 游客模式 |
| 0:50-1:20 | 数据导入 + 瀑布流呈现 |
| 1:20-1:50 | 知识画像 5 子模块 |
| 1:50-2:30 | 工作台 + 三档草稿切换 |
| 2:30-2:50 | 点击"生成标题组"弹窗 |
| 2:50-3:00 | 收束 |

---

## 📖 本地运行

### 最简单：双击打开

直接双击 `index.html`，浏览器即可打开。

### 推荐：本地服务器

```bash
# Python 3
python3 -m http.server 8000

# Node.js
npx serve .

# 浏览器打开 http://localhost:8000
```

---

## 📜 完整文档

| 文档 | 用途 |
|---|---|
| [产品说明文档](docs/02-产品说明文档.docx) | 完整产品定位 + 核心 Prompt + 模块组合 + 方案独特性 + 数据支撑 |
| [技术说明文档](docs/03-技术说明文档.docx) | 系统架构 + Prompt 工程 + 数据流 + 性能基准 |
| [闪电演讲](docs/01-闪电演讲.docx) | 300 字三段式作品简介 |
| [演示 PPT](docs/04-演示PPT.pptx) | 20 页主推材料 |

---

## 🏆 OPC 高手创造赛 · 提交概览

- **作品名称**：抟知 ToKnow · 基于办公小浣熊的个人知识资产化系统
- **作者**：Damia
- **版本**：V15.6
- **赛道**：OPC 高手创造赛
- **基于**：商汤办公小浣熊（数据分析 / 写作 / 文档 / PPT / 知识库 五能力协同）

---

## 📄 License

MIT License · Copyright (c) 2026 Damia

详见 [LICENSE](LICENSE)

---

## 🙏 致谢

- **办公小浣熊** · 全程驱动本作品构建（0 行手写代码）
- **女娲抟土造人** · 提供了产品命名与品牌叙事的文化锚点
- **Datawhale 与商汤** · 主办 OPC 高手创造赛

---

> *三千年前，女娲用一捧泥造出了人。*
> *三千年后，你用一万条碎片，造你自己的知识。*

**抟知 ToKnow** · Made with ❤️ by Damia
