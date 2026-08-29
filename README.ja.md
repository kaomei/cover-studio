<div align="center">

[简体中文](README.md) · [English](README.en.md) · [**日本語**](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md)

# 🎨 万能カバー画像 Skill (Cover Studio)

### 全プラットフォーム対応・バズるカバー画像制作ワークフロー · 9大トップオープンソースエンジンを統合

クリエイター、個人開発者、テックブロガーのためのオープンソース AI Skill。初期設定で**明確に区分されたサイズ組み合わせを自由に選択**し、記事入力時に**大見出し・副見出し・タグ要素の文字階層をまず確認**。その文字を基に**3種類の異なるデザイン画像を直接生成・提示**します。ブランドシステム固定化機能に加え、**Codex 環境直接生成**と **Nano Banana (Google Flow 無料) プロンプト出力**に対応。

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111827?style=flat-square)
![9大オープンソースエンジン](https://img.shields.io/badge/統合エンジン-9大オープンソースSkill-0066ff?style=flat-square)
![個別指定サイズ](https://img.shields.io/badge/自選サイズ-3%3A4%20%7C%202.35%3A1%20%7C%2016%3A9%20%7C%205%3A2-f59e0b?style=flat-square)
![画像生成対応](https://img.shields.io/badge/生成方式-Codex直出%20%7C%20Nano%20Banana無料-8b5cf6?style=flat-square)
![MIT License](https://img.shields.io/badge/License-MIT-16a34a?style=flat-square)

<br/>

適用シーン：**RED (小红书) 縦型画像、WeChat 公式アカウントヘッダー、X/Twitter 記事カバー、YouTube/Bilibili サムネイル、GitHub Social Preview**。

</div>

---

## ✨ 主な特徴

- ⚙️ **初回明確なカスタムサイズ選択**：常時一括出力したいプラットフォームサイズ（RED 3:4、WeChat 2.35:1、X ポスト 16:9、X 長文 5:2、動画 16:9、GitHub 2:1、1:1 正方形等）をユーザー自身が個別にチェック設定。
- ✍️ **文字階層の先行確認ステップ**：大見出し、副見出し、タグ要素の文言を画像生成前に必ずユーザーと擦り合わせ。
- 🖼️ **3パターン直接生成**：確認された文字を基に、異なる3つの高品質デザイン画像を直接生成・提示。
- 🏷️ **ワンクリック・ブランドシステム固定**：気に入ったスタイルをブランド標準として保存。
- 📐 **3大黄金ルールに基づく再レイアウト**：画幅に応じた構図の再設計。
- 🚀 **Codex 直出 ＋ Google Flow (Nano Banana) 無料生成のデュアルパス対応**。
- 🔄 **9大オープンソースカバーエンジン統合**。

---

## 🛠️ 標準ワークフロー全行程

```mermaid
flowchart TD
    classDef setupBox fill:#f0f7ff,stroke:#0284c7,stroke-width:2px,color:#0f172a,rx:10px,ry:10px;
    classDef textBox fill:#ecfdf5,stroke:#059669,stroke-width:2px,color:#064e3b,rx:10px,ry:10px;
    classDef genBox fill:#fffbeb,stroke:#d97706,stroke-width:2px,color:#78350f,rx:10px,ry:10px;
    classDef deliverBox fill:#faf5ff,stroke:#9333ea,stroke-width:2px,color:#581c87,rx:10px,ry:10px;
    classDef decision fill:#fff1f2,stroke:#e11d48,stroke-width:2px,color:#881337,rx:6px,ry:6px;
    classDef action fill:#1e293b,stroke:#0f172a,stroke-width:2px,color:#ffffff,font-weight:bold,rx:20px,ry:20px;

    subgraph S0 ["⚙️ フェーズ 0 · 初期設定 (初回のみ)"]
        A0(["🚀 万能カバー画像 Skill 起動"]):::action
        A1{"出力モード確認"}:::decision
        A2["🌟 <b>ブランド統一マルチサイズ一括出力</b><br/>━━━━━━━━━━━━━━━━━━━━━<br/>出力したい独立サイズをチェック：<br/>• 📕 RED 3:4<br/>• 🟢 WeChat 2.35:1<br/>• 🐦 X ポスト 16:9 / 📰 X 長文 5:2<br/>• 🎬 動画 16:9 / 💻 GitHub 2:1 / 🔲 1:1"]:::setupBox
        A3["🎯 <b>単一サイズ個別カスタム</b><br/>毎回単一サイズを個別カスタム"]:::setupBox
        A0 --> A1
        A1 -->|"一括モード"| A2
        A1 -->|"単一モード"| A3
    end

    subgraph S1 ["📝 フェーズ 1 · 記事入力と文字階層確認"]
        B0["📋 記事・原稿・タイトルを入力"]:::action
        B1["✍️ <b>3大文字階層を自動抽出して確認</b><br/>━━━━━━━━━━━━━━━━━━━━━<br/>1️⃣ 📌 <b>大見出しフック</b> (≤6-8文字)<br/>2️⃣ 📝 <b>副見出し価値説明</b> (10-15文字)<br/>3️⃣ 🏷️ <b>補足タグ・バッジ</b>：カプセルタグ / 箇条書き"]:::textBox
        B0 --> B1
    end

    subgraph S2 ["🎨 フェーズ 2 · 3スタイル直接生成"]
        C0["✅ 文字設定を確認"]:::action
        C1["🖼️ <b>確認された文字で3つのスタイル画像を直接生成</b><br/>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━<br/>• <b>スタイル A · サイバーギーク</b> (punk-cover)<br/>• <b>スタイル B · バズる大見出し</b> (atutun-xhs / ponyo)<br/>• <b>スタイル C · 深度コラム</b> (knowledge-media)"]:::genBox
        C0 --> C1
    end

    subgraph S3 ["🚀 フェーズ 3 · 選択＆最終納品"]
        D0{"ユーザーが好みのスタイルを選択 (A / B / C)"}:::decision
        D1["📦 <b>チェックした全サイズを一括出力</b><br/>(3:4 + 2.35:1 + 16:9 等)"]:::deliverBox
        D2["🖼️ <b>指定サイズを出力</b>"]:::deliverBox
        D3["💻 <b>Codex直接生成 または Google Flow無料ガイド</b>"]:::action

        D0 -->|"マルチサイズモード"| D1
        D0 -->|"単一サイズモード"| D2
        D1 ==> D3
        D2 ==> D3
    end

    A2 ==> B0
    A3 ==> B0
    B1 ==> C0
    C1 ==> D0
```

---

## 📚 4大流派 · 9大オープンソースエンジン

```mermaid
flowchart LR
    classDef rootBox fill:#0f172a,stroke:#38bdf8,stroke-width:2px,color:#ffffff,font-weight:bold,rx:8px,ry:8px;
    classDef cat1 fill:#eff6ff,stroke:#2563eb,stroke-width:2px,color:#1e3a8a,font-weight:bold,rx:6px,ry:6px;
    classDef cat2 fill:#fff1f2,stroke:#e11d48,stroke-width:2px,color:#881337,font-weight:bold,rx:6px,ry:6px;
    classDef cat3 fill:#ecfdf5,stroke:#059669,stroke-width:2px,color:#064e3b,font-weight:bold,rx:6px,ry:6px;
    classDef cat4 fill:#faf5ff,stroke:#9333ea,stroke-width:2px,color:#581c87,font-weight:bold,rx:6px,ry:6px;
    classDef leaf fill:#ffffff,stroke:#cbd5e1,stroke-width:1px,color:#334155,rx:4px,ry:4px;

    CS["🎨 Cover Studio<br/>万能カバー画像工作室"]:::rootBox

    CS --> S1["🌐 クロスプラットフォーム全能流"]:::cat1
    S1 --> E1["punk-cover<br/><i>サイバーギーク · 多サイズ自適応</i>"]:::leaf
    S1 --> E2["huashu-skills<br/><i>大企業発表会 · AI+HTML</i>"]:::leaf
    S1 --> E3["rn-cover-skill<br/><i>5:2 エディトリアル図解 · 厳格</i>"]:::leaf

    CS --> S2["📕 小紅書 3:4 縦型バズ流"]:::cat2
    S2 --> E4["atutun-xhs-cover<br/><i>人物登場 · 蛍光大見出し · Emoji</i>"]:::leaf
    S2 --> E5["gbro-cover-design<br/><i>フラット単色 · UIカード · 10構図</i>"]:::leaf
    S2 --> E6["ponyo-cover-anchor-system<br/><i>視覚アンカー · 痛点 · コラージュ</i>"]:::leaf

    CS --> S3["🟢 WeChat 2.35:1 専門流"]:::cat3
    S3 --> E7["knowledge-media-cover<br/><i>アイボリー紙 · 1:1 安全区</i>"]:::leaf
    S3 --> E8["wechatcover<br/><i>アートディレクション文字組</i>"]:::leaf

    CS --> S4["🎬 動画・実演ツール流"]:::cat4
    S4 --> E9["oil-cover<br/><i>Apple極簡 · Macウィンドウ · 録画</i>"]:::leaf
```

| 流派 | エンジン名 | GitHub リンク | ビジュアル特徴 | 適用シーン |
|:---|:---|:---|:---|:---|
| **🌐 クロスプラットフォーム** | `punk-cover` | [adrianpunk/Punk-Skill](https://github.com/adrianpunk/Punk-Skill) | サイバーギーク / 現代テック風 | 3:4、2.35:1、16:9、5:2 に自適応 |
| **🌐 クロスプラットフォーム** | `huashu-skills` | [alchaincyf/huashu-skills](https://github.com/alchaincyf/huashu-skills) | 大企業発表会 / インダストリアル | AI 生成 ＋ HTML ベクター描画 |
| **🌐 クロスプラットフォーム** | `rn-cover-skill` | [Pluviobyte/rnskill](https://github.com/Pluviobyte/rnskill) | 5:2 エディトリアル図解風 | 専門的な技術解説、調査レポート |
| **📕 縦型 3:4** | `atutun-xhs-cover` | [panggungunvibe/atutun-xhs-cover](https://github.com/panggungunvibe/atutun-xhs-cover) | 人物登場 / 蛍光大見出し / 絵文字 | 個人IP育成、実践ノウハウ共有 |
| **📕 縦型 3:4** | `gbro-cover-design` | [pyang5166/gbro-cover-design](https://github.com/pyang5166/gbro-cover-design) | フラット単色 / UI カード構図 | ツールレビュー、ソフトウェア解説 |
| **📕 縦型 3:4** | `ponyo-cover-anchor-system` | [ponyodong2026/ponyo-cover-anchor-system](https://github.com/ponyodong2026/ponyo-cover-anchor-system) | 感情フック / コラージュ風 | コラム、高クリック率フック |
| **🟢 横長 2.35:1** | `knowledge-media-cover` | [aa1143/knowledge-media-cover](https://github.com/aa1143/knowledge-media-cover) | アイボリー紙テクスチャ / 抽象概念 | 深度コラム（1:1 正方形クロップ対応） |
| **🟢 横長 2.35:1** | `wechatcover` | [naplesblue/wechatcover](https://github.com/naplesblue/wechatcover) | アートディレクション級文字組 | 企業ニュースレター、ブランド統一 |
| **🎬 動画・実演** | `oil-cover` | [oil-oil/oil-cover](https://github.com/oil-oil/oil-cover) | Apple風ミニマル / Macウィンドウ | プログラミング実演、AI ツール動画 |

---

## 📦 インストール方法

```bash
git clone https://github.com/kaomei/cover-studio.git
cd cover-studio

# Codex CLI
cp -R skills/cover-studio "${CODEX_HOME:-$HOME/.codex}/skills/cover-studio"

# Antigravity / Gemini CLI
cp -R skills/cover-studio ~/.gemini/config/skills/cover_studio
```

---

## ⚠️ 免責事項 (Disclaimer)

1. **オープンソース統合について**：本プロジェクトはカバー画像デザインのルーティングスキルであり、統合されている9つのスキルの知的財産権は各原著作者に帰属します。
2. **非公式プロジェクト**：各ソーシャルメディアプラットフォームおよび Google との公式な提携関係はありません。
3. **利用範囲**：個人の学習、研究、適法なコンテンツ制作にご利用ください。

---

## 🤝 コントリビューション

PR や Issue での新しいエンジン推薦やプロンプトレシピの共有を歓迎します！

このプロジェクトがお役に立ちましたら、**ぜひ Star ⭐️ をつけて kaomei（烤妹儿）を応援してください！**

## 📄 ライセンス

[MIT License](LICENSE) © 2026 [kaomei](https://github.com/kaomei)
