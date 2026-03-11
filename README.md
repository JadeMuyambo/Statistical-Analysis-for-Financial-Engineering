# Statistical-Analysis-for-Financial-Engineering
This repository contains six projects completed for **MTH 643 in Spring 2025** using R Markdown. I combined real-market data from Bank of America and JPMorgan Chase with simulated stochastic processes to practice statistical computing, time-series analysis, dependence modeling, and resampling.

## 🎯 Objective
Showcase applied statistics skills in R by:
- Exploring equity return behavior (EDA, distributions, heavy tails)
- Building and evaluating simple direction classifiers
- mModeling cross-asset dependence with copulas
- Studying linear and conditional-variance time series (ARMA, ARCH)
- Using simulation and bootstrap to validate theory and quantify uncertainty

## 🛠️ Tools & Packages
- **R / RStudio**, **R Markdown**
- Key packages: `quantmod`, `tidyverse`, `MASS` (LDA, fitdistr), `copula`, `mnormt`/`mvtnorm`, `ks` (KDE), `tseries`, `fGarch` (ARCH/GARCH), `stats` (glm, acf), `ggplot2`

## 📁 Problem Sets & Files

### PS1 — Monte Carlo vs. Theory for Random Walks
- **What’s included:** Simulate 200-step symmetric/biased/Gaussian walks; estimate boundary-crossing probabilities; verify with exact/binomial and CLT approximations.
- **Files:** [`muyambojade_mth643_problemset1.html`](./muyambojade_mth643_problemset1.html), prompt [`m643s25ps1.pdf`](./m643s25ps1.pdf)

### PS2 — Exploratory Analysis of BAC & JPM
- **What’s included:** Pull 5+ years of adjusted closes; plot prices & log-returns; Normal vs Student-t Q–Q diagnostics (heavy tails).
- **Files:** [`muyambojade_mth643_problemset2.html`](./muyambojade_mth643_problemset2.html), prompt [`m643s25ps2.pdf`](./m643s25ps2.pdf)

### PS3 — Return Densities & Direction Classification
- **What’s included:** KDE vs Normal vs t densities; Logistic Regression (lags, volume) and **LDA** to classify up/down; bivariate scatter of paired returns.
- **Files:** [`muyambojade_mth643_problemset3.html`](./muyambojade_mth643_problemset3.html), prompt [`m643s25ps3(1).pdf`](./m643s25ps3(1).pdf)

### PS4 — Bivariate-t & Copulas (t, Normal, Clayton, Joe)
- **What’s included:** MLE for bivariate-t with profile log-likelihood + 95% CI for df; univariate t fits; Kendall’s τ & Pearson ρ; copula fits with CDF contours.
- **Files:** [`muyambojade_mth643_problemset4B.md.html`](./muyambojade_mth643_problemset4B.md.html), prompt [`m643s25ps4(1).pdf`](./m643s25ps4(1).pdf)

### PS5 — Empirical vs Clayton Copula; Bootstrap α; ARMA(2,1)
- **What’s included:** Empirical-copula overlay vs fitted Clayton; Clayton pdf vs 2-D KDE; bootstrap variance of optimal weight in **αX + (1−α)Y**; ARMA(2,1) simulation & ACFs.
- **Files:** [`muyambojade_mth643_problemset5B.html`](./muyambojade_mth643_problemset5B.html), prompt [`m643s25ps5.pdf`](./m643s25ps5.pdf)

### PS6 — ARCH(1) Volatility & Ljung–Box Diagnostics
- **What’s included:** Simulate ARCH(1); ACF and Ljung–Box tests on returns and squared returns; derive **Var(Yₜ) = α₀/(1−α₁)**.
- **Files:** [`muyambojade_mth643_problemset6.html`](./muyambojade_mth643_problemset6.html), prompt [`m643s25ps6.pdf`](./m643s25ps6.pdf)

> Course context: [`MTH643_Syllabus.pdf`](./MTH643_Syllabus.pdf)


## 🧪 Skills Demonstrated
- **Statistical programming & reproducibility:** R Markdown workflow, vectorized simulation, seeded experiments.
- **Time-series EDA:** price/return transformations, ACF interpretation, stationarity intuition.
- **Distribution modeling:** KDE, Normal and Student-t fits, Q–Q analysis, heavy-tail reasoning.
- **Classification:** feature engineering with lags/volume, **GLM (logistic)** and **LDA**, performance interpretation when accuracy is near chance.
- **Dependence modeling:** rank correlation (Kendall’s τ), **bivariate-t**, and **copulas** (t, Normal, Clayton, Joe).
- **Resampling & inference:** **bootstrap** for portfolio weight variance; Monte Carlo vs theoretical checks.
- **Volatility modeling:** ARCH intuition, diagnostics, and analytical variance verification.

---

## 📄 License
- This project is licensed under the MIT lisence. See license file for details.

## 👩🏽‍💻 Author
**Jade Muyambo** — M.S. Data Science
University of Miami 
