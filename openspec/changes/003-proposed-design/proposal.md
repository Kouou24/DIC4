# Proposal

## Why

The current Overleaf `DIC4/main.tex` splits the system design across three separate sections (`System Architecture`, `Core Algorithms`, `Implementation`). For ICEIB, these must be unified into a single `III. Proposed Design` section following the 2020 A-Z SOP (`PA`–`PM`).

## What Changes

- Consolidate and rewrite `III. Proposed Design` in `DIC4/main.tex` covering `PA` through `PM` of `My_ref/A2Z outline example.pdf`:
  - `PA`–`PD`: Aim, Based-on/Benefit, Cure/Cause, Design paradigm shift.
  - `PE`–`PH`: Paper elements (8-stage pipeline, M1–M4, P1–P4, tools, RBAC, `rules.yaml`), Foundation, TikZ Architecture & State-Machine Graphs, and How goals are achieved.
  - `PI`–`PL`: Algorithms 1–3, `A003` GPU workstation walkthrough (`PJ`), key contributions (`PK`), and link to experimental evaluation (`PL`).
  - `PM`: Deterministic valuation equations and bounded-termination/RBAC-safety properties.

## Capabilities

### New Capabilities
- `paper-proposed-design-a2z`: Author and validate `III. Proposed Design` (`PA`–`PM`) for the LabSteward ICEIB paper in Overleaf `DIC4`.

### Modified Capabilities
<!-- None -->

## Impact

- Overleaf `DIC4/main.tex` (`\section{Proposed Design}`).
