# ToKnow
基于办公小浣熊的个人知识资产化系统

# 📦 抟知 ToKnow · GitHub README

````markdown
<div align="center">

<!-- 顶部 Banner / Logo 占位 -->
<img src="docs/banner.png" alt="ToKnow Banner" width="820"/>

# 抟知 · ToKnow

### 把你收藏夹里的"数字灰尘"，重新捏成知识。

**基于办公小浣熊的个人知识资产化系统**

[

![图片](https://img.shields.io/badge/version-V15.6-ff5e62?style=flat-square)

](#)
[

![图片](https://img.shields.io/badge/build-single--file-1f8feb?style=flat-square)

](#)
[

![图片](https://img.shields.io/badge/size-244KB-7c3aed?style=flat-square)

](#)
[

![图片](https://img.shields.io/badge/dependencies-ZERO-22c55e?style=flat-square)

](#)
[

![图片](https://img.shields.io/badge/deploy-Vercel%20%7C%20Netlify%20%7C%20Pages-000?style=flat-square)

](#)
[

![图片](https://img.shields.io/badge/license-MIT-fbbf24?style=flat-square)

](#)
[

![图片](https://img.shields.io/badge/built%20with-办公小浣熊-fb7185?style=flat-square)

](#)

[🚀 在线体验](#) · [🎞 演示视频](#-demo-视频) · [📊 闪电演讲 PPT](#-pitch-deck) · [🧠 Prompt 工程](#-prompt-工程) · [📮 联系作者](#-author)

</div>

---

## 🌌 为什么会有它？

> **数千年前，女娲用一捧泥造出了人。**  
> **数千年后，你用一万条碎片，造你自己的知识。**

你的论文摘要、网页收藏、灵感截图、跨平台笔记，正在十几个 App 之间各自冷宫。  
"收藏很多，真正用起来的很少"——这是被普遍困扰、却被市场忽略的命题。

**抟知 ToKnow** 不是再做一个笔记本，而是一台**复活机**：  
把沉睡在收藏夹与备忘录里的信息，重新转化为**可分析、可调用、可创作、可交付**的个人知识资产。

> *面向科研者 · 内容创作者 · 高灵感人群（也就是那种"灵感很多但产出很少"的同学，没错，说的就是你 🫵）*

---

## 🎞 Demo 视频

<!-- 在此处替换为你的演示视频。GitHub 支持 mp4 / mov 直接拖拽上传后嵌入 -->
<div align="center">

<a href="https://your-video-link.example.com">
  <img src="docs/video-cover.png" alt="ToKnow Demo Video" width="720"/>
</a>

▶️ *点击封面观看 90 秒完整演示（替换为你的视频地址）*

</div>

---

## 📊 Pitch Deck

<!-- 在此处替换为你的 PPT。可使用 GitHub Releases 上传 .pptx，或嵌入 SlideShare / 飞书 -->
<div align="center">

| 📁 文件 | 🔗 链接 |
|---|---|
| 闪电演讲 PPT（.pptx） | [点此下载](docs/ToKnow-V15.6-PPT-Damia.pptx) |
| 闪电演讲文档（.docx） | [点此下载](docs/ToKnow-V15.6-Pitch-Damia.docx) |
| 在线幻灯片预览 | [点此打开](https://your-slides-link.example.com) |

<img src="docs/slides-preview.png" alt="Slides Preview" width="720"/>

</div>

---

## ✨ 核心能力一览

| | 模块 | 一句话说明 |
|---|---|---|
| 🗂 | **灵感典藏** | 上传 Excel/CSV/JSON → 19 字段标准化 → 瀑布流 + 4 筛选 |
| 🧬 | **知识画像** | 高频关键词 / 主题簇 / 跨领域连接 / 沉睡复活 / 最值得发展方向 |
| 🧭 | **发展方向** | 6 大方向 × 12 联想角度，给"今天写什么"一个答案 |
| ✍️ | **三档草稿** | 200 字简版 / 800 字标准 / 2000 字完整 — 真独立稿，不是截取 |
| 🎬 | **6 大动作** | 标题组 / 封面 / 小红书 9 图 / 视频分镜 / 口播稿 / 系列规划 |
| 📱 | **平台样例** | 小红书 / B 站 / 公众号 / 抖音 — 点一下，看成品 |

> **6 方向 × 3 档 = 18 篇独立草稿** ＋ **6 方向 × 6 动作 = 36 套可复制成品**，全部预设。  
> *是的，不是按钮的样子，是按钮按下去之后的东西。*

---

## 🧩 产品架构

```
                ┌──────────────────────────────┐
                │   Excel / CSV / JSON 上传     │
                └──────────────┬───────────────┘
                               ▼
   ┌──────────┐   ┌──────────┐   ┌──────────┐   ┌──────────┐
   │  首页    │ → │ 灵感典藏 │ → │ 知识画像 │ → │ 发展方向 │
   │  Home    │   │Inspire   │   │Portrait  │   │Direction │
   └──────────┘   └──────────┘   └─────┬────┘   └─────┬────┘
                                       ▼              ▼
                              ┌──────────────────────────┐
                              │   生成成果工作台 ⚙️       │
                              │  3 档草稿 × 6 动作        │
                              └──────────────────────────┘
                                       ▼
                              ┌──────────────────────────┐
                              │   我的 · 登录 / 游客模式   │
                              └──────────────────────────┘
```

---

## 🛠 技术栈

- **前端**：原生 HTML5 + ES6 + CSS3，零依赖、零外部 CDN
- **数据**：JSON 数组 / SheetJS（xlsx）/ 内置 CSV 解析（19 字段标准）
- **持久化**：`localStorage`（筛选状态、待生成库、登录态、游客模式、昵称）
- **样式**：方正小标宋 → Songti SC → SimSun 回退；sticky 导航 + backdrop-filter
- **部署**：单文件 HTML（~244 KB / gzip ~55 KB），任意静态托管
- **隐私**：所有运算在浏览器本地，**零数据外传**

| 指标 | 数值 |
|---|---|
| 单文件大小 | 244 KB（未压缩）/ ~55 KB（gzip） |
| 首屏渲染 | < 150 ms（本地） |
| 页面切换 | 0.4s 缓入缓出 |
| 兼容性 | Chrome 90+ / Edge 90+ / Safari 14+ / Firefox 88+ |

---

## 🚀 快速开始

```bash
# 1. 克隆仓库
git clone https://github.com/<your-name>/toknow.git
cd toknow

# 2. 直接打开（没错，没有第 3 步）
open ToKnow-V15.6-Damia.html
```

或者一键部署：

[

![图片](https://vercel.com/button)

](#) &nbsp;
[

![图片](https://www.netlify.com/img/deploy/button.svg)

](#) &nbsp;
[

![图片](https://img.shields.io/badge/GitHub-Pages-181717?style=flat-square&logo=github)

](#)

> *把它丢进任何能托管 HTML 的地方，它就活了。比你的健身计划更容易上线。*

---

## 🧠 Prompt 工程

抟知 ToKnow 是一款**全程由 Prompt 驱动构建**的产品——从需求拆解到迭代上线，无任何手写代码。

**四个原则**：

1. **上下文塞满**：告诉模型"这是什么数据、用户是谁、目标是什么"
2. **约束清晰**：禁止虚构、不存在的卡片不引用、宁缺勿凑
3. **分步任务**：第一步分析字段，第二步生成 HTML，每步可检查可回退
4. **具体到字数 / 结构 / 元素**：不要"写一篇文章"，要"800 字 / 6 段 / 含开头钩子和结尾互动"

**演进时间线**：

| 版本 | 关键 Prompt 调整 | 产品形态变化 |
|---|---|---|
| V1 | 数据理解 + HTML 初版 | 一个简单的卡片池 |
| V4 | 联想引擎 12 角度 | 多角度选题发散 |
| V8 | 真实性约束 | 禁止虚构文献 |
| V12 | 工作台 6 段结构 | 创作者工作台成型 |
| V14 | 三档草稿生成 | 复制即用的真实成稿 |
| V15 | 可点击动作 + 平台样例 | 弹窗式真实生成结果 |
| **V15.6** | **文档化 Prompt 工程** | **可复用、可教学** |

📄 完整 4 个核心 Prompt 原词见 [`docs/TechDoc.md`](docs/TechDoc.md#7-prompt-工程)

---

## 🗺 Roadmap

- [x] V15.6 · 三档草稿 + 6 动作 + 平台样例 + 登录态
- [ ] 接入用户系统（Supabase / Clerk）
- [ ] 数据库持久化（PostgreSQL / SQLite）
- [ ] 实时联网搜索（Bing API / Google CSE）
- [ ] 多人协作（WebSocket / CRDT）
- [ ] 移动端原生壳（Tauri / Capacitor）

---

## 📁 交付物清单

| 类别 | 文件 | 大小 |
|---|---|---|
| 演示 | `ToKnow-V15.6-Damia.html` | 244 KB |
| 演示 | `ToKnow-V15.6-PPT-Damia.pptx` | 75 KB |
| 文档 | `ToKnow-V15.6-Pitch-Damia.docx` | 38 KB |
| 文档 | `ToKnow-V15.6-ProductDoc-Damia.docx` | ~60 KB |
| 文档 | `ToKnow-V15.6-TechDoc-Damia.docx` | ~55 KB |
| 文档 | `ToKnow-V15-DeployGuide-Damia.docx` | 38 KB |
| 数据 | `ToKnow-V15-Database.xlsx` | 28 KB |

---

## 🔐 安全与隐私

- 所有运算在**浏览器本地**完成
- 上传的 Excel **不会上传到服务器**
- `localStorage` 仅保留在本设备
- 登录态可一键退出清除

> *你的灵感是你自己的，不是任何云的。*

---

## 👤 Author

**Damia** · 2026.06.21  
> "做一个真正能把私人知识调用起来的系统——不是再做一个笔记本，是一台复活机。"

- 📮 Email: `your@email.com`
- 🐦 Twitter / X: `@yourhandle`
- 📕 小红书 / 公众号: `抟知 ToKnow`

---

## 📜 License

MIT © 2026 Damia · 自由使用、自由魔改、用之有德。

---

<div align="center">

**如果它帮你少打开了一次收藏夹，就给它一颗 ⭐ 吧。**

<sub>Built with 🦝 办公小浣熊 · Powered by Prompt Engineering · Made in 2026</sub>

</div>
````

---

## 🧷 使用提示

1. **PPT 占位**：把第 `📊 Pitch Deck` 区块的链接换成你 GitHub Releases 上传的 `.pptx`，或飞书/腾讯文档分享链接。
2. **视频占位**：把第 `🎞 Demo 视频` 区块的封面图与链接替换为你的 mp4 直链（GitHub Issue 拖拽上传即可获取直链）。
3. **图片资源**：建议在仓库根目录建 `docs/` 文件夹，放入 `banner.png` / `video-cover.png` / `slides-preview.png`。
4. **徽章颜色**：当前色系为「珊瑚红 / 宝蓝 / 紫 / 翠绿 / 琥珀」，与"抟泥造物"的暖色叙事一致，可按需在 `shields.io` 后缀 `&color=xxxxxx` 自定义。
5. **一键复制**：上面整个 ` ```markdown ` 代码块即为最终 README.md，复制 → 粘贴 → 推送即可。
