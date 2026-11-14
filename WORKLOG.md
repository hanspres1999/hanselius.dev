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

### Open items
- Replace placeholder copy in all eight sections with Hansel's real content.
- Real social links.
- Tune the synth orchestra (verdict pending from Hansel: majestic vs chiptune).
- Decide final name/domain ("hanselius.dev" is the working title).
- Eventually: enable GitHub Pages, then custom domain.
