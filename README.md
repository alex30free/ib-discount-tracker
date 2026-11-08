# Investment Company Discount Tracker

Part of [StockLab](https://alex30free.github.io/stocklab/).
Discount or premium to NAV for the Swedish investment companies on [ibindex.se](https://ibindex.se/ibi/#/index),
with z-score buy/sell zones, a backtest and each company's largest holdings.

- `index.html` – the page (GitHub Pages)
- `data.json` – data, updated every Friday by `.github/workflows/ibindex-weekly.yml`
- `scripts/ibindex_update.py` – downloads ibindex data and recomputes `data.json`

For informational purposes only — not financial advice.
