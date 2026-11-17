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

### Open items
- Hansel: bring back inspiration links; then decide act IV direction
  (3D rebuild vs refined simplicity).
- Hansel: merge PR #1, then enable GitHub Pages (or ask Claude to try the
  Pages API again post-merge).
- Hansel: GoatCounter account + site code → Claude wires the snippet.
- Hansel: Apollo raw material (roles, education, skills, project blurbs,
  links, resume PDF).
- Build Apollo (scroll-scene design) with contact page; then Bacchus with
  contact page.
- Content needed from Hansel for Apollo: real skills, roles, education,
  project write-ups (Chatter, JamClean), links; for Bacchus: his stories.
- Real social links.
- Decide final name/domain ("hanselius.dev" is the working title).
- Eventually: enable GitHub Pages, then custom domain.
