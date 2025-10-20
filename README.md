# Two-Stage Frontier Benchmarking (2-FB) Analysis: DEA + SFA Implementation

This repository contains the implementation of a **two-stage frontier benchmarking (2-FB)** framework developed to evaluate organizational efficiencies during the COVID-19 pandemic using **Data Envelopment Analysis (DEA)** and **Stochastic Frontier Analysis (SFA)**. The approach integrates country-level and hospital-level performance data across Asia between **January 2020 and June 2021**.

---

## 📘 Study Overview

With 18 months of data (January 2020 – June 2021), this study develops a **two-stage frontier benchmarking (2-FB)** methodology that evaluates system efficiency at both **national** and **hospital-health system (HHS)** levels.  

1. **Stage 1 – Data Envelopment Analysis (DEA)**  
   - Computes monthly **national-level efficiency scores** for **five countries** based on country-level panel data.  
   - DEA identifies the **efficiency frontier** — the boundary of maximum achievable output given a set of inputs.  
   - The resulting **national efficiency scores** are used as contextual inputs in Stage 2.

2. **Stage 2 – Stochastic Frontier Analysis (SFA)**  
   - Applies SFA at the **HHS level** (hospital or health system level).  
   - Evaluates efficiency across **64 model configurations**, accounting for variations in specifications and covariates.  
   - Adjusts for both **Stage 1 national efficiency scores** and **city-level response stringency**, allowing a multi-level understanding of system performance.

---

## 🧠 Methodological Framework

The 2-FB framework integrates **deterministic** and **stochastic** efficiency modeling:

| Stage | Method | Level | Output | 
|--------|---------|--------|----------|
| 1 | Data Envelopment Analysis (DEA) | Country | Monthly national efficiency scores | 
| 2 | Stochastic Frontier Analysis (SFA) | HHS | Hospital-level efficiency estimates | 

---

## 📊 Data Description

- **Time Period:** January 2020 – June 2021 (18 months)  
- **Geographic Coverage:** Five Asian countries  
- **Levels of Analysis:**
  - **National (Stage 1)**: Country-level inputs and outputs  
  - **HHS (Stage 2)**: Hospital-level data across 64 model specifications  

---

## 🧾 Citation

If you use this repository or adapt the 2-FB framework, please cite the following study:

> **Comparative Efficiency of Asian Surgical Systems in COVID-19 Response: A Multi-Level Longitudinal Benchmarking Study**  
> S. S. W. Lam, A. Kumar, Y. Ge, S. L. Chan, A. Pourghaderi, M. W. W. Zaw, A. Z. Khan, A. C. Roslani, C. Selvakumaran, R. Jarmin, D. H. Ngoc, D. K. Sari, D. Dey, D. N. T. Ngoc, D. D. Tan, D. N. V. Minh, F. Raduan, G. V. Son, H. Le, I. N. D. Lubis, K. Khalid, K. Nawawi, J. K. Koong, L. T. Meetei, M. Fatima, M. Fahdy, M. Ichwan, N. Sinam, N. S. Singh, N. Kania, N. Goswami, N. C. Borah, P. W. Nurikhwan, P. M. Yen, P. Sarkar, T. B. Duc, T. D. P. Nguyet, T. N. Van, V. T. Quoc, G. Z. Chen, V. Rao, P. K. H. Chow, and H. K. Tan, “Comparative Efficiency of Asian Surgical Systems in COVID-19 Response: A Multi-Level Longitudinal Benchmarking Study,” BMJ Public Health, submitted for publication, 2025.
> Submitted to *BMJ Public Health*.

---

## 📜 License

This repository is distributed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.
