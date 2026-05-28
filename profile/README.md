<div align="center">

# Takt

### Keep your AI agents in rhythm.

Native macOS utility that starts AI CLI agents on schedule, aligns their session
windows to your workday, checks your network before every run, and gives you
scriptable control from the terminal.

**Local-first · Scriptable · Predictable**

</div>

---

## What is Takt?

Many AI coding tools start a quota/session window the first time you use them — so one
accidental launch at 10:37 can shift your whole day. **Takt** launches your agents at
times *you* choose (08:00, 13:00, 18:00, 23:00…), sends a tiny `ok`, and intentionally
starts those windows when your work actually begins.

It is **not** a cloud service, an AI wrapper, or a chat UI — just a small, local
scheduling utility for AI agent session alignment.

## Repositories

| Repo | What |
|---|---|
| [**takt**](https://github.com/TaktAgents/takt) | macOS menu bar app (Swift / SwiftUI) |
| [**takt-cli**](https://github.com/TaktAgents/takt-cli) | cross-platform CLI `takt` (Bun / TypeScript) |
| [**landing**](https://github.com/TaktAgents/landing) | marketing site (Astro + Tailwind) |
| [**docs**](https://github.com/TaktAgents/docs) | public documentation (Vocs) |

## Highlights

- ⏱️ **Scheduled agent runs** — any CLI agent at configured cron times.
- 🎛️ **Native menu bar control** — next runs, last successes, skipped launches, state.
- 🛡️ **Network Guard** — verify the public egress IP before launch; skip if it's on your blocked list.
- ⌨️ **CLI control** — trigger, inspect, pause, resume, and debug from scripts.
- 🧩 **Limits awareness** — optional CodexBar integration to skip exhausted windows.
- 📋 **Local-first logs** — every run, skip, timeout, and failure logged locally.

---

<div align="center">
<sub>Built for macOS power users who live in the terminal, menu bar utilities, and AI coding workflows.</sub>
</div>
