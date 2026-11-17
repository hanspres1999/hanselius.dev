# WORKLOG — hanselius.dev

## 2026-11-14
- Project started in a Claude Code session. Explored three concepts as live
  prototypes on a Claude artifact (same URL throughout):
  1. Piano-key navigation (7 white keys = 7 life areas, Web Audio notes).
  2. 2D SVG orchestra stage menu (conductor = About me; sections play their own
     synthesized sounds).
  3. **Approved concept:** blurred veil + "Begin the overture" → looping
     synthesized Ode to Joy builds section by section over a low-poly 3D
     orchestra (Three.js), where hovering/clicking sections is the site menu.
- Fixed a bug where the Start button did nothing: the file was missing its
  closing `</script>` tag, so the browser never ran any JavaScript. Lesson:
  always check the browser console (F12) first — script failures are silent.
- Created this repo at `/Users/hansel/Hansel Website`, converted the artifact
  prototype into a standalone `index.html` (added the `<!DOCTYPE>`/`<head>`/
  `<body>` skeleton the artifact host used to provide), wrote README, and synced
  to GitHub as a private repo `hanselius.dev` (flip to public when enabling
  GitHub Pages).

## 2026-11-16
- Hansel reviewed the 3D orchestra concept and retired it. Nothing deleted: the
  whole page moved to `archive/overture/index.html`, stamped (veil + page
  banner) with his requested epitaph: "This would've been my website if my
  creativity had wings like that of a dog." The claude.ai prototype artifact
  shows the same archived version. Root `index.html` is now a small
  intermission page linking to the archive.
- New direction (strategy pending Hansel's approval before any build): a
  dual-intent site. **Mode A "Apollo"** — professional: skills, journey, the
  app and website building. **Mode B "Bacchus"** — creative: writing music,
  choir, cooking, swimming. The two modes are to be operated very distinctly.

## 2026-11-16 (later)
- Hansel approved: merge + go live, analytics, and the Apollo/Bacchus build
  (Apollo first). Repo made **public**. New ideas recorded in the "Hanselius
  Master Plan" doc on claude.ai: free backend server, mobile dashboard app,
  wedding 2027 evite + website, contact pages on both modes, Apollo
  scroll-scene design direction.
- Built **the gate**: root `index.html` is now a split threshold — Apollo half
  (bone/ink/gold, sun emblem) and Bacchus half (wine-dark, grape emblem), each
  a full-bleed door that grows on hover; the visitor's last door is remembered
  (localStorage) but never auto-redirected. Stub pages at `apollo/` and
  `bacchus/` hold the tone until their real builds.
- PR merging is blocked for Claude by harness safety rules, so the archive and
  the gate ride the same PR (#1) — one click from Hansel merges both; GitHub
  Pages gets enabled right after.

## 2026-11-16 (evening)
- The Codex concept went through three acts on the demo artifact: (I) a bare
  3D-flip book with fore-edge tabs; (II) the book on a desk in an evening
  study with scroll-to-approach; (III) a Seattle study — Denny Triangle window
  view (Space Needle, Elliott Bay, Olympics), room palette driven by Seattle's
  real clock with a weather preview toggle, desk objects (mug, fork, goggles,
  headphones, placeholder photo frame, plant), and TWO books, Apollo and
  Bacchus, each opening as its own tabbed codex — choosing a book replaces
  the gate concept.
- Hansel found the 2D look too simplistic; a Three.js 3D rebuild (act IV) was
  scoped and approved, then PAUSED: Hansel is hunting for simple-but-good
  website inspiration first. Act III is archived at `archive/study/`.
- A requested subtitle change (Apollo "My Professional Side" / Bacchus "My
  Passionate Side") was applied and then reverted at Hansel's request — the
  covers already explained the books.

## 2026-11-16 (night) — PIVOT per docs/website-brief.md
- Hansel supplied a brief (saved at docs/website-brief.md — READ IT FIRST next
  session). Direction now: ONE simple employer-first page. Codex/3D shelved.
- Built the draft: root index.html = Intro / Work (AWS + GMU + featured
  project Jam Clean with real TestFlight link) / About / Life (choir, cooking,
  swimming, reading) / Contact. All unknown facts are dashed "todo" chips.
  Side rails hold dashed slots for Hansel's future side-element ideas
  (reference: jackiezhang.co.za). Gate archived to archive/gate/.
- Draft preview artifact: https://claude.ai/artifact/E3266rGY5vkvFaPBS2GvCg
- Master Plan doc: https://claude.ai/artifact/VGyb54MerKWxTDCNiX7Nby

## 2026-11-17
- Hansel merged PR #1 (draft site + all archives) into `main`.
- Claude turned on GitHub Pages (deploy from `main`, root). First deploy
  succeeded; checked the live homepage (title "Hansel Saldanha") and
  `/archive/overture/` both return 200.
  **Live: https://hanspres1999.github.io/hanselius.dev/**
- README rewritten for the current site (it still described the orchestra);
  this WORKLOG's to-do lists merged into one priority list below.
- Workflow note: Hansel wants plain commits on `main`, not PRs. This
  background session can only commit to a side branch, so changes reach `main`
  via a one-line merge Hansel runs. Adding
  `{"worktree":{"bgIsolation":"none"}}` to `.claude/settings.json` lets
  future sessions commit to `main` directly.
- Added a visible "Work in progress" notice at the top of the site (17 Nov).

## 2026-11-17 — release v1126.17
- Versioning starts: the footer shows `vMMYY.DD` (date of the push), updated
  with every push, at most one version per day (Hansel's rule, until he says
  otherwise).
- Seattle scenery behind the page: scroll position runs the time of day from
  dawn (top) to night (bottom) — sun arc and sunset into Elliott Bay, moonrise
  in the right margin, stars, lit windows, the Space Needle beacon. Text sits
  on frosted cards that switch to dark glass after sunset.
- The reading column is split into cards with three open gaps showing the
  scene (gaps then shortened by 35%).
- Living scene: birds about every 30 s, a helicopter every 1–2 min, constant
  waves, an orca breaching every 40–80 s; about a third of flights pass in
  front of the page for depth.
- Weather: a 90 s cycle, with 30 s of rain under heavy moving cloud and 60 s
  dry. The page opens mid-rain.
- Name changed to Hansel Presley Saldanha (heading and page title); removed
  from the menu bar. Floating back-to-top button added.
- Archive section replaced by a hover dropdown in the menu (Overture, Gate,
  Study).
- README updated to match (scenery, versioning).
- Closing line under Contact: "Did you spot the orca in the Bay?"

## PRIORITY TO-DO (single source of truth — keep current)
1. Fill the draft's todo tags: headline and target roles, confirm Seattle,
   intro paragraph, public contact method, verify LinkedIn link.
   (Optional: hide todo tags on the live site until confirmed.)
2. Jam Clean: screenshots and Hansel's contribution details.
3. Decide whether to keep the 2020 SSRN paper note.
4. Life: one story + one photo per interest (choir, cooking, swimming,
   reading). Photo-frame picture set if the study concept returns.
5. GoatCounter account → Claude adds the analytics snippet.
6. Side elements, parallax, click-sketches — after content is real.
7. Decide final name / custom domain ("hanselius.dev" is a working title).
8. Later: free backend (Flask assumed), mobile dashboard app, wedding 2027
   site — specced in the Master Plan doc.
