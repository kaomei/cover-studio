---
name: cover-studio
description: 万能封面工作室 (Cover Studio) - 一站式全平台爆款封面选型与生成 Skill。集成社区 9 大顶级开源封面引擎，智能路由 4 大流派。输入文章后自动并行提供 3 种最匹配的风格排版方案，支持一键固化品牌系统、多尺寸多平台批量出图，提供 Codex 环境直接出图与 Nano Banana (Google Flow 免费平台) 提示词双路径交付。
---

# 🎨 Cover Studio (万能封面工作室)

`cover-studio` 是一站式解决全平台封面选择困扰的 AI Skill。无需在数十个独立封面工具间反复纠结，它通过智能路由机制，将社区最成熟的 **9 大开源封面引擎** 融会贯通，遵循「三大黄金铁律」，提供从**风格推荐 ➔ 品牌固化 ➔ 双路径交付**的极简工作流。

---

## 🧭 核心交互流程 (Interactive Workflow)

```mermaid
flowchart TD
    A[用户输入文章/标题/口播内容] --> B[步骤 1: 深度分析并并行输出 3 种最适配风格方案]
    B --> C[步骤 2: 用户确认心仪方案 1/2/3]
    C --> D{步骤 3: 询问品牌系统偏好}
    D -->|选项 A| E[固化为品牌标准: 批量输出多平台自适应尺寸 3:4 / 2.35:1 / 16:9]
    D -->|选项 B| F[单平台定制: 针对指定画幅输出专属定制版本]
    E --> G{步骤 4: 判断执行环境}
    F --> G
    G -->|Codex / 本地有生图工具| H[路径 A: 本地一键直出渲染高清封面]
    G -->|标准对话 / 外部生图| I[路径 B: 输出 Nano Banana 免费生图 Prompt + Google Flow 指引]
```

---

## 阶段一：初次同步与三方案并行推荐 (First Run & 3-Style Proposal)

当用户唤醒 `$cover-studio` 并输入文章标题、长文或口播草稿时，Skill **自动解析文章的主题属性、受众圈层与情绪张力**，并**同时输出 3 种截然不同但最契合内容的风格排版方案**供用户挑选：

### 输出格式示例：
```markdown
🎨 已为您深度分析文章内容，生成 3 组最匹配的封面排版方案：

---

### 方案 1：【赛博极客 · 现代科技流】（基于 punk-cover 理念）
- 📐 **推荐画幅**：X 16:9 / 5:2 或 小红书 3:4
- 💡 **视觉隐喻**：发光芯片在冷调灰网格上浮空旋转，左侧留出高对比度无衬线主标题
- 🎯 **适合场景**：AI 评测、开发者工具、Vibe Coding 技术教程
- 📝 **生图 Prompt 预览**：`High-end editorial tech cover illustration, aspect ratio 16:9...`

---

### 方案 2：【爆款干货 · 大字视觉锚点流】（基于 atutun-xhs / ponyo 理念）
- 📐 **推荐画幅**：小红书 3:4 竖版
- 💡 **视觉隐喻**：暖色明亮背景，顶部大字荧光黄色标题卡片 + 趣味表情包/人物手势痛点指引
- 🎯 **适合场景**：搞钱攻略、自媒体实操、小红书高 CTR 点击收割
- 📝 **生图 Prompt 预览**：`Viral Xiaohongshu style knowledge guide cover, vertical 3:4...`

---

### 方案 3：【深度专栏 · 典雅知识自媒体流】（基于 knowledge-media 理念）
- 📐 **推荐画幅**：微信公众号 2.35:1 / 全平台头图
- 💡 **视觉隐喻**：暖白高级纸张质感底色，暗红小标签分割，居中优雅抽象概念插画（1:1 方块安全区）
- 🎯 **适合场景**：商业深度观察、行业专栏、机构号品牌沉淀
- 📝 **生图 Prompt 预览**：`Sophisticated editorial publication header banner, ultra-wide 2.35:1...`

---

👉 **请回复您心仪的方案编号（1 / 2 / 3），或提出微调要求！**
```

---

## 阶段二：方案确认与品牌系统偏好 (Brand Preference Intake)

一旦用户确认了心仪方案（如回复“选方案 1”），Skill **立刻主动询问用户的品牌固化与分发偏好**：

> **“收到！已为您锁定该风格方案。请问您希望：”**
> 1. 🌟 **【固化为品牌标准 (Brand System)】**：将此风格保存为您的固定品牌体系，未来自动保持一致视觉基调，并**一次性批量输出全部多平台自适应尺寸**（小红书 3:4、公众号 2.35:1、X 16:9 / 5:2 等），方便多端一键分发？
> 2. 🎯 **【单平台独立出图】**：仅针对当前特定平台/尺寸出图，未来每个尺寸独立选用不同风格？

---

## 阶段三：双路径交付机制 (Dual-Path Delivery)

确认偏好后，Skill 根据用户当前运行环境提供最丝滑的生成路径：

### 路径 A：Codex / 本地具备生图环境
- 直接调用绘图工具（如 `generate_image` / DALL-E / Imagen）一键完成画面渲染。
- 将高清成品图写入工作区并提供下载链接。

### 路径 B：无本地生图环境 ➔ Nano Banana / Google Flow 免费直出
- 为用户输出经过精心架构调优的 **Nano Banana 英文生图提示词**。
- 提供保姆级免费出图指引：
  > 💡 **免费出图小贴士**：您可以直接打开 **[Google Flow 平台 (flow.google)](https://flow.google)**，选择免费的 **Nano Banana** 模型，将上方英文 Prompt 粘贴进去，即可免费生成超清大图！

---

## 🌟 封面选型的「三大黄金铁律」

1. **画幅决定构图，切忌硬裁**：
   - 小红书（`3:4` 垂直动线）、公众号（`2.35:1` 扁平横幅）、X/推特（`5:2` 或 `16:9` 极宽视野）。
   - 必须针对画幅重新组织主视觉与留白，严禁机械拉伸或切掉主体。
2. **分清 Prompt 派 vs 直出派**：
   - **Prompt 派**：生成高质量提示词，适合去 Google Flow (Nano Banana)、Midjourney、即梦等细致出图。
   - **直出派**：利用环境工具或 HTML 矢量渲染秒出成品。
3. **建立固定品牌系统 (Brand System)**：
   - 让读者“不看作者名就知道是你”，保持色调、字体、留白的一致性。

---

## 📚 集成的 9 大开源封面引擎速查

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
- 各平台画幅与避让安全区：[references/platform-specs.md](references/platform-specs.md)
- 提示词配方与 Nano Banana 指引：[references/prompt-recipes.md](references/prompt-recipes.md)
- 品牌固化系统配置模板：[references/brand-system.md](references/brand-system.md)
