# 🏷️ 品牌固化系统配置模板 (Brand System Specification)

当用户选择「固化为品牌标准」时，Cover Studio 会在用户配置或记忆中保存以下规范，确保未来每一次生成的封面都具备高度统一的品牌辨识度（“让读者不看作者名就知道是你”）。

---

## 📋 品牌配置规范模板 (`brand-system.json` / `brand-system.md`)

```json
{
  "brand_name": "疯狂的烤妹儿",
  "default_author_handle": "@CrazyKaomei",
  "primary_style": "cyber-minimalist-doodle",
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
  "default_channels": [
    {
      "platform": "xiaohongshu",
      "ratio": "3:4",
      "engine": "atutun-xhs-cover"
    },
    {
      "platform": "wechat",
      "ratio": "2.35:1",
      "engine": "knowledge-media-cover"
    },
    {
      "platform": "x_twitter",
      "ratio": "16:9",
      "engine": "punk-cover"
    }
  ],
  "safe_zone_rules": {
    "bottom_margin_percent": 15,
    "pass_wechat_1to1_center_crop": true
  }
}
```
