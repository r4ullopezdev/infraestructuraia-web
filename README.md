# Infraestructura IA — Company website

**Digital infrastructure for local economies.**

Infraestructura IA builds **country-level digital directories** that drive local and
international tourism, bundled with **Claude-powered tools** that give informal
businesses and entrepreneurs a professional online presence — with zero technical
skills: profiles, bilingual translation, bookings, quotes and customer replies
generated from plain-language chat.

A new country launches **by configuration, not rebuild** — one multi-agent,
config-driven stack, with Claude as the core model.

## Live directories

| Country / region | Site | Businesses |
|---|---|---|
| 🇵🇦 Panama (ES/EN) | [panamadigitaldirectory.com](https://panamadigitaldirectory.com) | 3,537 |
| 🇪🇸 Spain | [spaindigitaldirectory.com](https://spaindigitaldirectory.com) | 5,423 |
| 🏖️ Coronado · Panama | [coronadodigitaldirectory.com](https://coronadodigitaldirectory.com) | 3,410 |
| 🇦🇩 Andorra | [andorradigitaldirectory.com](https://andorradigitaldirectory.com) | 800 |
| 🇨🇴 Colombia | [colombiadigitaldirectory.com](https://colombiadigitaldirectory.com) | 600+ |
| 🇩🇴 Dominican Republic | *launching* | pilot |

**~13,000+ businesses · 2,000+ bilingual guides · fully ES / EN.**

## This repository

A fast, self-contained static website (`index.html` + `assets/`). No build step.

### Run locally
Open `index.html` in a browser, or serve the folder:
```bash
npx serve .
```

### Deploy
- **Vercel** — import the repo; it serves the static files as-is. Add the domain `infraestructuraia.com` in the project settings.
- **GitHub Pages** — enable Pages on the `main` branch (root). The included `CNAME` points it at `infraestructuraia.com`.

## Built on Claude
Claude is the core model across the stack — generating listings, translations and
local guides at scale, and powering the owner-facing tools (quotes, bookings,
replies), with model routing (Haiku / Sonnet / Opus), prompt caching and batching
to keep cost per business near zero.

---
© 2026 Infraestructura IA
