---
name: cover-studio
description: 万能封面工作室 (Cover Studio) - 一站式全平台爆款封面选型与生成 Skill。集成社区 9 大顶级开源封面引擎，智能路由 4 大流派。输入文章后自动确认文字层级（大字标题/副标题/小标签），直接并行输出 3 种不同风格的成图或 Nano Banana (Google Flow 免费平台) 提示词，支持全平台多尺寸一键批量出图与品牌固化。
---

# 🎨 Cover Studio (万能封面工作室)

`cover-studio` 是一站式解决全平台封面制作与排版困扰的 AI Skill。无需在数十个独立封面工具间纠结，它通过智能路由机制，将社区最成熟的 **9 大开源封面引擎** 融会贯通，提供从**出图偏好配置 ➔ 文字层级精准确认 ➔ 3 种风格直接出图/出提示词 ➔ 全平台多尺寸交付**的极简闭环。

---

## 🧭 标准交互全流程图 (Standardized Workflow)

```mermaid
flowchart TD
    subgraph S0["⚙️ 首次配置 (仅首次问询)"]
        A0[用户安装/唤醒 Skill] --> A1[确认出图偏好模式:<br/>1. 🌟 统一品牌多尺寸分发模式 (选定后批量出全套尺寸)<br/>2. 🎯 单尺寸独立定制模式]
    end

    subgraph S1["📝 阶段一：文章录入与文字层级确认"]
        B0[用户输入文章/标题/口播草稿] --> B1[Skill 自动提取并与用户确认 3 大文字层级:<br/>1. 📌 大字主标题 (≤6-8字，高对比吸睛核心)<br/>2. 📝 副标题 (10-15字，阐明具体价值)<br/>3. 🏷️ 小标签元素 (胶囊标签/勾选框/痛点短词)]
    end

    subgraph S2["🎨 阶段二：3 种不同风格直接出图 / 出提示词"]
        C0[用户确认文字内容] --> C1[基于确认的文字，直接并行生成 3 套不同风格的成图 / 提示词:<br/>• 风格 A: 赛博极客/科技感 (基于 punk-cover)<br/>• 风格 B: 爆款干货/大字视觉锚点 (基于 atutun-xhs / ponyo)<br/>• 风格 C: 深度专栏/典雅知识流 (基于 knowledge-media)]
    end

    subgraph S3["🚀 阶段三：用户挑选 ➔ 全平台多端最终交付"]
        D0[用户选定心仪风格 (A / B / C)] --> D1{根据阶段 0 预设偏好}
        D1 -->|统一品牌多尺寸模式| D2[一键批量交付全平台多画幅尺寸:<br/>小红书 3:4 + 公众号 2.35:1 + X 16:9/5:2]
        D1 -->|单尺寸定制模式| D3[交付当前画幅专属版本]
        D2 --> D4[Codex 本地一键直出成图 OR 输出 Google Flow Nano Banana 免费出图指引]
        D3 --> D4
    end

    S0 --> S1 --> S2 --> S3
```

---

## 阶段 0：首次配置出图模式偏好 (First-Run Intake)

在用户首次安装或初次使用时，**第一时间主动确认出图偏好**（后续无需每次重复问询）：

> **“欢迎使用 Cover Studio 万能封面工作室！🐻✨ 为方便后续极速出图，请先告诉我您的常用出图偏好：”**
> 
> 1. 🌟 **【统一品牌多尺寸分发模式】（推荐）**：每次选定 1 个心仪风格后，自动为您**一次性批量输出全部多平台自适应尺寸**（默认包含：小红书 `3:4`、微信公众号 `2.35:1`、X/推特 `16:9` / `5:2`、视频横版 `16:9` 等），让全网多端视觉高度统一。
> 2. 🎯 **【单尺寸独立定制模式】**：每次只针对当前指定的单一画幅单独定制不同风格。
> 
> *(该偏好会保存在记忆中，随时可修改)*

---

## 阶段 1：文章录入与【文字层级强制核对】(Text Alignment)

用户输入文章标题、长文或口播草稿后，Skill **首先提取核心信息并强制与用户核对 3 大文字层级**：

```markdown
👌 已深度分析您的文章内容！在为您直接生成 3 套不同风格封面之前，请先核对文字排版层级：

1. 📌 **大字主标题 (Main Headline)**：`普通人翻盘` （≤6-8字，最核心痛点，超大字高对比度呈现）
2. 📝 **副标题 / 价值阐述 (Sub-headline)**：`AI 时代个人商业闭环与实操指南` （10-15字，阐释具体价值）
3. 🏷️ **小文字与标签元素 (Pill Badges & Tags)**：
   - 分类胶囊标签：`[实操干货]` / `[2026最新]`
   - 勾选亮点短词：`✔ 0门槛` · `✔ 附 Prompt 模板` · `✔ 一键复用`

👉 **请确认文字是否符合预期？（直接回复“确认”或直接告知修改意见）**
```

---

## 阶段 2：基于确认文字，直接生成 3 组风格成图/提示词 (Direct 3-Style Generation)

用户确认文字后，Skill **不废话、不给空洞选项，而是直接生成 3 种完全不同流派的完整作品**：

- **Codex / 本地环境**：直接调用绘图工具生成 3 张高清成品图展示；
- **标准对话环境**：直接输出 3 套完整的、包含确认文字指令的 **Nano Banana 英文生图 Prompt**。

### 输出范例：
```markdown
🎨 已根据确认的文字层级，为您直接生成 3 种不同流派的封面结果：

---
### 🖼️ 风格 A：【赛博极客 · 现代科技流】（基于 punk-cover 理念）
- 📐 **画幅**：16:9 / 5:2（X / 即刻 / 科技专栏）
- 💡 **画面**：冷调灰网格背景，发光 3D 芯片悬浮，左侧极简排版大字「普通人翻盘」与标签「实操干货」
- 📝 **直接可用生图 Prompt**：
```text
High-end editorial tech cover illustration, aspect ratio 16:9, clean off-white background with subtle circuit grid, glowing cyan and electric purple accents. Centerpiece: a stylized minimalist 3D rendering of glowing GPU microchips. Text overlay: bold headline "普通人翻盘", sub-headline "AI 时代个人商业闭环与实操指南", pill badge "[实操干货]". Sleek isometric perspective, professional studio lighting, 8k resolution.
```

---
### 🖼️ 风格 B：【爆款干货 · 大字视觉锚点流】（基于 atutun-xhs / ponyo 理念）
- 📐 **画幅**：3:4（小红书竖版）
- 💡 **画面**：明亮暖色底，顶部亮黄色高反差大字标题卡片「普通人翻盘」，配 Q 版手势与清单勾选框
- 📝 **直接可用生图 Prompt**：
```text
Viral Xiaohongshu style knowledge guide cover, vertical 3:4 aspect ratio, vibrant and friendly atmosphere. Bright warm lighting, soft pastel background. Upper section features large bold typographic hook area with high-contrast yellow text card reading "普通人翻盘", supporting text "AI 时代个人商业闭环与实操指南", and checklist items "✔ 0门槛", "✔ 附 Prompt 模板".
```

---
### 🖼️ 风格 C：【深度专栏 · 典雅知识自媒体流】（基于 knowledge-media 理念）
- 📐 **画幅**：2.35:1（微信公众号首图，通过 1:1 居中测试）
- 💡 **画面**：暖象牙纸质底色 #F7F5EE，暗红小标签「实操干货」，居中抽象商业飞轮与大字标题
- 📝 **直接可用生图 Prompt**：
```text
Sophisticated editorial publication header banner, ultra-wide 2.35:1 aspect ratio, warm fine ivory paper texture background #F7F5EE. Centered visual composition: elegant conceptual illustration with restrained deep crimson and slate gray accents. Typography: centered clean headline "普通人翻盘", subtitle "AI 时代个人商业闭环与实操指南".
```

---
👉 **请回复您选中的风格（A / B / C）！**
```

---

## 阶段 3：用户挑选 ➔ 最终多端交付与免费出图指引

用户回复选定风格（如“选 B”）后：
1. **多尺寸批量出图（若处于阶段 0 统一品牌模式）**：
   - 自动基于选中的风格 B，一键输出该风格下适配**小红书 3:4**、**公众号 2.35:1**、**X 16:9 / 5:2** 的全套尺寸图片或提示词！
2. **免费出图操作指引（无本地生图环境时提供）**：
   > 💡 **Google Flow 免费生图指南**：
   > 1. 打开 **[Google Flow 平台 (flow.google)](https://flow.google)**；
   > 2. 模型选择免费的 **Nano Banana**；
   > 3. 粘贴上述英文 Prompt，即可免费秒出超清封面大图！

---

## 📚 4 大流派 · 9 大开源封面引擎速查表

| 流派 | 引擎名 | GitHub 地址 | 特色风格 | 最佳适配场景 |
|---|---|---|---|---|
| **跨平台全能** | `punk-cover` | [adrianpunk/Punk-Skill](https://github.com/adrianpunk/Punk-Skill) | 赛博极客 / 现代科技风 | 3:4 / 2.35:1 / 5:2 三端自适应，可配虚拟人设 |
| **跨平台全能** | `huashu-skills` | [alchaincyf/huashu-skills](https://github.com/alchaincyf/huashu-skills) | 大厂发布会 / 工业级设计 | AI 生图 + HTML 矢量渲染双路径 |
| **跨平台全能** | `rn-cover-skill` | [Pluviobyte/rnskill](https://github.com/Pluviobyte/rnskill) | 5:2 编辑图解风 | 暖白底 + 粗黑大标题 + 概念主图，严肃知识感 |
| **小红书 3:4** | `atutun-xhs-cover` | [panggungunvibe/atutun-xhs-cover](https://github.com/panggungunvibe/atutun-xhs-cover) | 真人出镜 + 荧光黄大字 | 小红书百万干货排版逻辑，单选题引导 |
| **小红书 3:4** | `gbro-cover-design` | [pyang5166/gbro-cover-design](https://github.com/pyang5166/gbro-cover-design) | 纯色扁平 / 产品主视觉 | 10种高频构图，UI 界面卡片挂接 |
| **小红书 3:4** | `ponyo-cover-anchor-system` | [ponyodong2026/ponyo-cover-anchor-system](https://github.com/ponyodong2026/ponyo-cover-anchor-system) | 情绪冲突 + 涂鸦撕纸拼贴 | 视觉锚点与痛点钩子，专治低点击率 |
| **公众号 2.35:1** | `knowledge-media-cover` | [aa1143/knowledge-media-cover](https://github.com/aa1143/knowledge-media-cover) | 暖象牙纸底 + 暗红标签 | 专属文字保护区，整年封面长得像一家人 |
| **公众号 2.35:1** | `wechatcover` | [naplesblue/wechatcover](https://github.com/naplesblue/wechatcover) | 艺术指导级精准排版 | 固化 brand_system.md，中文不乱码 |
| **视频实操** | `oil-cover` | [oil-oil/oil-cover](https://github.com/oil-oil/oil-cover) | Apple 极简 + Mac 视窗 | 截取视频关键帧，3:4 / 4:3 / 16:9 多端输出 |

---

## 🛠️ 参考文档导航
- 详细引擎特性解析：[references/skills-catalog.md](references/skills-catalog.md)
- 各平台画幅与文字层级规范：[references/platform-specs.md](references/platform-specs.md)
- 提示词配方与 Nano Banana 指引：[references/prompt-recipes.md](references/prompt-recipes.md)
- 品牌固化系统配置模板：[references/brand-system.md](references/brand-system.md)
