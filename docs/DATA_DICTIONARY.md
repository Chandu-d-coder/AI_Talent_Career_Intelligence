# Data Dictionary

This document describes all variables used in the **AI Talent & Career Intelligence Platform** dataset.

---

# Dataset Overview

| Property | Value |
|----------|-------|
| Dataset Name | Global AI & Data Science Job Market |
| Total Records | 90,000 |
| Total Features | 35 |
| Data Type | Structured Tabular Data |
| Format | CSV |
| Primary Language | English |

---

# Column Definitions

| Column Name | Data Type | Description |
|------------|-----------|-------------|
| `id` | Integer | Unique identifier for each job record. |
| `country` | Categorical | Country where the AI job opportunity is located. |
| `job_role` | Categorical | Job title or role offered by the organization. |
| `ai_specialization` | Categorical | Primary AI domain associated with the role (e.g., NLP, Computer Vision, LLM). |
| `experience_level` | Categorical | Experience category (Entry, Mid, Senior, Lead). |
| `experience_years` | Integer | Total years of professional experience required. |
| `salary_usd` | Numeric | Annual base salary in US Dollars. |
| `bonus_usd` | Numeric | Annual bonus compensation in US Dollars. |
| `education_required` | Categorical | Minimum educational qualification required. |
| `industry` | Categorical | Industry sector employing AI professionals. |
| `company_size` | Categorical | Organization size classification (Small, Medium, Large). |
| `interview_rounds` | Integer | Number of interview rounds during recruitment. |
| `year` | Integer | Year associated with the job record. |
| `work_mode` | Categorical | Employment mode (Remote, Hybrid, Onsite). |
| `weekly_hours` | Numeric | Average working hours per week. |
| `company_rating` | Numeric | Overall company rating on a 0–5 scale. |
| `job_openings` | Integer | Number of available openings for the role. |
| `hiring_difficulty_score` | Numeric | Score indicating recruitment difficulty (0–100). |
| `layoff_risk` | Numeric | Estimated probability of layoffs (0–1). |
| `ai_adoption_score` | Numeric | Organization's AI adoption maturity score (0–100). |
| `company_funding_billion` | Numeric | Company funding expressed in billions of US Dollars. |
| `economic_index` | Numeric | Country-level economic performance indicator. |
| `ai_maturity_years` | Numeric | Years of AI adoption within the organization. |
| `offer_acceptance_rate` | Numeric | Percentage of job offers accepted by candidates. |
| `tax_rate_percent` | Numeric | Estimated income tax percentage. |
| `vacation_days` | Integer | Annual paid vacation days offered. |
| `skill_demand_score` | Numeric | Market demand score for required technical skills (0–100). |
| `automation_risk` | Numeric | Estimated probability of job automation (0–100). |
| `job_security_score` | Numeric | Overall employment stability score (0–100). |
| `career_growth_score` | Numeric | Long-term career advancement score (0–100). |
| `work_life_balance_score` | Numeric | Employee work-life balance score (0–100). |
| `promotion_speed` | Numeric | Promotion progression score (0–100). |
| `salary_percentile` | Numeric | Salary percentile within the overall workforce. |
| `cost_of_living_index` | Numeric | Cost of living index for the job location. |
| `employee_satisfaction` | Numeric | Employee satisfaction score (0–100). |

---

# Data Type Summary

| Type | Columns |
|------|---------|
| Integer | `id`, `experience_years`, `interview_rounds`, `year`, `job_openings`, `vacation_days` |
| Numeric | `salary_usd`, `bonus_usd`, `weekly_hours`, `company_rating`, `hiring_difficulty_score`, `layoff_risk`, `ai_adoption_score`, `company_funding_billion`, `economic_index`, `ai_maturity_years`, `offer_acceptance_rate`, `tax_rate_percent`, `skill_demand_score`, `automation_risk`, `job_security_score`, `career_growth_score`, `work_life_balance_score`, `promotion_speed`, `salary_percentile`, `cost_of_living_index`, `employee_satisfaction` |
| Categorical | `country`, `job_role`, `ai_specialization`, `experience_level`, `education_required`, `industry`, `company_size`, `work_mode` |

---

# Business Domains Covered

The dataset supports analytics across six workforce intelligence domains:

1. Salary Intelligence
2. Career Growth Intelligence
3. Workforce Risk Intelligence
4. Talent Market Intelligence
5. Employee Experience Intelligence
6. Recruitment Intelligence

---

# Feature Categories

## Employee Profile

- Country
- Job Role
- AI Specialization
- Experience Level
- Experience Years
- Education Required

---

## Compensation

- Salary
- Bonus
- Salary Percentile
- Tax Rate

---

## Organization

- Industry
- Company Size
- Company Rating
- Company Funding

---

## Workforce

- AI Adoption
- AI Maturity
- Job Security
- Layoff Risk
- Automation Risk

---

## Career Development

- Career Growth
- Promotion Speed

---

## Recruitment

- Job Openings
- Hiring Difficulty
- Interview Rounds
- Offer Acceptance Rate

---

## Employee Experience

- Employee Satisfaction
- Work-Life Balance
- Weekly Hours
- Vacation Days

---

## Economic Indicators

- Economic Index
- Cost of Living Index

---

# Data Quality Notes

The dataset was validated before analysis through the following steps:

- Missing value inspection
- Duplicate record detection
- Data type validation
- Numerical range validation
- Categorical consistency checks
- Outlier assessment
- Business rule verification

---

# Analytical Usage

This dataset was used for:

- Descriptive Analytics
- Segmentation Analytics
- Statistical Analysis
- Correlation Analysis
- Feature Engineering
- Business Intelligence
- Executive Reporting
- Strategic Workforce Analytics

---

# Engineered Features

The following custom metrics were created during the project:

- Total Compensation
- Career Momentum Score
- Workforce Stability Index
- Talent Demand Index
- Employee Experience Index
- Recruitment Success Index
- Candidate Attraction Score
- Hiring Efficiency Score
- Market Opportunity Index
- Skill Premium Index

These engineered features were developed specifically to support advanced workforce analytics and executive decision-making.

---
