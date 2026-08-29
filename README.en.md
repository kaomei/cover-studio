<div align="center">

[简体中文](README.md) · [**English**](README.en.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md)

# 🎨 Cover Studio

### All-in-One Viral Cover Design Workflow · Integrated with 9 Top Open-Source Cover Engines

An open-source AI Skill designed for creators, developers, writers, and tech bloggers. Solves cover choice paralysis! Configures output mode on first install, **first aligns headline & sub-element text hierarchy**, and **directly generates 3 distinct style images or prompts simultaneously**. Supports one-click Brand System locking, **Codex in-tool generation**, and **Nano Banana (Google Flow free platform) prompt delivery**.

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
- ✍️ **Text Hierarchy First Alignment**: Clarifies the exact wording for **Main Headline Hook**, **Sub-headline**, and **Pill Badges / Tags** before generating artwork.
- 🖼️ **Direct 3-Style Generation**: Directly generates 3 fully rendered images or ready-to-run prompts across distinct visual streams simultaneously.
- 🏷️ **One-Click Brand System Locking**: Lock your chosen style as your persistent brand VI so readers recognize your content across platforms.
- 📐 **3 Golden Rules of Re-composition**: Dynamically re-arranges visuals and safe zones for Xiaohongshu (`3:4`), WeChat (`2.35:1`), and X (`16:9` / `5:2`) without arbitrary cropping.
- 🚀 **Dual-Path Delivery (Codex Direct + Nano Banana Free)**:
  - **Codex / Local Tool**: Generates high-res image directly in conversation.
  - **Standard Chat**: Outputs structured English prompts tuned for **Nano Banana**, completely free to run on **Google Flow (flow.google)**.
- 🔄 **9 Curated Open-Source Cover Engines**: Seamlessly routes across 9 battle-tested community skills without installing each individually.

---

## 🛠️ Standardized Workflow

```mermaid
flowchart TD
    subgraph S0["⚙️ First-Run Setup (One-time)"]
        A0[Install / Wake Skill] --> A1[Confirm Output Mode Preference:<br/>1. 🌟 Multi-size Unified Brand Batch Mode<br/>2. 🎯 Single-size Custom Mode]
    end

    subgraph S1["📝 Phase 1: Input & Text Hierarchy Alignment"]
        B0[Input Article / Title / Script] --> B1[Skill Extracts & Aligns 3 Text Tiers:<br/>1. 📌 Main Headline Hook<br/>2. 📝 Sub-headline Value Prop<br/>3. 🏷️ Pill Badges & Checklist Tags]
    end

    subgraph S2["🎨 Phase 2: Direct 3-Style Image / Prompt Generation"]
        C0[User Confirms Text] --> C1[Directly Produce 3 Distinct Results / Prompts:<br/>• Style A: Cyber Tech / Geek (punk-cover)<br/>• Style B: Viral Big-Text Hook (atutun-xhs / ponyo)<br/>• Style C: Deep Editorial (knowledge-media)]
    end

    subgraph S3["🚀 Phase 3: Pick & Multi-Platform Final Delivery"]
        D0[User Picks Favorite (A / B / C)] --> D1{Check Phase 0 Preference}
        D1 -->|Unified Brand Mode| D2[Batch Export Full Multi-Ratio Assets:<br/>XHS 3:4 + WeChat 2.35:1 + X 16:9/5:2]
        D1 -->|Single Size Mode| D3[Export Custom Size Asset]
        D2 --> D4[Codex In-Tool Direct Render OR Free Google Flow Guide]
        D3 --> D4
    end

    S0 --> S1 --> S2 --> S3
```

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
