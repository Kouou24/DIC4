# Spec Delta: paper-related-work-a2z

## Purpose

Defines the M-to-O SOP structure and comparative 4x5 SWOT/judgement table requirements for `II. Related Work`.

## ADDED Requirements

### Requirement: M-to-O Related Work Structure
`II. Related Work` SHALL follow steps `M` through `O` of `My_ref/A2Z outline example.pdf`: Methods ordered from old/simple to new/complex (`M`), New proposed trend and novelty (`N`), and Organization via a comparative SWOT/judgement table (`O`).

#### Scenario: M-N-O progression in Related Work
- **WHEN** `\section{Related Work}` in `DIC4/main.tex` is reviewed
- **THEN** it surveys legacy-to-modern methods (`M`), highlights the hybrid agentic-compliance trend (`N`), and summarizes them in a comparative table (`O`).

### Requirement: 4x5 Comparative SWOT Table
Item `O` SHALL include a 4x5 table comparing four method categories across five evaluation dimensions without `Overfull \hbox` in two-column IEEEtran layout.

#### Scenario: Table layout and dimensions
- **WHEN** the comparative table in `II. Related Work` is compiled in `DIC4`
- **THEN** it renders 4 rows (Manual/Campus ERP, Commercial Procurement AI, Pure LLM/Shopping Agents, LabSteward) by 5 columns cleanly within column or page width.
