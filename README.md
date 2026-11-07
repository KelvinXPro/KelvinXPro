# Xinyu (Lexyl) Li

**MS Financial Engineering, NYU Tandon** (expected 2028) · **BS Mathematics, CS minor, UIUC** (2026)
Seeking **Summer 2027** quantitative research and trading internships.

I build quantitative research that is designed to be checked: every headline number has a benchmark it can fail against, and every backtest has a test that tries to break it.

## Research

| Repository | The question | What it shows |
| --- | --- | --- |
| [spread-option-monte-carlo](https://github.com/KelvinXPro/spread-option-monte-carlo) | When Monte Carlo and Kirk's approximation disagree by 1.1%, which one is wrong? | Mostly neither. The gap is 1.96 standard errors of sampling noise; an exact conditional integral puts Kirk's true error at 0.09%, and conditional MC cuts variance about 3,300×. Input assumptions move the price more than the model does. |
| [cointegration-pairs-decay](https://github.com/KelvinXPro/cointegration-pairs-decay) | Why do cointegrated pairs stop working out of sample? | A cost-aware pipeline screens 226 equities with regression tests against look-ahead bias. The selected pair's hedge ratio drifts 83% and the pair fails on 2021–2026 data; the same screening process, rerun on new data, still finds a positive pair. |

The edge isn't in the backtest; it's in the test that tries to break it. Both repositories ship pinned dependencies, tests that lock every quoted number, and a Limitations section written as carefully as the results.

## Experience

- **Quantitative Research Intern, China Pacific Asset Management** (2025): evaluated backtests for 9 equity factor strategies on Sharpe, drawdown, turnover and costs; designed acceptance tests for an LLM strategy-generation tool.
- **Operations Strategy Intern, ByteDance** (2024): reconciled SQL definitions and maintained GMV dashboards for 2,000+ merchants.
- **Currently:** NYU FRE team, CME Group Trading Challenge (simulated trading).

## Toolkit

Python (NumPy, pandas, SciPy, statsmodels, scikit-learn, PyTorch) · C++ · SQL · R · Git · Linux · Bloomberg · LSEG Workspace

## Contact

[LinkedIn](https://www.linkedin.com/in/lexyl-li/) · xl5032@nyu.edu
