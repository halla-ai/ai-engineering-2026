---
title: Capstone Project Overview
description: AI Systems 2026 Capstone — Ralphthon individual project guide
---

## Ralphthon Capstone Project

**Ralphthon** is the final capstone project of this 16-week course. Each student **individually** designs and implements an **autonomous agentic system that solves a real software problem**, based on the Ralph Loop methodology.

> **2026 Format**: Given the small class size, the capstone runs as **individual projects** rather than team projects.

## Schedule

| Week | Content | Deadline |
|------|---------|----------|
| Week 8 | Project proposal PR + proposal presentation (midterm replacement) | 2026-04-20 / present 04-21 |
| Week 13 | Kickoff + architecture design document | 2026-06-03 |
| Week 14 | Ralphthon execution + interim report | 2026-06-10 |
| Week 15 | Integration testing + presentation materials | 2026-06-17 |
| Week 16 | Final presentation + peer evaluation | 2026-06-24 |

## Grading

The capstone is worth 30 points (30% of the final grade). Separately, the **Week 8 proposal counts as 20% (midterm project)**.

| Item | Points | Description |
|------|--------|-------------|
| Technical Completeness | 12 | Agent pipeline actually works |
| Problem Fit | 6 | Appropriateness of topic and effectiveness of solution |
| Presentation Quality | 6 | Clear explanation, live demo |
| Peer Evaluation | 6 | Evaluation of other students' presentations and deliverables |

## Submission Structure

```
capstone/
└── projects/
    └── [student-id]/
        ├── proposal.md        # Project proposal (Week 8)
        ├── design.md          # Architecture design document (Week 13)
        ├── progress-week14.md # Interim progress report (Week 14)
        ├── README.md          # Final project documentation (Week 15)
        ├── report.md          # Final report (Week 15)
        ├── links.md           # External links for slides + demo video (Week 15)
        └── src/                # Source code
```

> **Slides and demo video are submitted as external links**: To keep the repository lean, `.pdf` and `.mp4` files are not committed directly — instead, record external URLs (Google Drive / YouTube / Figma, etc.) in `links.md`. `.gitignore` blocks `*.pdf` and `*.mp4`.

## Related Pages

- [Project Registration](/en/capstone/teams)
- [Project Proposal Writing Guide](/en/capstone/proposal-guide)
- [Detailed Rubric](/en/capstone/rubric)
- [Submission Status](/en/capstone/submissions)
