# Twisted Hearts (2024), Marketing Blueprint by Brazil Singh

> A confidential marketing dossier for [**Twisted Hearts (2024)**](https://www.imdb.com/title/tt30970776/), presenting the [quiz](https://game.cueandcodafilms.com/)-to-[Prime](https://www.amazon.com/gp/video/detail/0Q20ICPYLH1EMO3A11DO6YUEHJ) funnel strategy for [Cue & Coda Films](https://cueandcodafilms.com/).

![Status](https://img.shields.io/badge/status-launch%20ready-8E1F30)
![Built with](https://img.shields.io/badge/built%20with-HTML%20%7C%20CSS%20%7C%20JS-C9A24B)
![Deploy](https://img.shields.io/badge/hosted%20on-GitHub%20Pages-181717)
![Dependencies](https://img.shields.io/badge/dependencies-none-success)

**🔗 Live page:** https://brazilsingh.github.io/twisted-hearts-blueprint/
<!-- Replace with your custom domain if you set one, e.g. https://blueprint.cueandcodafilms.com -->

---

## About

This repository hosts a single-page, self-contained web document outlining the marketing strategy behind the **Twisted Hearts** relationship quiz and its $2.99 Amazon Prime rental funnel.

The core thesis: at a $2.99 price point you can't profitably *buy* customers, so the strategy treats the **email/SMS lead, not the rental - as the asset**. A shareable "relationship sin" quiz feeds an owned audience, which is nurtured to convert on impulse and kept for every future Cue & Coda release.

## What's inside

The blueprint covers, in order:

1. **Strategy in one line** - sell the rental, keep the audience
2. **The flywheel** - why this is a loop, not a funnel
3. **Six funnel stages** - Attract → Capture → Nurture → Convert → Amplify → Retain
4. **Channels & budget logic** - organic first, paid as retargeting only
5. **The content engine** - seven sins mapped to seven content pillars
6. **Measurement** - the Amazon attribution gap and how to work around it
7. **The first 30 days** - a week-by-week launch plan
8. **Priority fixes** - live conversion leaks to patch immediately

## Design

The page is themed as a **"confession dossier,"** taking its cue from the quiz's own line - *"This is not a cute relationship quiz. This is a mirror."*

- **Palette** - candlelit wine-black with oxblood (`#8E1F30`) and brass-gold (`#C9A24B`) accents
- **Typography** - `Fraunces` (display serif) · `Instrument Sans` (body) · `Space Mono` (labels & data)
- **Signature element** - the seven sins rendered as numbered confession cards (I–VII)
- Responsive to mobile, keyboard-accessible focus states, and `prefers-reduced-motion` respected

## Tech stack

No frameworks, no build step, no dependencies - a single HTML file with inline CSS and vanilla JavaScript (one `IntersectionObserver` for scroll reveals). Fonts load from Google Fonts.

## Project structure

```
.
├── index.html      # The complete blueprint (markup, styles, and script inline)
└── README.md       # This file
```

## Deployment (GitHub Pages)

No terminal required:

1. Create a public repository and upload `index.html` via **Add file → Upload files**.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch** → branch `main` → folder `/ (root)` → **Save**.
4. The page goes live at `https://<username>.github.io/<repo>/` within a minute or two.

## Local preview

Open `index.html` directly in any browser - no server needed.

## Customising

- **Byline / client name** - edit the header `.mark` block and the `<footer>` in `index.html`.
- **Colours** - all defined as CSS custom properties in the `:root` block at the top of the `<style>` tag.
- **Share preview** - update the `og:title` / `og:description` meta tags to control how the link previews when shared.

## Credits

Strategy, design, and build by [**Brazil Singh**](https://www.linkedin.com/in/brazil-singh-rittik/)
Prepared for **Cue & Coda Films** · *Twisted Hearts* (2024)

## License

© 2026 [**Brazil Singh**](https://www.linkedin.com/in/brazil-singh-rittik/). Prepared for Cue & Coda Films. All rights reserved.
This document contains proprietary marketing strategy and is not licensed for redistribution.
