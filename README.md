# Adequately Engineered by Venky — Catalogue

### *The Boringly Functional Project Index*

A static GitHub Pages catalogue for the **Adequately Engineered by Venky** series — because the problems were real, the tools work, and they deserved a page that isn't just a list of GitHub links.

---

**Part of the *Adequately Engineered by Venky* Series**
> *Real problem. Boring stack. Thing actually works. No LLMs doing arithmetic. No Kubernetes for a side project. No blockchain anywhere. Every project in this series exists because "I was personally annoyed by this problem and decided to fix it properly." Style points? Optional. Working in production? Mandatory.*

---

![Status](https://img.shields.io/badge/Status-3_Shipped-brightgreen?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-GitHub_Pages-black?style=for-the-badge&logo=github)
![Stack](https://img.shields.io/badge/Stack-Vanilla_HTML%2FCSS-blue?style=for-the-badge)
![Build Step](https://img.shields.io/badge/Build_Step-None-gray?style=for-the-badge)

---

## What Is This

A single `adequately-engineered.html` catalogue page that lists the tools in this series. It features:

- **Project cards** for IndITR, JobMemo, and MumbaiDams — with descriptions, tech stacks, key stats, and GitHub links
- **A WIP card** for whatever's being fixed next
- **Dark navy design** — clean, readable, Inter font, sky-blue accent. Works on first open.

Zero frameworks. Zero dependencies. Zero npm install. One file.

---

## Projects

| # | Project | What It Fixes |
|---|---------|--------------|
| 001 | [IndITR](https://github.com/acervenky/adequately-engineered-inditr) | Indian income tax filing (AY 2026-27) — LLM parses, Python calculates, 301 tests make sure it's right |
| 002 | [JobMemo](https://github.com/acervenky/adequately-engineered-jobmemo) | Chrome extension that scores jobs, researches companies, and drafts cover letters — directly on the portal, no backend |
| 003 | [MumbaiDams](https://github.com/acervenky/mumbai-dam-tracker) | All 7 Mumbai reservoirs on one page — storage history, ENSO tracking, IMD cross-validation, 12-month projections. No backend. ([Live](https://acervenky.github.io/mumbai-dam-tracker/)) |
| 004 | Next one | Found another problem. Currently annoyed by it. |

---

## Stack

| Layer | Choice | Why |
|-------|--------|-----|
| Markup | HTML5 | It's a static page. |
| Styling | Vanilla CSS + CSS Variables | No build step. Didn't need one. |
| Fonts | Inter + JetBrains Mono | Loaded from Google Fonts. One `<link>` tag. |
| Animations | CSS transitions | Subtle. Not the point. |
| Hosting | GitHub Pages | Free, zero config, done. |

**Total dependencies: 0** *(two Google Fonts, which barely counts)*

---

## Deploy to GitHub Pages

**Live URL:** `https://acervenky.github.io/adequately-engineered-catalogue`

**1. Create the repo**

Go to [github.com/new](https://github.com/new) and name it:

```
adequately-engineered-catalogue
```

**2. Clone, add files, push**

```bash
git clone https://github.com/acervenky/adequately-engineered-catalogue
cd adequately-engineered-catalogue
# Add adequately-engineered.html as index.html and this README
git add index.html README.md
git commit -m "feat: launch AE catalogue"
git push origin main
```

**3. Enable GitHub Pages**

Repo → **Settings** → **Pages** → Source: `main` branch, `/ (root)` → Save.

**4. Done.** Wait ~60 seconds. Visit the URL.

---

## File Structure

```
adequately-engineered-catalogue/
└── index.html      # The entire catalogue. One file. Works.
└── README.md       # This.
```

No `node_modules`. No `package.json`. No build pipeline.

---

## Updating the Page

**Adding a new project card** — find the `<!-- WIP -->` card, replace it with a real card (copy the structure from IndITR or JobMemo), then add a fresh WIP card after it. Update the section label count at the top.

**Updating stats** — they're plain text inside the `.stat-val` elements. Edit directly.

**Retiring the WIP card** — when the next project ships, swap it for a real card. Add a new WIP card. Repeat indefinitely.

---

## Design Notes

Dark navy background (`#08101b`). Inter for everything. JetBrains Mono for numbers and code. Sky blue accent. Clean borders. No scanlines, no CRT effects, no noise texture, no Bebas Neue. The design is not the point. The tools are.

If you want the version where the design *is* the point, see [Over Engineered by Venky](https://github.com/acervenky/over-engineered-catalogue).

---

## License

**CC BY-NC 4.0** — Free for personal and educational use. Commercial use prohibited.

See [creativecommons.org/licenses/by-nc/4.0](http://creativecommons.org/licenses/by-nc/4.0/) for full terms.

---

**Adequately Engineered by Venky**

*Style points: optional. Working in production: mandatory.*
