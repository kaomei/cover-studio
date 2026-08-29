<div align="center">

[简体中文](README.md) · [**English**](README.en.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md)

# 🎨 Cover Studio

### All-in-One Viral Cover Design Workflow · Integrated with 9 Top Open-Source Cover Engines

An open-source AI Skill designed for creators, developers, writers, and tech bloggers. Solves cover choice paralysis! Clarifies output mode on first install, **simultaneously proposes 3 tailored layout options** upon article input, and **mandatorily aligns headline & sub-element text hierarchy** before generation. Supports one-click Brand System locking, **Codex in-tool generation**, and **Nano Banana (Google Flow free platform) prompt delivery**.

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111827?style=flat-square)
![9 Open-Source Engines](https://img.shields.io/badge/Engines-9%20Top%20Open--Source%20Skills-0066ff?style=flat-square)
![Multi-Platform Ratios](https://img.shields.io/badge/Ratios-3%3A4%20%7C%202.35%3A1%20%7C%2016%3A9-f59e0b?style=flat-square)
![Free Image Gen](https://img.shields.io/badge/Generation-Codex%20Direct%20%7C%20Nano%20Banana%20Free-8b5cf6?style=flat-square)
![MIT License](https://img.shields.io/badge/License-MIT-16a34a?style=flat-square)

<br/>

Ideal for: **Xiaohongshu viral notes, WeChat Official Account headers, X/Twitter articles, Bilibili/YouTube thumbnails, and GitHub Social Previews**.

</div>

---

## ✨ Key Features

- ⚙️ **First-Run Preference Intake**: Immediately asks whether you prefer batch multi-platform generation (3:4, 2.35:1, 16:9, etc.) or single-size custom styling.
- 🧠 **Simultaneous 3-Style Proposal**: Analyzes your content and recommends 3 distinct, high-converting layout concepts at once.
- ✍️ **Mandatory Text Hierarchy Alignment**: Every run confirms exact wording for **Main Headline**, **Sub-headline**, and **Pill Badges / Tags** before rendering.
- 🏷️ **One-Click Brand System Locking**: Lock your chosen style as your persistent brand VI so readers recognize your content across platforms.
- 📐 **3 Golden Rules of Re-composition**: Dynamically re-arranges visuals and safe zones for Xiaohongshu (`3:4`), WeChat (`2.35:1`), and X (`16:9` / `5:2`) without arbitrary cropping.
- 🚀 **Dual-Path Delivery (Codex Direct + Nano Banana Free)**:
  - **Codex / Local Tool**: Generates high-res image directly in conversation.
  - **Standard Chat**: Outputs structured English prompts tuned for **Nano Banana**, completely free to run on **Google Flow (flow.google)**.
- 🔄 **9 Curated Open-Source Cover Engines**: Seamlessly routes across 9 battle-tested community skills without installing each individually.

---

## 📚 4 Major Streams & 9 Integrated Engines Matrix

| Stream | Engine Name | GitHub Repo | Visual Characteristics | Best Suited For |
|:---|:---|:---|:---|:---|
| **🌐 Cross-Platform** | `punk-cover` | [adrianpunk/Punk-Skill](https://github.com/adrianpunk/Punk-Skill) | Cyberpunk / Modern Tech / Virtual Avatars | 3:4, 2.35:1, 5:2 multi-ratio adaptive |
| **🌐 Cross-Platform** | `huashu-skills` | [alchaincyf/huashu-skills](https://github.com/alchaincyf/huashu-skills) | Enterprise Launch / Industrial Design / Tokens | AI Gen + HTML Vector Rendering |
| **🌐 Cross-Platform** | `rn-cover-skill` | [Pluviobyte/rnskill](https://github.com/Pluviobyte/rnskill) | 5:2 Editorial Infographic / Bold Typography | Deep tech breakdowns, research reports |
| **📕 XHS 3:4** | `atutun-xhs-cover` | [panggungunvibe/atutun-xhs-cover](https://github.com/panggungunvibe/atutun-xhs-cover) | Presenter / Neon Bold Text / Checkbox Stickers | Creator branding, side hustle, actionable guides |
| **📕 XHS 3:4** | `gbro-cover-design` | [pyang5166/gbro-cover-design](https://github.com/pyang5166/gbro-cover-design) | Clean Flat / Product Visual / UI Cards | Tool reviews, software tutorials |
| **📕 XHS 3:4** | `ponyo-cover-anchor-system` | [ponyodong2026/ponyo-cover-anchor-system](https://github.com/ponyodong2026/ponyo-cover-anchor-system) | Emotional Conflict / Visual Anchors / Collage | Storytelling, mindset, high-CTR hooks |
| **🟢 WeChat 2.35:1** | `knowledge-media-cover` | [aa1143/knowledge-media-cover](https://github.com/aa1143/knowledge-media-cover) | Ivory Paper / Crimson Tag / Center Metaphor | Deep articles (passes 1:1 center crop) |
| **🟢 WeChat 2.35:1** | `wechatcover` | [naplesblue/wechatcover](https://github.com/naplesblue/wechatcover) | Art Director Typography / Brand Rules | Enterprise newsletters, publication VI |
| **🎬 Video Tutorial** | `oil-cover` | [oil-oil/oil-cover](https://github.com/oil-oil/oil-cover) | Apple Minimalist / Mac Window Shell / Screencap | Coding screencasts, AI tool tutorials |

---

## 🛠️ Standard Workflow

```mermaid
flowchart LR
    A[Stage 0: First-Run Output Preference] --> B[Stage 1: Input Article / Draft]
    B --> C[Stage 2: Propose 3 Distinct Concepts]
    C --> D[Stage 3: Pick & Mandatory Text Alignment]
    D --> E[Stage 4: Codex Direct Gen / Free Google Flow Gen]
```

---

## 📦 Installation & Quick Start

```bash
git clone https://github.com/kaomei/cover-studio.git
cd cover-studio

# Codex CLI
cp -R skills/cover-studio "${CODEX_HOME:-$HOME/.codex}/skills/cover-studio"

# Antigravity / Gemini CLI
cp -R skills/cover-studio ~/.gemini/config/skills/cover_studio
```

Invoke in conversation:

```text
Use $cover-studio to design a cover for my article:

Title: DeepSeek Explosion: How Creators Build Moats with AI
Content: [Paste your outline or script here]
```

---

## ⚠️ Disclaimer & IP Notice

1. **Open-Source Attribution**: `cover-studio` is an open-source workflow routing skill. All intellectual property of the 9 integrated skills belongs to their respective original authors.
2. **Non-Affiliation**: This project has no official commercial affiliation with Xiaohongshu, WeChat, X, or Google.
3. **Permitted Use**: Provided for educational, research, and compliant content creation.

---

## 🤝 Contributing

PRs, new open-source cover engine recommendations, and prompt recipes are welcome!

If this project helped your cover workflow, **please give it a ⭐️ Star to support kaomei**!

## 📄 License

[MIT License](LICENSE) © 2026 [kaomei](https://github.com/kaomei)
