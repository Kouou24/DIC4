# Design: 002-related-work

## Context
See `proposal.md` for motivation. Currently `II. Related Work` has four subsections (`Asset Management`, `Procurement AI`, `ReAct/RAG`, `Residual Value`) without the `O` 4x5 SWOT/judgement summary table.

## Goals / Non-Goals
**Goals:** Order `M` from old/simple to new/complex, articulate `N` (new trend: deterministic-guarded Agentic RAG), and present `O` as a 4x5 SWOT/judgement table.
**Non-Goals:** Adding unverified external citations beyond `references.bib`.

## Decisions
- Use `\begin{table*}[t]` (two-column span) with `\footnotesize` for the 4x5 SWOT/judgement table so all 5 columns (Method Category, Strengths, Weaknesses, Opportunities/Threats, Taiwan Compliance & Auditability) fit cleanly with zero `Overfull \hbox`.

## Risks / Trade-offs
- **Table width overflow** → Fixed by using `table*` with `p{...}` column widths.
