# ProgramPulse

**Portfolio health at a glance — a lightweight dashboard for program managers.**

ProgramPulse turns a portfolio of programs into a single, scannable health view: RAG status, progress, open risks, and the next milestone for every program, plus an auto-generated "pulse" summary that reads the portfolio and tells you where attention is needed.

🔗 **Live demo:** _add your deployed URL here_

---

## Why I built it

As a program manager, I spend a lot of time answering one question for leadership: *"What's the status across everything?"* The honest answer usually lives in a sprawling spreadsheet that nobody outside the PMO wants to read.

ProgramPulse is my take on the alternative — a focused tool that does three things well:

1. **Shows status instantly.** Color-coded program cards (on track / at risk / off track), each with progress, open risks, and the next milestone.
2. **Summarizes the portfolio in plain language.** The "pulse" banner reads every program and writes a one-line health summary — surfacing the nearest milestone and flagging what's off track, so leadership gets the headline before the detail.
3. **Stays out of the way.** No login, no setup, no backend to maintain. Add a program in seconds; data persists privately to your session.

It's intentionally small. The goal was a tool a PM would actually open on a Monday morning — not another dashboard that takes a quarter to roll out.

## Features

- **Live portfolio pulse** — auto-generated health summary and at-a-glance counts (on track / at risk / off track)
- **Program cards** — RAG status, progress bar, open-risk flag, next milestone with due-date countdown
- **Filtering** — view all programs or drill into a single status
- **Detail view** — full program detail including days-to-milestone and the top risk/note
- **Add / edit / delete** — manage the portfolio inline
- **One-click sample portfolio** — load a realistic set of programs to explore the tool
- **Responsive + accessible** — works on mobile, keyboard-navigable, respects reduced-motion

## Tech

- Single-file **vanilla HTML / CSS / JavaScript** — no framework, no build step
- Persistent storage via a simple key-value store
- Designed to deploy anywhere static (GitHub Pages, Netlify, Vercel) in under a minute

No dependencies by design: the whole app is one `index.html` you can read top to bottom.

## Run it locally

Clone the repo and open the file — that's it.

```bash
git clone https://github.com/<your-username>/ProgramPulse.git
cd ProgramPulse
open index.html      # or just double-click it
```

## Roadmap

- [ ] Export portfolio to CSV / PDF for status reports
- [ ] Milestone timeline (Gantt-style) view
- [ ] Risk register per program with severity scoring
- [ ] Trend tracking — health over time, not just a snapshot

## About

Built as a portfolio project by a program manager exploring AI-assisted, tech-forward delivery — pairing 12+ years of hands-on program management with modern build tools.

---

_Sample data in the demo is illustrative and does not represent any real company's confidential information._
