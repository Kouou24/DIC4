# Spec Delta: paper-experiment-a2z

## Purpose

Defines the Q-to-V SOP structure and non-fabrication requirements for `IV. Experiment` of the LabSteward ICEIB paper.

## ADDED Requirements

### Requirement: Q-to-V Experiment Structure
`\section{Experiment}` SHALL follow steps `Q` through `V` of `My_ref/A2Z outline example.pdf`: Quality/Quantity metrics (`Q`), Related methods to compare (`R`), Setup (`S`), Tuning parameters (`T`), Useful results (`U`), and Verification plan (`V`).

#### Scenario: Q-to-V flow in Experiment
- **WHEN** `\section{Experiment}` in `DIC4/main.tex` is reviewed
- **THEN** it presents the 8 evaluation metrics (`Q`), baselines B1–B3 (`R`), 50-task dataset setup (`S`), configurable parameters (`T`), results table (`U`), and 4-ablation verification plan (`V`).

### Requirement: Non-Fabrication of Unexecuted Results
Unexecuted benchmark metrics in `IV. Experiment` SHALL be marked `TBD` and clearly distinguished from architectural expectations.

#### Scenario: Placeholder results table
- **WHEN** `tab:results` is inspected
- **THEN** all unmeasured cells display `TBD` or `---` per `DESIGN.md` Section 11.4.
