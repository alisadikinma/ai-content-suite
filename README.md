# AI Content Suite — Claude Code Marketplace

Marketplace for AI content creation plugins.

## Install

```bash
# Step 1: Add marketplace
claude plugins marketplace add alisadikinma/ai-content-suite

# Step 2: Install plugins
claude plugins install ai-video-promo-engine
claude plugins install ai-image-carousel-prompt-gen
claude plugins install article-content-writer
claude plugins install linkedin-post-writer
claude plugins install social-short-form-writer
claude plugins install ai-business-document-designer
```

Or via **Manage Plugins UI** → **Marketplaces** tab → paste `alisadikinma/ai-content-suite` → **Add**, then install from **Plugins** tab.

## Plugins

| Plugin | Description |
|--------|-------------|
| [ai-image-carousel-prompt-gen](https://github.com/alisadikinma/ai-image-carousel-prompt-gen) | Cinematic carousel image prompt production (Instagram, TikTok, LinkedIn, Threads) |
| [ai-video-promo-engine](https://github.com/alisadikinma/ai-video-promo-engine) | End-to-end AI video promo production: brainstorm → script → image prompts (NB2) → video prompts (VEO 3.1) |
| [article-content-writer](https://github.com/alisadikinma/article-content-writer) | AI-powered long-form article writing with copywriting frameworks, viral hooks, image prompts, and dual scoring gates |
| [linkedin-post-writer](https://github.com/alisadikinma/linkedin-post-writer) | Blog → native LinkedIn post (text or 7-10 slide carousel) with Depth Score validator, 12 hook formulas, and 20-rule anti-slop rubric |
| [social-short-form-writer](https://github.com/alisadikinma/social-short-form-writer) | Blog → native Instagram + TikTok captions. `/instagram-gen` (4:5 carousel, 5-hashtag hardcap since Dec 2025, no link in caption) + `/tiktok-gen` (9:16 photo-mode, 5-8 hashtags, first-100-char search-index gate). English authoring, anti-AI-slop. Pairs with linkedin-post-writer + ai-image-carousel-prompt-gen. |
| [ai-business-document-designer](https://github.com/alisadikinma/ai-business-document-designer) | Visual-first AI designer for 9 business document types: VC + B2B pitch decks, brochures, portfolios (personal + agency), product catalogs, service flyers, trifold leaflets. 5-stage pipeline (brief → narrative/layout → copywriting → gen → validate) with 2 human approval gates. 8 framework files + 7 named themes + dual-rubric scoring (deck or print). Print-ready (CMYK + bleed + 300dpi). Indonesian-first. Migrated from pitch-deck-designer 2026-05-21 with merged print-collateral scope. |

## License

MIT
