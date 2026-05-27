---
layout: default
---

# Rachel Chung, PA-C
**Healthcare Data Builder · Clinical AI · Real-World Evidence**

Physician Assistant with surgical clinical experience, building scalable data pipelines and AI-augmented workflows for healthcare. I bring something most data engineers don't have: I understand how healthcare actually operates at the point of care — the sequencing, the stakes, the documentation, and the data it generates.

I build with Python, SQL, and PostgreSQL, and use LLMs (Claude, GPT-4) as core development tools — not shortcuts, but force multipliers for producing better, faster-iterated work.

---

## Featured Project

### NHANES Biomarker Analysis Pipeline
**End-to-end healthcare data pipeline · PostgreSQL · Python · Real-World Evidence**

A reusable epidemiological analysis system built on the NHANES 2017–2020 Pre-Pandemic dataset — one of the most comprehensive population-level health surveys available.

**What I built:**
- Automated ingestion of 46 NHANES laboratory tables into a structured PostgreSQL database
- Long-table architecture with a `biomarker_registry` mapping 345 biomarkers from raw NHANES codes to human-readable names — so new analyses require configuration, not rewriting code
- Reusable analysis functions (correlation, linear/logistic regression, quartile analysis) that accept any biomarker and disease combination via a config file
- Clinically grounded cohort definitions based on ACC/AHA, WHO, and ADA guidelines
- Three complete analyses: urine biomarkers vs. BMI (n=2,898), carbohydrate metabolism vs. BMI (n=3,478), SHBG vs. BMI in males 22–49 (n=1,387)

**What makes it different:** Most NHANES analyses are one-off scripts. This is a system — built to scale across any biomarker, any disease, any cohort filter without touching the underlying architecture.

**Stack:** Python · PostgreSQL · SQLAlchemy · pandas · statsmodels · seaborn · pyreadstat · LLM-augmented development

[View Pipeline & Documentation](https://github.com/eudorach/portfolio_ds_projects/blob/main/NHANES_analysis/pipeline/README.md)

---

## Skills

| | |
|---|---|
| **Clinical Domain** | Surgical medicine, perioperative workflows, procedural and CPT coding, point-of-care clinical decision-making |
| **Data Engineering** | PostgreSQL, long-table architecture, automated ingestion pipelines, modular reusable code |
| **Analysis** | Pearson correlation, linear & logistic regression, odds ratios, covariate adjustment |
| **Python** | pandas, SQLAlchemy, statsmodels, seaborn, pyreadstat |
| **AI-Augmented Workflow** | Daily use of Claude and GPT-4 for code generation, iteration, and QA |

---

*Building at the intersection of surgical medicine and data engineering.*
