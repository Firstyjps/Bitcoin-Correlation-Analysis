# Bitcoin Correlation Analysis Dashboard (BTC vs QQQ / SPY / Gold)

A Streamlit dashboard + research workflow for analyzing **Bitcoin correlation with traditional assets**.  
Focus assets:
- **BTC vs Nasdaq (QQQ)**
- **BTC vs S&P 500 (SPY)**
- **BTC vs Gold**
- *(Optional add-on)* **SET50** for additional comparison

## Live Results (Streamlit App)
View the dashboard and results here:  
**https://firstyjps.streamlit.app**

---

## What this project does
- Computes **rolling correlation** (e.g., 30-day window) to see how relationships change over time
- Visualizes correlations and trends in a clean dashboard
- Provides a repeatable workflow for producing charts that can be used in a report (PDF/Word)

---

## Project Structure
- `dashboard.py` — Streamlit app (main dashboard)
- `requirements.txt` — Python dependencies
- `test.ipynb` — notebook experiments / drafts
- `test.py` — quick testing scripts
- `README.md` — project overview

---

## How to Run Locally

### 1) Create & activate a virtual environment (recommended)
```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate
