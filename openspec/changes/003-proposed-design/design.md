# Design: 003-proposed-design

## Context
See `proposal.md` for motivation. The current `DIC4/main.tex` separates `System Architecture`, `Core Algorithms`, and `Implementation` into Sections III, IV, and V. ICEIB requires a single `III. Proposed Design` following `PA`–`PM`.

## Goals / Non-Goals
**Goals:** Unify Sections III–V into `III. Proposed Design` with clear `PA`–`PM` progression while preserving the TikZ architecture diagram, TikZ FSM, Algorithms 1–3, Technology Stack table, and RBAC table.
**Non-Goals:** Changing any algorithm logic or inventing unverified theorems for `PM`.

## Decisions
- Group `PA`–`PM` into five IEEE subsections:
  - `A. Design Aim, Paradigm Shift, and Principles (PA–PD)`
  - `B. System Elements, Architecture, and Foundation (PE–PH)` (includes Fig. 1 TikZ pipeline & Technology Stack)
  - `C. Algorithms, Database, and Governance (PI)` (includes Algorithms 1–3, Fig. 2 FSM, Table II RBAC, `rules.yaml`)
  - `D. Illustrative Case Study and Contributions (PJ–PL)` (`A003` GPU workstation walkthrough, key contributions, transition to Experiment)
  - `E. Formal Valuation Model and Safety Properties (PM)` (book/market equations + bounded-termination and RBAC-gating invariants).

## Risks / Trade-offs
- **Long Section III** → Use clear `\subsection` headings and compact tables/figures to maintain IEEE readability.
