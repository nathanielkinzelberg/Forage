# CLAUDE.md — Forage Simulations

This file tells Claude Code how to work with this repository.

## Repository Purpose

This repo contains Nathaniel's Forage virtual job simulations, each in its own subdirectory. Simulations are educational programs — not employment. Documentation should make that distinction clear.

## Repository Layout

```
Forage/
├── README.md
├── CLAUDE.md                                    # This file
└── PwC-Cybersecurity-Consulting-Simulation/
    ├── README.md
    ├── CLAUDE.md
    ├── docs/
    │   ├── overview.md
    │   ├── key-concepts.md
    │   ├── lessons-learned.md
    │   └── references.md
    ├── task-01/
    │   ├── README.md
    │   ├── methodology.md
    │   └── findings.md
    ├── task-02/
    │   ├── README.md
    │   ├── methodology.md
    │   └── findings.md
    ├── task-03/
    │   ├── README.md
    │   ├── methodology.md
    │   └── findings.md
    ├── task-04/
    │   ├── README.md
    │   ├── methodology.md
    │   └── findings.md
    └── assets/
        └── screenshots/
```

Only create task folders that actually correspond to simulation tasks. Do not create placeholder content.

## Simulation Tracking

| Simulation | Path | Status |
|------------|------|--------|
| PwC Cybersecurity Consulting | `PwC-Cybersecurity-Consulting-Simulation/` | In Progress |

Update this table when a simulation is completed.

## Workflow Per Task

1. User sends task instructions and materials
2. Explain the objective, concepts, and real-world context — ask questions before giving answers
3. User develops their approach or draft
4. Review, challenge, refine
5. Produce professional Markdown documentation
6. Commit before moving to the next task

## Key Rules

- Never fabricate results, findings, or actions the user hasn't performed.
- Never publish copyrighted or confidential simulation materials.
- Documentation is Nathaniel's original analysis — not copied simulation content.
- Always label simulation work as educational, not actual consulting employment.
- Each simulation has its own `CLAUDE.md` — read it before starting work in that subfolder.
- Update `README.md` at the root when a new simulation is added or a status changes.

## Portfolio Integration

When a simulation is complete:
- Polish the simulation's README for GitHub presentation
- Update the Simulations table in this repo's README.md
- Add a project card to `~/Projects/portfolio/index.html` (read `~/Projects/portfolio/CLAUDE.md` first)
- Update `~/Projects/Home.md`
