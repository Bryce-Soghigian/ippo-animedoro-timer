# Ippo Animedoro Timer 🥊

Minimal, flocus-style animedoro timer with full-screen Hajime no Ippo gifs.

- **Full background gifs** — work vs relax swap (high-res 498px, ~1.5MB)
  - Work: Dempsey Roll (`c.tenor.com/esQzZcKf6FwAAAAC/dempsey-roll.gif` → `assets/work.gif`)
  - Relax: Ippo chill (`c.tenor.com/dhiZs4RULI0AAAAC/ippo-hajime-no-ippo.gif` → `assets/relax.gif`)
- **Flocus-like minimal UI** — centered glass card, `88px` tabular timer, thin progress line, single Start/Pause + Reset + Skip
- **Custom time split** — pick any work/break you want:
  - Presets: 40/20 (default animedoro), 25/5, 45/15, 50/10, 60/20, 30/10
  - Or custom via stepper/number inputs (1–120m work, 1–60m break) with live split preview (`40m work + 20m break = 60m cycle`)
  - Persisted in `localStorage` (`animedoro-ippo-v2`), updates instantly; `⚙` gear opens settings modal
- **Sound & notifications** — boxing-bell Web Audio chime + `Notification` + title flash on phase change (toggleable, permission button)
- **Custom gifs** — paste any Tenor/Giphy URL in settings to replace either background (saved locally)

## Use

Open `index.html` directly or `npx serve .` — no build.

```
open index.html
# presets or custom split via ⚙
Space = Start/Pause, R = Reset, S = Skip, Esc = close settings
```

Gifs are fan-use via Tenor; replace via settings if publishing commercially.
