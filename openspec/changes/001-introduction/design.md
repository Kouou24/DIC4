# Design: 001-introduction

## Context
See `proposal.md` for motivation. The current `Introduction` in `DIC4/main.tex` lacks explicit `I` (literature grouping) and `J` (SWOT/judgement preview) before `K` (Keypoints) and `L` (List organization).

## Goals / Non-Goals
**Goals:** Structure `I. Introduction` cleanly as `G`–`L` using verified statistics from `DESIGN.md` and `專業摘要.pdf`.
**Non-Goals:** Moving the full 4x5 SWOT table into Introduction (that belongs in `II. Related Work` item `O`).

## Decisions
- `G`: Control Yuan precision instrument utilization report + Korea 2026 open-research-infrastructure policy + Deloitte/McKinsey 2026 procurement AI adoption gap.
- `H`: Four lab pain points (P1–P4) from `DESIGN.md` 1.2.
- `I` & `J`: Brief grouping (Excel/campus ERP → commercial procurement AI → pure LLM/shopping agents) and their high-level pros/cons leading to the research gap.
- `K`: Five bulleted LabSteward design keypoints/contributions.
- `L`: Roadmap pointing to Sections II–V (`Related Work`, `Proposed Design`, `Experiment`, `Conclusion`).

## Risks / Trade-offs
- **Overlap with Related Work** → Keep `I` and `J` concise in Introduction (1–2 paragraphs) and expand in `II. Related Work`.
