# Proposal

## Why

Section `IV. Experiment` in Overleaf `DIC4/main.tex` needs to be renamed from `Experimental Evaluation` to `Experiment` and structured strictly according to the 2020 A-Z SOP (`Q`–`V`) for ICEIB IEEE conference style.

## What Changes

- Rewrite `\section{Experiment}` in `DIC4/main.tex` following `Q`–`V` of `My_ref/A2Z outline example.pdf`:
  - `Q`: Quality & Quantity performance metrics (Table of 8 metrics).
  - `R`: Related methods to compare (B1 Manual Excel, B2 LLM-only, B3 RAG-only).
  - `S`: Setup (50-task dataset, de-identified inventory, synthetic & market listings).
  - `T`: Tuning parameters (`N_min`, `K_max`, `T_max`, `R_max`, `tau`, `u_min`, `delta`).
  - `U`: Useful results (`TBD` placeholders per `DESIGN.md` 11.4, plus expected outcomes).
  - `V`: Verification plan via 4-ablation study (A1–A4).

## Capabilities

### New Capabilities
- `paper-experiment-a2z`: Author and validate `IV. Experiment` (`Q`–`V`) for the LabSteward ICEIB paper in Overleaf `DIC4`.

### Modified Capabilities
<!-- None -->

## Impact

- Overleaf `DIC4/main.tex` (`\section{Experiment}`).
