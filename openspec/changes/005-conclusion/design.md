# Design: 005-conclusion

## Context
See `proposal.md` for motivation. The current `Conclusion` in `DIC4/main.tex` is a single paragraph that does not explicitly follow `W`–`Z`.

## Goals / Non-Goals
**Goals:** Structure `V. Conclusion` cleanly across `W`–`Z` and merge `Limitations and Future Work` into `Z` (or keep `Z` as the closing synthesis) so the top-level section list matches the user's exact 6-section request.
**Non-Goals:** Fabricating quantitative results in `Y`.

## Decisions
- Fold the key limitations (regulatory calibration, market data sparsity, LLM non-determinism) and future work (QR-code audit, LINE Bot, real transaction prices, multi-PI RBAC) into `Z` within `V. Conclusion` so the paper has no extra top-level section between `Experiment` and `Conclusion`.

## Risks / Trade-offs
- **Losing limitation details** → Keep all 3 limitations and 4 future-work items concisely preserved inside `V. Conclusion` (`Z`).
