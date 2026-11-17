# hanselius.dev

Hansel Saldanha's personal website — a simple, employer-first page about his
work, with real room for the rest of his life (choir, cooking, swimming,
reading).

**Live:** https://hanspres1999.github.io/hanselius.dev/
("hanselius.dev" is the working name; a custom domain comes later.)

## What's on the page

One page, five sections: **Intro**, **Work** (AWS, George Mason research, and
the featured project *Jam Clean* with its TestFlight beta link), **About**,
**Life**, and **Contact**.

Facts that haven't been confirmed yet appear as dashed yellow **todo** tags
instead of made-up text. The content rules and the source of every fact are in
[`docs/website-brief.md`](docs/website-brief.md) — read that before editing
copy.

## Running it locally

No build step, no install. Double-click `index.html`, or:

```sh
cd "/Users/hansel/Hansel Website"
python3 -m http.server 8000
# then open http://localhost:8000
```

## How it's built (and why)

- **One plain `index.html`, no frameworks, no JavaScript.** A personal page
  doesn't need React or a bundler, and a single file means nothing can break
  between "edit" and "reload".
- **Colors and fonts are defined once** as CSS variables at the top of the
  `<style>` block (`--bg`, `--ink`, `--accent`, …), so restyling is a
  few-line change. Fonts come from Google Fonts.
- **Layout:** a readable centre column. On wide screens, the side margins hold
  reserved slots for future side elements (the brief's visual reference is
  jackiezhang.co.za); on phones they disappear and the page is one column.
- **Accessibility basics:** a "skip to content" link, visible keyboard focus,
  and smooth scrolling turned off for people who prefer reduced motion.

## Publishing

GitHub Pages serves the `main` branch. Anything merged or pushed to `main` is
live within a minute or two. Hosting is free; the only planned cost is a
custom domain (~US$12/year).

## Repo map

| Path | What it is |
|---|---|
| `index.html` | The live site |
| `docs/website-brief.md` | The content brief: confirmed facts vs. proposals |
| `WORKLOG.md` | Dated log of every change, plus the prioritized to-do list |
| `archive/overture/` | Retired concept: 3D orchestra with a synthesized Ode to Joy |
| `archive/gate/` | Retired concept: Apollo / Bacchus two-door gate |
| `archive/study/` | Retired concept: a Seattle study with two tabbed books |

The archived pages still work and are linked from the site's footer.

## Roadmap

The bigger plan — analytics, a free backend, a mobile dashboard app, and a
wedding site for 2027 — lives in the "Hanselius Master Plan" doc. The
short-term priority list is at the bottom of `WORKLOG.md`.
