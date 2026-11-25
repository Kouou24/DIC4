# Design: 006-references

## Context
See `proposal.md` for motivation. After sections `00-abstract` through `005-conclusion` are applied to `DIC4/main.tex`, `references.bib` and the full PDF build must be verified.

## Goals / Non-Goals
**Goals:** Ensure all citations (including `mof_disposal` and any new citations added during `001`–`005`) exist in `references.bib`, keep `\balance` active, and verify `0` errors via Overleaf `compile` + `read_log`.
**Non-Goals:** Adding unverified or hallucinated bibliographic entries.

## Decisions
- Run `compile` and `read_log` on Overleaf `DIC4` (`6b06476f303028f28d394422`) after the final section edit and inspect all warnings.

## Risks / Trade-offs
- **BibTeX key mismatches** → Cross-check every `\cite{...}` key in `main.tex` against `references.bib`.
