# NowcastBox

**Nowcasting with dynamic factor models in Python.**

NowcastBox develops [`nowcastbox`](https://github.com/NowcastBox/nowcastbox), an
open-source (MIT) library that estimates the present, the recent past and the near future
of macroeconomic variables, such as GDP, from large panels of indicators released at
different frequencies and with different publication lags.

- **Models**: two-step and maximum-likelihood (EM) dynamic factor models with mixed
  frequencies (daily, weekly, monthly, quarterly), blocks, robust Student-t errors and a
  time-varying long-run mean.
- **Real time**: release calendars, pseudo real-time and real vintages, news
  decomposition and nowcast tracking.
- **Evaluation**: backtests against AR, bridge, MIDAS and scikit-learn benchmarks, forecast
  comparison tests and density scoring.
- **Data**: connectors to BCB, IBGE, IPEA and FRED, with built-in Brazilian and US datasets.

📖 [Documentation](https://nowcastbox.github.io/nowcastbox/) ·
💻 [Source](https://github.com/NowcastBox/nowcastbox) ·
🐛 [Issues](https://github.com/NowcastBox/nowcastbox/issues)

## Authors

- **Gustavo Haase**
- **Alexandre Leão Sanches**

Graduate Program in Economics, Universidade Católica de Brasília (UCB).
