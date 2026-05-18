# FREQ. Coffee — Brand Landing Page

> 调到你这一频。 / Tune in to your frequency.

A bilingual (中文 / English) brand landing page for **FREQ. Coffee**, a fictional retro-future coffee brand built around the metaphor of radio frequencies — light roast = high frequency, dark roast = low frequency, drip packs = portable band, cold brew = night channel.

## Live Site

🌐 **https://xiaoyikun.github.io/freq-coffee-landing/**

## Design System

- **Aesthetic**: Warp (terminal retro-future) × Wired (editorial big-type) — 85% / 15%
- **Type Stack**: Unbounded · Space Grotesk · JetBrains Mono · Noto Sans SC
- **Color Palette**: Ink Indigo `#1B1646` (50–60%) · Cream `#F2E8D5` (25–35%) · Signal Green `#5BFF8F` (≤8%)
- **All borders**: `radius: 0` (precision-first)
- **Quality Score**: 23 / 25 (5-dim review) · 8 / 8 Anti-Slop guardrails passed

## Page Structure

1. **HERO** — Big-type poster with `FREQ.` wordmark + 24-column dial strip
2. **THE DAILY DOSE** — 6 signature drinks (HIGH FREQ. ESPRESSO / MID-WAVE LATTE / LOW-BAND DRIP / STATIC COLD BREW / AM CHANNEL FLAT WHITE / NIGHT MODE MOCHA)
3. **TAKE IT HOME** — 4 retail products (drip / cold brew / beans / cassette merch) with photographic packaging
4. **THE FIX** — Brand manifesto with independent ZH/EN switcher + 3 stats
5. **OUR SPOTS** — 4 stores across Shanghai / Shenzhen / Hangzhou / Chengdu, each with its own FM frequency ID
6. **STAY TUNED** — Newsletter signup + social links + footer

## Tech

- Single-file HTML (~65 KB), all CSS / JS inlined
- 4 product photos in `./images/` (~6.6 MB total)
- Fonts loaded via Google Fonts CDN
- Full responsive (mobile / tablet / desktop)
- `prefers-reduced-motion` honored
- Semantic HTML + ARIA + focus-visible
- Bilingual toggle via `data-lang` attribute + class-based show/hide

## Local Preview

Just open `index.html` in any modern browser — no build step required.

---

Built with the **Design Engine** orchestration team:
画统筹 (Hua, Design Orchestrator) · 许明需 (Discovery Analyst) · 彩格调 (Design System Expert) · 筑原型 (Prototype Builder) · 严过审 (Critique Reviewer)
