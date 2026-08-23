# No Perfectly Truthful Sequential Calibration Measure

## Abstract

A calibration measure should assign sublinear error to correct probabilistic forecasts, linear error to a fixed incorrect forecast, and give a forecaster no incentive to misreport its beliefs. Whether these three requirements can coexist under perfect truthfulness has remained open for sequential prediction. We prove that they cannot. Our main structural result shows that every bounded perfectly truthful measure computed from the outcomes and the forecasts observed along the realized path has a tree-additive Bayes risk. This representation requires no continuity, differentiability, strict truthfulness, or downstream decision guarantee. Although the measure itself may be nonsmooth, one fixed report probability avoids all nondifferentiability points across every horizon. At that report, the measure is forced to be a sum of nonnegative one-step proper losses. Concavity then implies that, under fair independent outcomes, this fixed incorrect report has expected error at most twice the truthful error. Completeness makes the latter sublinear, contradicting soundness. This resolves the perfect-truthfulness question posed by Haghtalab et al. and separates sequential evaluation from recent positive results for batch calibration. The boundary is sharp: if the evaluator can inspect the full forecast tree rather than one realized path, a simple squared-count score satisfies perfect truthfulness, completeness, and product soundness simultaneously.

## Contributions

- A no-regularity representation theorem for bounded perfectly truthful realized-path scores. Their entropy is a sum of history-dependent binary entropies over the forecast tree.
- An impossibility theorem resolving the open coexistence of perfect truthfulness, completeness, and soundness in sequential calibration. It removes the decision-theoretic assumption from the previous impossibility result.
- A quantitative witness. For one fixed $\beta\ne1/2$, the expected error of reporting $\beta$ on fair coins is at most twice the truthful expected error at every horizon.
- A matching information separation. Full-tree access admits a perfectly truthful, deterministically complete, product-complete, and product-sound score.

## Keywords

calibration measures, truthfulness, sequential prediction, proper scoring rules, impossibility results, forecasting incentives

## Files

- `main_old_2026-08-13.pdf`, the paper as first published, with its OpenTimestamps proof `main_old_2026-08-13.pdf.ots`.
- `main.pdf`, the current version.
- source: `iclr2027_conference.bst`, `iclr2027_conference.sty`, `main.tex`, `references.bib`.
- also: `main.aux`, `main.bbl`, `main.out`.
