# 🏓 NEON PONG — Premium Edition

A polished, single-file Pong game (you vs. the computer) built with plain HTML, CSS, and JavaScript. No build step, no dependencies — just open it and play.

![Made with](https://img.shields.io/badge/Made%20with-HTML%2FCSS%2FJS-19f0ff) ![No deps](https://img.shields.io/badge/Dependencies-none-7a5cff)

## ▶️ Play

Open `index.html` in any modern browser. That's it.

```bash
# clone, then:
open index.html        # macOS
# or just double-click the file
```

## ✨ Features

- **Predictive AI opponent** — the CPU forecasts the ball's path (including wall bounces) with tunable reaction time and aim error.
- **4 difficulty levels** — Easy, Normal, Hard, Insane.
- **Selectable match length** — first to 5, 7, or 11.
- **Angle-based paddle physics** — where you hit the ball changes its trajectory.
- **Escalating rallies** — the ball speeds up the longer a rally lasts, with a live rally counter.
- **Neon glassmorphism UI** — animated aurora background, glowing paddles and ball, motion trail.
- **Juice** — particle bursts, screen shake, and goal-line flashes on impact and scoring.
- **Procedural sound** — paddle, wall, scoring, and win/lose effects generated with the Web Audio API (no audio files).
- **3·2·1·GO countdowns**, pause/resume, fullscreen, and a mute toggle.
- **Victory / defeat screens** with instant rematch.

## 🎮 Controls

| Action | Keys |
| --- | --- |
| Move paddle | **Mouse**, or `↑` / `↓`, or `W` / `S` |
| Pause / resume | `Space` |
| Mute / unmute | `M` |
| Back to menu | `Esc` |
| Fullscreen | ⛶ button |

Touch controls are supported on mobile — drag on the left side of the court.

## 🛠️ Customizing

Everything lives in `index.html`:

- **AI strength / ball speed** — edit the `DIFF` presets near the top of the script (`speed`, `react`, `err`, `ballStart`).
- **Colors / theme** — tweak the CSS variables in `:root` (`--cyan`, `--magenta`, `--violet`, `--gold`).
- **Paddle size, margins, win logic** — see the constants and `scorePoint` / `bounce` functions.

## 📄 License

Free to use, modify, and share.
