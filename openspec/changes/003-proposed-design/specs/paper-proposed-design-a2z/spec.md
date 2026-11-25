# Spec Delta: paper-proposed-design-a2z

## Purpose

Defines the PA-to-PM SOP structure and technical grounding requirements for `III. Proposed Design` of the LabSteward ICEIB paper.

## ADDED Requirements

### Requirement: Unified Proposed Design Section (PA–PM)
The paper SHALL consolidate system architecture, algorithms, and implementation into a single `\section{Proposed Design}` covering `PA` through `PM` of `My_ref/A2Z outline example.pdf`.

#### Scenario: PA-to-PM coverage
- **WHEN** `\section{Proposed Design}` in `DIC4/main.tex` is reviewed
- **THEN** it covers Aim (`PA`), Based-on/Benefit (`PB`), Cure/Cause (`PC`), Design paradigm shift (`PD`), Paper elements (`PE`), Foundation (`PF`), TikZ Graphs (`PG`), How (`PH`), Implementation & Algorithms 1–3 (`PI`), Case study example (`PJ`), Key contributions (`PK`), Evaluation link (`PL`), and Valuation/formal properties (`PM`).

### Requirement: Grounded Technical Artifacts
All figures, tables, algorithms, schemas, and case-study examples in `III. Proposed Design` SHALL match `DESIGN.md`, `db/schema.sql`, `knowledge/rules.yaml`, and `data/sample_assets.csv`.

#### Scenario: Consistency with repository artifacts
- **WHEN** the TikZ architecture, FSM states, RBAC table, `rules.yaml` snippet, and `A003` case study are checked against `AIOT-Final`
- **THEN** all state names, role permissions, threshold values, and asset IDs match the repository files exactly.
