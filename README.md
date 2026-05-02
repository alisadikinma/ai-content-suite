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
claude plugins install pitch-deck-designer
```

Or via **Manage Plugins UI** → **Marketplaces** tab → paste `alisadikinma/ai-content-suite` → **Add**, then install from **Plugins** tab.

## Plugins

| Plugin | Description |
|--------|-------------|
| [ai-image-carousel-prompt-gen](https://github.com/alisadikinma/ai-image-carousel-prompt-gen) | Cinematic carousel image prompt production (Instagram, TikTok, LinkedIn, Threads) |
| [ai-video-promo-engine](https://github.com/alisadikinma/ai-video-promo-engine) | End-to-end AI video promo production: brainstorm → script → image prompts (NB2) → video prompts (VEO 3.1) |
| [article-content-writer](https://github.com/alisadikinma/article-content-writer) | AI-powered long-form article writing with copywriting frameworks, viral hooks, image prompts, and dual scoring gates |
| [linkedin-post-writer](https://github.com/alisadikinma/linkedin-post-writer) | Blog → native LinkedIn post (text or 7-10 slide carousel) with Depth Score validator, 12 hook formulas, and 20-rule anti-slop rubric |
| [pitch-deck-designer](https://github.com/alisadikinma/pitch-deck-designer) | Visual-first investor / B2B pitch deck designer — 4-stage pipeline (brief → storyline → gen → validate). Dual-mode adaptive (VC fundraise / B2B channel-partner adoption). Outputs per-slide image prompts (GeminiGen.AI), Seedance 2.0 video prompts, optional Remotion configs, Indonesian-aware speaker notes. 100-point quality gate (Visual Ratio + Narrative Arc + Ask Clarity + Investor Psychology + Anti-AI-Slop). |

## License

MIT
