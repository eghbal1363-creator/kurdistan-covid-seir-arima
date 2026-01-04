# COVID-19 SEIR Modeling in Kurdistan Province

This repository provides the code and synthetic data to fully reproduce the SEIR model results for the early COVID-19 epidemic in Kurdistan Province, Iran (Feb–Apr 2020).

## Key Features
- Absolute numbers (population = 1,600,000)
- 95% confidence interval for Infected via Monte Carlo simulation
- Intervention onset marked on day 25
- High-resolution figure

## Files
- `seir_arima_analysis.py`: SEIR model with uncertainty quantification and plotting
- `covid19_kurdistan_seir.jpg`: Generated figure (absolute numbers with 95% CI)
- `synthetic_hospitalizations.csv`: Synthetic hospitalization time series
- `requirements.txt`: Dependency versions
- `kurdistan_covid_seir_arima.zip`: Legacy zipped version (contains older files)

## Reproduction
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
