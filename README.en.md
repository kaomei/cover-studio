<div align="center">

[简体中文](README.md) · [**English**](README.en.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md)

# 🎨 Universal Cover Skill (Cover Studio)

### All-in-One Viral Cover Design Workflow · Integrated with 9 Top Open-Source Cover Engines

An open-source AI Skill designed for creators, developers, writers, and tech bloggers. Solves cover choice paralysis! Configures your **clearly separated platform size bundle** upon installing Universal Cover Skill, **first aligns headline & sub-element text hierarchy**, and **directly generates 3 distinct style images or prompts simultaneously**. Supports one-click Brand System locking, **Codex in-tool generation**, and **Nano Banana (Google Flow free platform) prompt delivery**.

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111827?style=flat-square)
![9 Open-Source Engines](https://img.shields.io/badge/Engines-9%20Top%20Open--Source%20Skills-0066ff?style=flat-square)
![Discrete Ratios](https://img.shields.io/badge/Ratios-3%3A4%20%7C%202.35%3A1%20%7C%2016%3A9%20%7C%205%3A2-f59e0b?style=flat-square)
![Free Image Gen](https://img.shields.io/badge/Generation-Codex%20Direct%20%7C%20Nano%20Banana%20Free-8b5cf6?style=flat-square)
![MIT License](https://img.shields.io/badge/License-MIT-16a34a?style=flat-square)

<br/>

Ideal for: **Xiaohongshu viral notes, WeChat Official Account headers, X/Twitter articles, Bilibili/YouTube thumbnails, and GitHub Social Previews**.

</div>

---

## ✨ Key Features

- ⚙️ **Discrete Platform Size Bundle Setup**: Select distinct individual platform ratios for recurring batch output (e.g. XHS `3:4`, WeChat `2.35:1`, X Post `16:9`, X Article `5:2`, Video `16:9`, GitHub `2:1`, Square `1:1`).
- ✍️ **Text Hierarchy First Alignment**: Clarifies the exact wording for **Main Headline Hook**, **Sub-headline**, and **Pill Badges / Tags** before generating artwork.
- 🖼️ **Direct 3-Style Generation**: Directly generates 3 fully rendered images or ready-to-run prompts across distinct visual streams simultaneously.
- 🏷️ **One-Click Brand System Locking**: Lock your chosen style as your persistent brand VI so readers recognize your content across platforms.
- 📐 **3 Golden Rules of Re-composition**: Dynamically re-arranges visuals and safe zones for selected aspect ratios without arbitrary cropping.
- 🚀 **Dual-Path Delivery (Codex Direct + Nano Banana Free)**:
  - **Codex / Local Tool**: Generates high-res image directly in conversation.
  - **Standard Chat**: Outputs structured English prompts tuned for **Nano Banana**, completely free to run on **Google Flow (flow.google)**.
- 🔄 **9 Curated Open-Source Cover Engines**: Seamlessly routes across 9 battle-tested community skills without installing each individually.

---

## 🛠️ Standardized Workflow

```mermaid
flowchart TD
    classDef default fill:#ffffff,stroke:#e2e8f0,stroke-width:1.5px,color:#1e293b,rx:8px,ry:8px;
    classDef startNode fill:#0f172a,stroke:#0f172a,stroke-width:2px,color:#ffffff,font-weight:bold,rx:20px,ry:20px;
    classDef stepNode fill:#ffffff,stroke:#cbd5e1,stroke-width:1.5px,color:#0f172a,rx:8px,ry:8px;
    classDef highlightNode fill:#eff6ff,stroke:#2563eb,stroke-width:2px,color:#1e40af,font-weight:bold,rx:8px,ry:8px;

    A0(["🚀 Wake Universal Cover Skill"]):::startNode
    --> A1["<b>0. First-Run Preference (One-time)</b><br/>Select mode: Unified Brand Batch Mode (select platforms) or Single Size Mode"]:::stepNode
    --> A2["<b>1. Input Article ➔ Mandatory Text Hierarchy Alignment</b><br/>📌 Main Headline (≤8 words) ＋ 📝 Sub-headline ＋ 🏷️ Pill Badges"]:::highlightNode
    --> A3["<b>2. Direct 3-Style Generation</b><br/>Simultaneously produce 【Cyber Geek】·【Viral Big-Text】·【Deep Editorial】options"]:::stepNode
    --> A4["<b>3. Pick Favorite ➔ Rapid Batch Multi-Platform Delivery</b><br/>Codex in-tool direct render OR Google Flow (Nano Banana) free fast gen"]:::stepNode
```

---

## 📚 4 Major Streams & 9 Integrated Engines Matrix

```mermaid
flowchart LR
    classDef rootBox fill:#0f172a,stroke:#38bdf8,stroke-width:2px,color:#ffffff,font-weight:bold,rx:8px,ry:8px;
    classDef cat1 fill:#eff6ff,stroke:#2563eb,stroke-width:2px,color:#1e3a8a,font-weight:bold,rx:6px,ry:6px;
    classDef cat2 fill:#fff1f2,stroke:#e11d48,stroke-width:2px,color:#881337,font-weight:bold,rx:6px,ry:6px;
    classDef cat3 fill:#ecfdf5,stroke:#059669,stroke-width:2px,color:#064e3b,font-weight:bold,rx:6px,ry:6px;
    classDef cat4 fill:#faf5ff,stroke:#9333ea,stroke-width:2px,color:#581c87,font-weight:bold,rx:6px,ry:6px;
    classDef leaf fill:#ffffff,stroke:#cbd5e1,stroke-width:1px,color:#334155,rx:4px,ry:4px;

    CS["🎨 Cover Studio<br/>Universal Cover Workflow"]:::rootBox

    CS --> S1["🌐 Cross-Platform Universal"]:::cat1
    S1 --> E1["punk-cover<br/><i>Cyber Geek · Multi-Ratio Adaptive</i>"]:::leaf
    S1 --> E2["huashu-skills<br/><i>Enterprise Launch · AI+HTML</i>"]:::leaf
    S1 --> E3["rn-cover-skill<br/><i>5:2 Editorial Infographic · Seriousness</i>"]:::leaf

    CS --> S2["📕 Xiaohongshu 3:4 Viral"]:::cat2
    S2 --> E4["atutun-xhs-cover<br/><i>Presenter · Neon Bold · Emoji</i>"]:::leaf
    S2 --> E5["gbro-cover-design<br/><i>Clean Flat · UI Cards · 10 Layouts</i>"]:::leaf
    S2 --> E6["ponyo-cover-anchor-system<br/><i>Visual Anchor · Hooks · Collage</i>"]:::leaf

    CS --> S3["🟢 WeChat 2.35:1 Brand"]:::cat3
    S3 --> E7["knowledge-media-cover<br/><i>Ivory Paper · 1:1 Safe Zone</i>"]:::leaf
    S3 --> E8["wechatcover<br/><i>Art Direction Typography · Brand VI</i>"]:::leaf

    CS --> S4["🎬 Video & Tutorial Stream"]:::cat4
    S4 --> E9["oil-cover<br/><i>Apple Minimal · Mac Window · Keyframe</i>"]:::leaf
```

| Stream | Engine Name | GitHub Repo | Visual Characteristics | Best Suited For |
|:---|:---|:---|:---|:---|
| **🌐 Cross-Platform** | `punk-cover` | [adrianpunk/Punk-Skill](https://github.com/adrianpunk/Punk-Skill) | Cyberpunk / Modern Tech / Virtual Avatars | 3:4, 2.35:1, 16:9, 5:2 multi-ratio adaptive |
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
