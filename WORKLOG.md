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

### Open items
- Approve/adjust the Apollo + Bacchus implementation strategy, then build.
- Content needed from Hansel for Apollo: real skills, roles, education,
  project write-ups (Chatter, JamClean), links; for Bacchus: his stories.
- Real social links.
- Decide final name/domain ("hanselius.dev" is the working title).
- Eventually: enable GitHub Pages, then custom domain.
