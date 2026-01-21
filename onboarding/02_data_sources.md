---

## 📄 File 3: `onboarding/02_data_sources.md`

```md
# Data Sources – Kinetru Global

## Objective
Use **simple, reliable global market data** so focus stays on analysis.

---

## Primary Source (Recommended)
### Yahoo Finance via Python
Library: `yfinance`

Example indices:
- ^GSPC – S&P 500
- ^IXIC – NASDAQ
- ^DJI – Dow Jones
- ^FTSE – FTSE 100
- ^N225 – Nikkei 225
- ^NSEI – NIFTY 50

---

## Example Download Code
```python
import yfinance as yf

data = yf.download("^GSPC", start="2015-01-01")

Data Storage Rules
	•	Raw data → datasets/raw/
	•	Cleaned data → datasets/processed/
	•	Document any assumptions

⸻

Optional Sources
	•	Stooq
	•	Investing.com (manual CSV)
	•	FRED (macro overlays)

⸻

Naming Convention

index_<symbol>_<frequency>.csv

Example:

index_gspc_daily.csv