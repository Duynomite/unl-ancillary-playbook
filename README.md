# The Ancillary Playbook

Comprehensive training for Clear Path Coverage MA agents cross-selling UNL Hospital Indemnity (HI) and Home Healthcare (HHC) on every MA call, plus dedicated HHC lead sales.

**Live URL:** https://duynomite.github.io/unl-ancillary-playbook/
**Iframed at:** clearpathcoverage.com (WordPress shell)

## What this is

The Ancillary Playbook is the complete training tool for CPC MA agents. It absorbed and replaced the prior 3-tool educational stack (Crash Course + Master Class + Strategy Guide) into a single comprehensive resource structured as 3 modules:

- **Module 1 — The Core (~45 min):** Why it matters · Two-step motion · Know your products · Integrated CPC script · Rx-Net-Cost reframe · Q1-Q4 close · Top 6 objections · Six Master Principles.
- **Module 2 — The Depth (~35 min):** Reading the customer · NEPQ discovery mastery · Customer profiles · Advanced pushback (5 advanced objections + emotional curveballs + rapport repair + skeptical-of-insurance + time pressure) · 2 annotated master calls.
- **Module 3 — The Specialized (~15 min):** HHC-specific lead sales · Income + mastery path.

Followed by a 7-question scenario assessment with printable certification.

## Deploy structure

This repo is the **public deploy artifact only**. Contains a single static HTML file (`index.html`) served by GitHub Pages.

- **Source:** lives in the private `Duynomite/claude-projects` repo at `TOOLS/MA_Crosssell_Strategy_Guide.html`.
- **Companion:** `Duynomite/unl-ancillary-quickref` — during-call quick reference.

## Update flow

1. Edit `TOOLS/MA_Crosssell_Strategy_Guide.html` in the private source repo.
2. Copy to `/tmp/unl-ancillary-playbook/index.html`.
3. `git commit -am "..."` and `git push`.
4. GitHub Pages auto-rebuilds; WordPress iframe picks up new content. No WP touch needed.
