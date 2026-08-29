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

## 💡 なぜ「万能カバー画像 Skill」を作ったのか？

クリエイター、個人開発者、テックブロガーなら、誰もが一度は経験したことのある**「カバー画像制作の苦悩」**：

1. **🤯 ツールの選択疲れと迷い**：GitHub には素晴らしいカバー画像スキル（サイバー風、小紅書風、WeChat風、大企業風など）が多数存在しますが、毎回どのツールを使うべきか迷い、何度も試行錯誤する時間が無駄になっていました。
2. **📐 複数プラットフォーム配信の「画幅地獄」**：1本の記事を小紅書（3:4 縦型）、WeChat（2.35:1 超ワイド）、X/Twitter（16:9 / 5:2）、YouTube（16:9）に展開する際、1枚の画像を無理やりトリミングすると文字が切れたり構図が崩れてしまいます。
3. **✍️ 文字の乱れと情報階層の崩壊**：画像生成AIで文字が崩れたり、大見出しのフックが弱かったり、サブタイトルやタグが抜けてしまう問題。
4. **🎨 ブランド統一感の欠如**：投稿ごとにデザインがバラバラで、読者に自分のブランドを覚えてもらえない。

### 🎯 解決策：車輪の再発明ではなく、最高の一元ルーティングを！
> **10個の個別スキルを使い分ける手間をなくし、コンテンツ・画幅・ブランドを熟知した「万能カバー画像コマンダー」を構築しました！**

- **9大トップオープンソースエンジンを統合**：記事内容に応じた3つの異なる流派のデザインを直接提示。
- **文字階層の先行確認**：大見出し・副見出し・タグを確定させてから生成することで失敗を防止。
- **自選マルチサイズの一括出力**：お気に入りのスタイルを選べば、選択した各プラットフォーム向けに構図を最適化して一括生成。
- **ブランドVIのワンクリック固定**：選んだスタイルを記憶させ、継続的なブランド認知を確立。

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
    classDef default fill:#ffffff,stroke:#e2e8f0,stroke-width:1.5px,color:#1e293b,rx:8px,ry:8px;
    classDef startNode fill:#0f172a,stroke:#0f172a,stroke-width:2px,color:#ffffff,font-weight:bold,rx:20px,ry:20px;
    classDef stepNode fill:#ffffff,stroke:#cbd5e1,stroke-width:1.5px,color:#0f172a,rx:8px,ry:8px;
    classDef highlightNode fill:#eff6ff,stroke:#2563eb,stroke-width:2px,color:#1e40af,font-weight:bold,rx:8px,ry:8px;

    A0(["🚀 万能カバー画像 Skill 起動"]):::startNode
    --> A1["<b>0. 初期設定 (初回のみ確認)</b><br/>出力モード選択：ブランド統一マルチサイズ (希望サイズを選択) または 単一サイズ"]:::stepNode
    --> A2["<b>1. 記事入力 ➔ 文字階層の先行確認</b><br/>📌 大見出し (≤8文字) ＋ 📝 副見出し価値 ＋ 🏷️ カプセルタグ"]:::highlightNode
    --> A3["<b>2. 3スタイル直接生成</b><br/>【サイバーギーク】·【大見出しバズ】·【深度コラム】の3案を直接提示"]:::stepNode
    --> A4["<b>3. 選択 ➔ 自選サイズ一括納品</b><br/>Codex 直接生成 または Google Flow (Nano Banana) 無料出図"]:::stepNode
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
| **🟢 横长 2.35:1** | `wechatcover` | [naplesblue/wechatcover](https://github.com/naplesblue/wechatcover) | アートディレクション級文字組 | 企業ニュースレター、ブランド統一 |
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

## ⚠️ 免責事項

1. **オープンソース統合について**：本プロジェクトはカバー画像デザインのルーティングスキルであり、統合されている9つのスキルの知的財産権は各原著作者に帰属します。
2. **非公式プロジェクト**：各ソーシャルメディアプラットフォームおよび Google との公式な提携関係はありません。
3. **利用範囲**：個人の学習、研究、適法なコンテンツ制作にご利用ください。

---

## 🤝 コントリビューション

PR や Issue での新しいエンジン推薦やプロンプトレシピの共有を歓迎します！

このプロジェクトがお役に立ちましたら、**ぜひ Star ⭐️ をつけて kaomei（烤妹儿）を応援してください！**

## 📄 ライセンス

[MIT License](LICENSE) © 2026 [kaomei](https://github.com/kaomei)
