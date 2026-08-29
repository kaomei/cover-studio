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
    subgraph S0["⚙️ 初期設定 (初回のみ)"]
        A0["万能カバー画像 Skill 起動"] --> A1{"出力モード確認"}
        A1 -->|"マルチサイズモード"| A2["出力したい独立サイズをチェック:<br/>3:4 / 2.35:1 / X 16:9 / X長文 5:2 / 動画 16:9 / GitHub 2:1 / 1:1"]
        A1 -->|"単一サイズモード"| A3["毎回単一サイズを個別カスタム"]
    end

    subgraph S1["📝 フェーズ1: 記事入力と文字階層確認"]
        B0["記事・原稿を入力"] --> B1["3大文字階層を自動抽出して確認:<br/>1. 📌 大見出しフック<br/>2. 📝 副見出し価値説明<br/>3. 🏷️ 補足タグ・バッジ"]
    end

    subgraph S2["🎨 フェーズ2: 3スタイル直接生成"]
        C0["ユーザーが文字を確認"] --> C1["確認された文字で3つのスタイル画像を直接生成:<br/>• スタイル A: サイバーギーク (punk-cover)<br/>• スタイル B: バズる大見出し (atutun-xhs / ponyo)<br/>• スタイル C: 深度コラム (knowledge-media)"]
    end

    subgraph S3["🚀 フェーズ3: 選択＆最終納品"]
        D0["ユーザーが好みのスタイルを選択"] --> D1{"フェーズ0の初期設定"}
        D1 -->|"マルチサイズモード"| D2["チェックした全サイズを一括出力:<br/>例: 3:4 + 2.35:1 + 16:9"]
        D1 -->|"単一サイズモード"| D3["指定サイズを出力"]
        D2 --> D4["Codex直接生成 または Google Flow無料ガイド"]
        D3 --> D4
    end

    A2 --> B0
    A3 --> B0
    B1 --> C0
    C1 --> D0
```

---

## 📚 4大流派 · 9大オープンソースエンジン

```mermaid
flowchart LR
    CS["🎨 Cover Studio<br/>万能カバー画像工作室"]
    
    CS --> S1["🌐 クロスプラットフォーム全能流"]
    S1 --> E1["punk-cover (サイバーギーク / 現代テック / 多サイズ自適応)"]
    S1 --> E2["huashu-skills (大企業発表会 / インダストリアル / AI+HTML)"]
    S1 --> E3["rn-cover-skill (5:2 エディトリアル図解風 / 厳格な知識感)"]

    CS --> S2["📕 小紅書 3:4 縦型バズ流"]
    S2 --> E4["atutun-xhs-cover (人物登場 / 蛍光大見出し / 絵文字)"]
    S2 --> E5["gbro-cover-design (フラット単色 / UIカード / 10種構図)"]
    S2 --> E6["ponyo-cover-anchor-system (感情フック / 痛点 / コラージュ)"]

    CS --> S3["🟢 WeChat 2.35:1 専門流"]
    S3 --> E7["knowledge-media-cover (アイボリー紙 / 暗赤タグ / 1:1 安全区)"]
    S3 --> E8["wechatcover (アートディレクション文字組 / 崩れない)"]

    CS --> S4["🎬 動画・実演ツール流"]
    S4 --> E9["oil-cover (Apple極簡 / Macウィンドウ / キーフレーム)"]
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
