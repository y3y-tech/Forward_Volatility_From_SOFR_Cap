# Forward_Volatility_From_SOFR_Cap

Strip forward volatilities from the SOFR cap market over 2022–2025 and test whether the forward vol curve predicts future spot vol—a Fama–Bliss analog for the volatility term structure. Characterize the resulting volatility term premium and analyze how it varies across the hiking, pause, and easing regimes of the Fed’s policy cycle.

## Setup
For mac
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

For windows
```bash
python -m venv .venv
.\.venv\Scripts\activate
pip install -r requirements.txt
```

Using uv
```bash
uv sync
```

**Before you push**
```bash
pip freeze > requirements.txt
```

OR

```bash
uv export --no-hashes --no-annotate --no-header -o requirements.txt
```
