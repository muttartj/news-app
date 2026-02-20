<!-- README.md -->
# NEON NEWS 99 (GitHub Pages)

A static, single-file “news dashboard” that shows **interesting headlines + concise summaries + quick takeaways** based on your interests — with a **90s retro UI**.

It fetches **RSS/Atom feeds** (including **Google News RSS search feeds**) and ranks items by:
- recency
- keyword matches
- a small “high-signal term” boost (IPO, launch, transfer, trade, draft, etc.)

No build step. No paid API keys required.

---

## What’s Included

### Sections
- **⚽ Soccer / Football** (Premier League + Manchester United)
- **🏙️ Seattle Sports** (Sounders + Mariners + Seahawks)
- **🚆 Rail + Transport Tech**
- **🚀 Startups + IPOs**
- **🤖 AI News + Tools** + **Vibe Coding Challenge**

### Features
- Refresh pulls the latest items (feeds are requested with `cache: "no-store"`).
- Search + time window filters.
- Sort by “Most interesting” or “Newest.”
- Control Panel lets you edit categories/keywords/feeds in JSON.
- Config persists via `localStorage`.
- Export / Import config JSON.

---

## Quick Start (Local)

1) Create a folder and add:
- `index.html`
- `README.md`

2) Run a tiny local web server:

```bash
python3 -m http.server 8000
