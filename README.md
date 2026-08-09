# Ippo × Initial D — Animedoro Timer 🏁🥊

Flocus-style minimal animedoro timer with full-screen high-res themes.

## Themes
- **🥊 Hajime no Ippo** (default): Work = Dempsey Roll `498×380 1.5MB` (`esQzZcKf6FwAAAAC`), Relax = Ippo chill `498×375 1MB` (`dhiZs4RULI0AAAAC`)
- **🏎️ Initial D**: Work = AE86/FD drift `498×318 1.2MB` (`8I_13j-yo0UAAAAC/initiald-car.gif`), Relax = Eurobeat driving `498×369 228KB` (`1osmNTdrmukAAAAC`)

Switch via theme pills above Work/Watch or in `⚙` → Theme (persisted `localStorage: animedoro-ippo-v3`). Custom GIF URLs per theme still supported.

## UI — Image 1 / Flocus style
- Two pills top: `📚 Work` (white fill active) / `📺 Watch` (outline)
- Huge `50:00`-style time `clamp(84px,18vw,148px)` — **click the time to edit split**
- Controls: black `Start/Pause` pill + `↻` reset + `⚙` gear; no glass card, just floating over full-bleed gif
- Background: full viewport `object-fit:cover` gifs with crossfade `0.8s`, `scale(1.04→1)` + dark overlay

## Time split
Presets `40/20`, `25/5`, `45/15`, `50/10`, `60/20`, `30/10` + custom stepper (Work 1–120m, Watch 1–60m) with live split preview bar. Applies instantly, saved locally. Open via clicking time or gear. Also `Space`/`R`/`Esc`.

## Use
```
open index.html  # or npx serve .
# click 40:00 to change 40/20 → any split, or toggle 🥊/🏎️ theme
```

Gifs fan-use via Tenor `c.tenor.com/…AAAAC` (high-res); replace via settings if publishing commercially.
