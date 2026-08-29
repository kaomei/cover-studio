<div align="center">

[简体中文](README.md) · [English](README.en.md) · [**日本語**](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md)

# 🎨 Cover Studio (万能カバー画像スタジオ)

### 全プラットフォーム対応・バズるカバー画像制作ワークフロー · 9大トップオープンソースエンジンを統合

クリエイター、個人開発者、テックブロガーのためのオープンソース AI Skill。記事やナレーション原稿を入力するだけで、**最適な3種類のデザイン案を同時提案**。独自のブランドシステム（Brand System）固定化機能に加え、**Codex 環境での直接画像生成**と **Nano Banana (Google Flow 無料プラットフォーム) 向けプロンプト出力**のデュアルパスに対応しています。

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111827?style=flat-square)
![9大オープンソースエンジン](https://img.shields.io/badge/統合エンジン-9大オープンソースSkill-0066ff?style=flat-square)
![マルチアスペクト比](https://img.shields.io/badge/対応サイズ-3%3A4%20%7C%202.35%3A1%20%7C%2016%3A9-f59e0b?style=flat-square)
![画像生成対応](https://img.shields.io/badge/生成方式-Codex直出%20%7C%20Nano%20Banana無料-8b5cf6?style=flat-square)
![MIT License](https://img.shields.io/badge/License-MIT-16a34a?style=flat-square)

<br/>

適用シーン：**RED (小红书) 縦型画像、WeChat 公式アカウントヘッダー、X/Twitter 記事カバー、YouTube/Bilibili サムネイル、GitHub Social Preview**。

</div>

---

## ✨ 主な特徴

- 🧠 **3パターン同時提案**：記事内容を自動分析し、異なる3つの高品質デザイン構図を同時に提案。
- 🏷️ **ワンクリック・ブランドシステム固定**：気に入ったスタイルをブランド標準として保存し、今後のカバー画像の統一感を維持。
- 📐 **3大黄金ルールに基づく再レイアウト**：画幅（3:4 / 2.35:1 / 16:9）に応じた構図の再設計。
- 🚀 **Codex 直出 ＋ Google Flow (Nano Banana) 無料生成のデュアルパス対応**。
- 🔄 **9大オープンソースカバーエンジン統合**：コミュニティで実績のある9つの Skill を一元ルーティング。

---

## 📚 4大流派 · 9大オープンソースエンジン

| 流派 | エンジン名 | GitHub リンク | ビジュアル特徴 | 適用シーン |
|:---|:---|:---|:---|:---|
| **🌐 クロスプラットフォーム** | `punk-cover` | [adrianpunk/Punk-Skill](https://github.com/adrianpunk/Punk-Skill) | サイバーギーク / 現代テック風 | 3:4、2.35:1、5:2 に自適応 |
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
