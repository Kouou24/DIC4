# Design: 004-experiment

## Context
See `proposal.md` for motivation. `DIC4/main.tex` currently titles this section `Experimental Evaluation` and mixes `Q`–`V` elements.

## Goals / Non-Goals
**Goals:** Rename to `\section{Experiment}` and order subsections cleanly as `Q`–`V`, explicitly documenting tunable parameters (`T`: `N_min`, `K_max`, `T_max`, `R_max`, `tau`, `u_min`, `delta`).
**Non-Goals:** Running `eval/run_eval.py` or populating fake numbers in `tab:results`.

## Decisions
- Present `Q` (Metrics table), `R` (Baselines B1–B3), `S` (50-task dataset + de-identified/market data), `T` (Configurable policy & valuation parameters from `rules.yaml`), `U` (Expected outcomes + `TBD` comparison table), and `V` (Ablation study A1–A4).

## Risks / Trade-offs
- **Reviewers expecting numbers** → Clearly state "ongoing benchmark evaluation" and distinguish expected architectural behaviors from pending measurements.
