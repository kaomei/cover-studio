# 🎨 Cover Studio 集成开源封面引擎库 (Skills Catalog)

Cover Studio 不重复造轮子，而是精选并无缝路由至社区最顶级的 9 款开源封面引擎，按「4 大流派」分类适配：

---

## 🌟 封面选型的「三大黄金铁律」

1. **画幅决定构图，切忌硬裁**：
   - 小红书（`3:4` 垂直视觉动线，留出上下 UI 与互动区）
   - 公众号（`2.35:1` 扁平横幅，视觉中心聚焦，防居中裁剪变形）
   - X / 推特（`5:2` 或 `16:9` 极宽视野，留白与标题清晰）
   - 优秀的封面工作流必须根据目标画幅重新规划排版，而不是简单拉伸或硬切。
2. **分清 Prompt 派 vs 直出派**：
   - **Prompt 派**（输出高质量生图提示词）：适合直接配合 Nano Banana（Google Flow 平台免费使用）、Midjourney、即梦、FLUX 细致出图。
   - **直出派**（HTML/SVG/API 矢量渲染）：适合在 Codex / Claude Code / Antigravity 环境下秒级直接生成。
3. **建立固定品牌系统 (Brand System)**：
   - 深度知识博主与品牌号切忌每期风格大乱炖；固定一套配色、字体与构图系统，让读者“不看作者名就知道是你”。

---

## 一、 🌐 跨平台全能流（小红书 / 公众号 / X 三端通吃）
> **适用场景**：一个人运营多平台、希望一份文章内容自适应输出多端不同画幅的超级个体与独立创作者。

### 1️⃣ adrianpunk/Punk-Skill (`punk-cover`) ⭐ 821
- **GitHub**: [github.com/adrianpunk/Punk-Skill](https://github.com/adrianpunk/Punk-Skill)
- **视觉风格**: 赛博极客 / 现代科技风 / 极简线框 / 冷调高级灰。
- **核心亮点**: 支持按小红书 `3:4`、公众号 `2.35:1`、X `5:2` 三种画幅自适应重排主视觉；搭配 `punk-avatar` 可锁定统一的虚拟人设出镜。
- **适合人群**: AI 开发者、科技博主、Vibe Coding 玩家。

### 2️⃣ alchaincyf/huashu-skills (花叔封面系列) ⭐ 1,421
- **GitHub**: [github.com/alchaincyf/huashu-skills](https://github.com/alchaincyf/huashu-skills)
- **视觉风格**: 大厂发布会 / 工业级高质感设计 / 品牌 Token 色彩系统。
- **核心亮点**: 提供 AI 生图 ＋ HTML 矢量渲染双路径；涵盖 `huashu-wechat-image`（公众号）、`huashu-xhs-image`（小红书）及信息图模块。
- **适合人群**: 品牌主理人、创业团队、高审美设计师。

### 3️⃣ Pluviobyte/rnskill (`rn-cover-skill`) ⭐ 1,419
- **GitHub**: [github.com/Pluviobyte/rnskill](https://github.com/Pluviobyte/rnskill)
- **视觉风格**: 5:2 编辑图解风（暖白底 ＋ 粗黑大标题 ＋ 右侧概念主图）。
- **核心亮点**: 专为推特和系列专栏头图优化，排版极其克制，具备极强的知识严肃感与证据感。
- **适合人群**: 深度技术拆解博主、行业研究员。

---

## 二、 📕 小红书竖版 3:4 爆款流（点击率收割机）
> **适用场景**：主攻小红书、需要高 CTR、大字钩子、人设出镜与高信息密度的创作者。

### 4️⃣ panggungunvibe/atutun-xhs-cover (阿囤囤风格) ⭐ 382
- **GitHub**: [github.com/panggungunvibe/atutun-xhs-cover](https://github.com/panggungunvibe/atutun-xhs-cover)
- **视觉风格**: 真人/人像出镜 ＋ 超大荧光黄/白描边大字 ＋ Emoji 贴纸 ＋ 清单勾选框。
- **核心亮点**: 复刻小红书百万级干货博主的排版逻辑；通过“一次只问一个单选题”引导完成人设、痛点词和画风配置。
- **适合人群**: 个人 IP 孵化、副业搞钱博主、实用干货博主。

### 5️⃣ pyang5166/gbro-cover-design ⭐ 708
- **GitHub**: [github.com/pyang5166/gbro-cover-design](https://github.com/pyang5166/gbro-cover-design)
- **视觉风格**: 纯色扁平 / 产品主视觉 / 对比卡片 / 极简留白。
- **核心亮点**: 内置 10 种高频构图，图 1 固定真人面孔，图 2 自动挂接 UI 界面截图，三轮提问即可生成完整生图 Prompt。
- **适合人群**: 工具测评博主、软件教程作者。

### 6️⃣ ponyodong2026/ponyo-cover-anchor-system (波妞钩子系统) ⭐ 181
- **GitHub**: [github.com/ponyodong2026/ponyo-cover-anchor-system](https://github.com/ponyodong2026/ponyo-cover-anchor-system)
- **视觉风格**: 情绪冲突 ＋ 数字量化 ＋ 截图证据 ＋ 涂鸦撕纸拼贴。
- **核心亮点**: 不只管画面，更主攻“视觉锚点与痛点钩子”，专治封面没有吸引力的顽疾。
- **适合人群**: 情感疗愈、自媒体认知、故事类博主。

---

## 三、 🟢 微信公众号横版 2.35:1 专用流（拒绝文字乱码）
> **适用场景**：深度长文作者、注重中文标题可读性与品牌沉淀的机构号与专栏作者。

### 7️⃣ aa1143/knowledge-media-cover (知识自媒体视觉系统)
- **GitHub**: [github.com/aa1143/knowledge-media-cover](https://github.com/aa1143/knowledge-media-cover)
- **视觉风格**: 暖象牙纸底色 ＋ 暗红标签分隔线 ＋ 居中大标题 ＋ 抽象概念隐喻图。
- **核心亮点**: 专治“封面风格每期大乱炖”！输入分类和标题，自动补齐副标题并匹配专属文字保护区，实现**“一整年的封面长得像一家人”**。
- **适合人群**: 泛知识自媒体、深度专栏作者、机构公众号。

### 8️⃣ naplesblue/wechatcover (品牌系统化封面)
- **GitHub**: [github.com/naplesblue/wechatcover](https://github.com/naplesblue/wechatcover)
- **视觉风格**: 艺术指导级排版 ＋ 精准中文排版。
- **核心亮点**: 允许创作者通过修改 `brand_system.md` 固化自己的配色与字体规则，让生图模型在生成底图的同时保证中文不乱码。
- **适合人群**: 企业公众号运营、要求严格品牌 VI 的专业作者。

---

## 四、 🎬 视频与实操工具专属流（证据感拉满）
> **适用场景**：B 站、抖音、油管的 AI 工具测评、开发实操录屏与极客技术视频。

### 9️⃣ oil-oil/oil-cover ⭐ 208
- **GitHub**: [github.com/oil-oil/oil-cover](https://github.com/oil-oil/oil-cover)
- **视觉风格**: Apple 极简高级感 ＋ 真实屏幕证据截图 ＋ 纯净无人物构图。
- **核心亮点**: 直接从视频中智能截取关键操作帧，自动套上 Mac 视窗外壳与大厂 Logo，同时输出小红书 `3:4`、B 站 `4:3` 与 `16:9` 封面。
- **适合人群**: Coding 录屏博主、AI 工具教程作者、极客开发者。
