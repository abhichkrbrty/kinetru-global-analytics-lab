# Access & Environment Setup

## Purpose
Ensure every contributor can run, analyze, and submit work without friction.

---

## Required Accounts
- GitHub account (public)
- Local Git installation
- Python 3.9+ installed
- VS Code or equivalent editor
- (BI role) PowerBI Desktop

---

## Repo Access
1. Fork the repository
2. Clone your fork locally
3. Add upstream remote if needed

```bash
git clone https://github.com/<your-username>/kinetru-global-analytics-lab.git

Python Environment (Data Roles)

Recommended: virtual environment

python -m venv .venv
source .venv/bin/activate  # mac/linux

Install basics:
pip install pandas numpy matplotlib seaborn jupyter yfinance

Rules
	•	Do NOT commit secrets
	•	Do NOT upload raw credentials
	•	Large datasets stay out of Git unless approved
