# 🏁 Math Race

A fast, colourful, **completely offline** math practice game for kids — one HTML file, no install, no internet, no accounts.

Inspired by the class-race format of 99math, minus the multiplayer: instead of racing other people, you race a **ghost replay of your own best run**.

![single file](https://img.shields.io/badge/one-HTML%20file-7c5cff) ![offline](https://img.shields.io/badge/works-offline-3ddc84) ![no build](https://img.shields.io/badge/build%20step-none-00d4ff)

---

## Play it

Download `math-race.html` and double-click it. That's the whole setup.

Works in Chrome, Edge, Firefox and Safari, on a laptop or a tablet.

---

## What's in it

**Racers** — a profile per kid: name, character, level band (K–2 / 3–5 / 6–8), and their own choice of operations, difficulty and race length. Everything saves between sessions.

**The race** — 3-2-1-GO countdown, then as many questions as you can answer before the clock runs out. Streaks build a ×1.5 → ×2 → ×3 multiplier, fast answers earn a speed bonus, and a track at the top races your character against a 👻 ghost of your own personal best on those exact settings.

**Question types**
- ➕ ➖ ✖️ ➗ across three level bands and three difficulties (🐢 Chill / 🐇 Normal / 🔥 Turbo)
- ❓ Missing-number problems (`7 × ▢ = 42`)
- 🧠 Brain teasers for grades 6–8: order of operations, squares, roots, percents, negatives

**Progression that carries over**
- 🏅 **Career points** — every point from every race is banked forever
- **Levels & titles** — Rookie → Cadet → Racer → Ace → Champion → Legend → Math Wizard → Grand Master
- 🪙 **Coins** — earned per race, with bonuses for accuracy, long streaks, personal bests, and daily play
- 🔥 **Daily streak** — come back tomorrow for a bigger coin bonus
- 🛒 **Shop** — unlock 16 extra characters, 10 pets that ride along on the track, and 5 track themes

**Practice that adapts** — wrong answers show the correct one, get re-asked later in the same race, and are remembered. Facts a kid keeps missing quietly resurface in future races until they stick.

**For grown-ups** — a Progress screen with per-operation accuracy bars and a list of each kid's shakiest facts, plus a family leaderboard of the top 15 races.

---

## Controls

| | |
|---|---|
| Type an answer | On-screen keypad, or number keys |
| Submit | `Enter` / `Space` / the ✓ key |
| Delete | `Backspace` |
| Negative numbers | `-` or the ± key (grades 6–8) |
| Pause | `Esc` |

Correct answers auto-advance by default, so there's no need to hit Enter when you're on a roll. Both that and the re-ask-missed-questions behaviour are toggles on the setup screen.

---

## Notes

- Progress is stored in that browser's `localStorage`, so use the same browser on the same device. Copying the file elsewhere starts a fresh save.
- The file has to live on disk as a real file — opening it from inside a zip won't save scores.
- No network requests, no tracking, no dependencies. Sound is synthesised with the Web Audio API, so there are no asset files to lose.

---

## License

MIT — do whatever you like with it.
