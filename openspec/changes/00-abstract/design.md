# Design: 00-abstract

## Context
See `proposal.md` for motivation. The existing `Abstract` in `DIC4/main.tex` is informative but not explicitly ordered as `A`–`F` per the 2020 A-Z SOP.

## Goals / Non-Goals
**Goals:** Map `A`–`F` into a single crisp IEEEtran abstract (~150–200 words) plus `IEEEkeywords`.
**Non-Goals:** Adding citations inside the abstract (standard IEEE style avoids citations in abstracts).

## Decisions
- `A`: Publicly funded university lab equipment scale and utilization motivation.
- `B`: "Bought but unused, used but unrecorded, broken but undisposed" + lack of Taiwanese procurement compliance in existing tools.
- `C`: Propose LabSteward domain AI Agent.
- `D`: Built on LLM ReAct planner, hybrid RAG, deterministic YAML rule engine, dual-track valuation, and human-in-the-loop approval.
- `E`: Evaluated on a 50-task benchmark against three baselines (B1–B3).
- `F`: Expected improvements in compliance, asset reuse, stability, and drafting time (no fabricated numbers).

## Risks / Trade-offs
- **Abstract exceeds 200 words** → Keep each `A`–`F` step to 1–2 tight sentences.
