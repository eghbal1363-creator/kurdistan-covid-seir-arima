# COVID-19 SEIR Modeling in Kurdistan Province

This repository provides the complete Python implementation of the SEIR epidemic model used in the study:

**"Hybrid SEIR and Time-Series Modeling of COVID-19 Dynamics in Kurdistan Province, Iran"**

The purpose of this repository is to enhance transparency and reproducibility of the modeling workflow while respecting ethical and institutional constraints on patient-level data sharing.

---

## ?? Contents

- `seir_analysis_only.py`  
  Python script implementing the SEIR model and generating epidemic curves with 95% confidence intervals.

- `covid19_kurdistan_seir.jpg`  
  Reproducible figure generated from the SEIR model (absolute population counts).

- `requirements.txt`  
  List of Python packages and exact versions used.

- `README.md`  
  Documentation and reproduction instructions.

---

## ?? Model Description

The SEIR (Susceptible–Exposed–Infected–Recovered) compartmental model is implemented using ordinary differential equations solved with `scipy.integrate.odeint`.

To quantify uncertainty, a Monte Carlo simulation framework is applied, where the transmission rate (?) is perturbed, and a 95% confidence interval is constructed for the infected compartment.

An intervention onset is explicitly marked to reflect changes in transmission dynamics.

---

## ?? Data Availability Statement

Due to ethical and institutional regulations from Kurdistan University of Medical Sciences, the original hospital admission data contain sensitive patient information and **cannot be shared publicly**.

Therefore, this repository does **not** include raw or synthetic hospitalization data.

Instead, it provides the **full analysis code** required to:
- Verify the modeling framework
- Reproduce the SEIR figures
- Apply the same workflow to authorized datasets

This approach ensures methodological transparency while fully complying with patient data privacy requirements.

---

## ?? How to Run the Code

1. Clone the repository:
   ```bash
   git clone https://github.com/eghbal1363-creator/kurdistan-covid-seir-arima.git
   cd kurdistan-covid-seir-arima
