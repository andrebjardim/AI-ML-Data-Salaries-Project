# Market Analysis of In-Office Salary Trends in AI, Data, and Machine Learning (US, CA, UK)

![Dashboard Screenshot](https://github.com/andrebjardim/AI-ML-Data-Salaries-Project/blob/main/Dashboard.png)

*Interactive dashboard for salary insights, talent benchmarking, and market trends (2020–2024).*

---

## Executive Summary

Gain an edge in hiring or negotiation: This project delivers clear, data-driven salary benchmarks for in-office AI, Data, and Machine Learning roles, focusing on the US, Canada, and UK.  
**Key findings:** Executive and specialist roles command the highest pay; US leads the market; large firms and experience drive compensation higher.  
_Explore the dashboard above or dive into the code for full transparency._

---

## Project Overview

- **Goal:** Provide actionable compensation insights for HR, hiring managers, analysts, and job seekers in AI/Data/ML fields.
- **Approach:**  
  - Rigorous data cleaning, outlier handling, and aggregation for reliability  
  - Focused on in-office, full-time roles (remote/hybrid excluded for clarity)
  - Clear, visual storytelling with Tableau & Python  
- **Outcome:** Ready-to-use benchmarks for negotiation, budgeting, and talent strategy.

---

## Key Insights

- **Executives and specialists (e.g., Head of Data, AI Product Manager) earn the highest median salaries.**
- **US roles pay 27%+ more than UK and Canada at median.**
- **Large firms pay $34K more than medium-sized ones, at median.**
- **Seniority matters:** Executives earn 2x more than entry-level roles; career progression pays.

---

## Dataset & Methodology

- **Data Source:** [AIJobs.net](https://aijobs.net) salary dataset, 2020–2024 (CC0 licensed)
- **Scope:** 59,325 records → 44,733 in-office, full-time jobs (US, CA, UK) after filtering  
- **Aggregation:**  
  - Aggregated by job title, experience, year, location, and company size  
  - Only groups with ≥3 survey responses are considered “statistically stable”
- **Cleaning:**  
  - Duplicates and outliers handled to ensure robust analysis  
  - All data and code available for reproducibility

---

## Project Structure

- **Jupyter Notebook:** End-to-end analysis, data prep, and reproducible code  
  [`ai_ml_data_salaries_project.ipynb`](ai_ml_data_salaries_project.ipynb)
- **Dashboard:** Interactive Tableau (see screenshot above)
- **Data:**  
  - `Data/salaries.csv` (raw, as provided)  
  - `salary_groups.csv` (aggregated, for Tableau/dashboard)  
- **Docs:** Methodology, insights, and appendix

---

## How to Use

1. **Explore the Dashboard:** See key salary benchmarks at a glance
2. **Run the Notebook:** Full code & step-by-step reproducibility
3. **Re-use the Data:** All cleaned/aggregated data provided (see `/Data` folder)

---

## Example Insights

> - **Head of Data**: $232K median salary (highest in market)
> - **US, In-Office, Executive**: $180K+ median salary  
> - **Career Progression**: Executive roles pay 2x more than Entry level  
> - **Large vs. Medium Companies**: +$34K at median for large firms

---

## 📮 Contact

**André Jardim**  
Data Analyst | Portfolio: [GitHub](https://github.com/andrebjardim) 
[LinkedIn](https://linkedin.com/in/andrebjardim)

---

*This project is open-source, fully reproducible, and designed for real-world business impact. Feel free to fork, use, or reference!*
