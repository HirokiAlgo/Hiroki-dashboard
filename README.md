# HirokiAlgo — Next 3 Chapters Dashboard

> An interactive, single-file progress dashboard tracking the next three chapters of my roadmap:
> **Summer 2026 → 1Bac SM → Summer 2027 (IOI 2027, Germany 🇩🇪)**

![Dark themed dashboard](https://img.shields.io/badge/theme-JARVIS%20dark-22d3ee) ![No dependencies](https://img.shields.io/badge/dependencies-none-f5c518) ![License](https://img.shields.io/badge/license-MIT-22c55e)

## ✨ What it is

A pure **HTML + CSS + JavaScript** dashboard (zero dependencies, works fully offline) that tracks every goal and event across the next 15 months of my life:

| Chapter | Period | Focus |
|---|---|---|
| ☀️ **Chapter I — Summer 2026** | Jul → Sep 2026 | CF 1600 Expert · CSES 100 · German A1 · Digital identity |
| 🎓 **Chapter II — 1Bac SM** | Oct 2026 → Jun 2027 | MOI 2027 rounds · CF 1900 Candidate Master · SAT 1500+ · German A2 → B1 |
| 🌅 **Chapter III — Summer 2027** | Jul → Sep 2027 | **IOI 2027 Germany 🇩🇪** · CF 2100 Master · German B1 · IOI past problems |

## 🚀 Features

- **3 chapter tabs** with per-chapter progress rings and done counters
- **Checkboxes** on every goal/event — tick them, get confetti 🎉
- **Live countdown** to the next upcoming deadline (days/hrs/min/sec)
- **Days-left badges** on every row (green → yellow → red)
- **Measurable goals** with +/− buttons and live progress bars (CF rating, CSES count, SAT score, Bac grade…)
- **Priority stars** (★★★★★) on every item
- **EXPORT DAY** — downloads your full progress as JSON
- **AUTO 23:55** mode — arms an automatic daily export at 11:55 PM
- **localStorage** — all progress is saved in your browser automatically
- Fully **responsive**, dark JARVIS-style theme, keyboard-friendly

## 📦 Usage

```bash
# clone
git clone https://github.com/hirokialgo/next-3-chapters.git
cd next-3-chapters

# open — no build, no server needed
open index.html        # macOS
xdg-open index.html    # Linux
# or just double-click index.html
```

## 🗂️ Repo structure

```
next-3-chapters/
├── index.html     # the entire dashboard (HTML + CSS + JS in one file)
├── README.md      # this file
├── LICENSE        # MIT
└── .gitignore
```

## 💾 Data & privacy

Everything you tick or enter is stored **locally in your browser** (`localStorage`, key `hirokialgo_3chapters_v1`). Nothing is sent anywhere. Use **EXPORT DAY** regularly to keep JSON backups — you can re-import them manually if you switch devices.

## 📌 About me

**Abderrahmane F. "HirokiAlgo"** — 16 y/o student from Morocco 🇲🇦
Competitive programming · IOI 2027/2028 · German A1→B2 · MIT 2029 🎯

> *"You are building your genius step by step."*

## 📄 License

MIT — see [LICENSE](LICENSE). Fork it, adapt it, track your own chapters.
