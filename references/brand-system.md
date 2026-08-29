# 🏷️ 品牌固化系统配置模板 (Brand System Specification)

当用户选择「统一品牌多尺寸分发模式」时，Cover Studio 会在用户配置中保存以下规范，确保未来每一次生成的封面都自动输出用户自主勾选的各项独立尺寸，并具备高度统一的品牌辨识度（“让读者不看作者名就知道是你”）。

---

## 📋 品牌配置规范模板 (`brand-system.json` / `brand-system.md`)

```json
{
  "brand_name": "疯狂的烤妹儿",
  "default_author_handle": "@CrazyKaomei",
  "output_mode": "unified_brand_multi_size",
  "custom_ratio_bundle": [
    {
      "id": "xhs",
      "platform": "xiaohongshu",
      "name": "小红书 / 抖音图文",
      "ratio": "3:4",
      "resolution": "1080x1440",
      "engine": "atutun-xhs-cover",
      "enabled": true
    },
    {
      "id": "wechat",
      "platform": "wechat",
      "name": "微信公众号首图",
      "ratio": "2.35:1",
      "resolution": "2350x1000",
      "engine": "knowledge-media-cover",
      "pass_1to1_center_crop": true,
      "enabled": true
    },
    {
      "id": "x_post",
      "platform": "x_twitter_post",
      "name": "X / Twitter / 即刻推文配图",
      "ratio": "16:9",
      "resolution": "1200x675",
      "engine": "punk-cover",
      "enabled": true
    },
    {
      "id": "x_article",
      "platform": "x_twitter_article",
      "name": "X Article / 专栏长文头图",
      "ratio": "5:2",
      "resolution": "1200x480",
      "engine": "rn-cover-skill",
      "enabled": false
    },
    {
      "id": "video",
      "platform": "video_cover",
      "name": "B站 / YouTube 视频封面",
      "ratio": "16:9",
      "resolution": "1920x1080",
      "engine": "oil-cover",
      "enabled": false
    },
    {
      "id": "github",
      "platform": "github",
      "name": "GitHub Social Preview / 博客头图",
      "ratio": "2:1",
      "resolution": "1280x640",
      "enabled": false
    },
    {
      "id": "square",
      "platform": "square_post",
      "name": "通用方形配图 / 朋友圈 / 头像",
      "ratio": "1:1",
      "resolution": "1080x1080",
      "enabled": false
    }
  ],
  "palette": {
    "background": "#F8F6EF",
    "primary_accent": "#0066FF",
    "secondary_accent": "#F59E0B",
    "neutral_dark": "#111827"
  },
  "typography": {
    "title_style": "bold-clean-sans",
    "hook_highlight": "yellow-pill-badge"
  },
  "safe_zone_rules": {
    "bottom_margin_percent": 15,
    "pass_wechat_1to1_center_crop": true
  }
}
```
