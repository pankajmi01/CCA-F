# CCA-F · Claude Certified Architect Foundations

A self-contained study tracker and reference guide for the **Anthropic CCA-F (Claude Certified Architect — Foundations)** certification exam.

> **Live demo:** [pankajmi01.github.io/CCA-F](https://pankajmi01.github.io/CCA-F)  
> **Academy:** [anthropic.skilljar.com](https://anthropic.skilljar.com/)

---

## What's inside

| Tab | Description |
|-----|-------------|
| **Domains** | Full instructor guide — all 5 exam domains, task statements, knowledge points, and skills |
| **Courses** | All Anthropic Academy courses mapped to CCA-F exam domains |
| **Scenarios** | 6 realistic exam scenarios (4 appear on the actual exam, chosen at random) |
| **Practice** | 12 exam-style questions with full explanations |
| **Progress** | Track lesson completion across all courses with weighted score |

## Exam at a glance

| Domain | Weight |
|--------|--------|
| D1 — Agentic Architecture & Orchestration | 27% |
| D2 — Tool Design & MCP Integration | 18% |
| D3 — Claude Code Configuration & Workflows | 20% |
| D4 — Prompt Engineering & Structured Output | 20% |
| D5 — Context Management & Reliability | 15% |

**Pass score:** 720 / 1000

## Usage

This is a single-file app — no build step, no dependencies, no server required.

```bash
# Clone and open locally
git clone https://github.com/pankajmi01/CCA-F.git
cd CCA-F
open index.html   # macOS
# or just drag index.html into your browser
```

Progress is stored in memory during the session. To persist progress across sessions, use the app in a browser that keeps tabs open, or fork and add `localStorage` support.

## Deploy to GitHub Pages

1. Go to your repo → **Settings → Pages**
2. Set **Source** to `Deploy from branch`
3. Choose `main` branch, `/ (root)` folder
4. Click **Save**

Your tracker will be live at `https://pankajmi01.github.io/CCA-F/` within a minute.

## Contributing

Found an error in a knowledge point, skill, or question explanation? PRs welcome — open an issue or submit a fix directly.

## License

MIT — free to use, share, and adapt.
