# Insurance Claims Profitability & Risk Analysis

## Identifying the Primary Drivers of Poor Portfolio Profitability

### Author

**Ajnur Sivac**

Master of Science in Data Science

---

# Project Overview

This project analyzes an insurance claims portfolio to identify the primary factors driving poor financial performance and determine where operational intervention would have the greatest business impact.

Using SQL within a Jupyter Notebook, the project integrates insurance claims, employee (agent), and vendor datasets into a unified analytical model. The analysis evaluates portfolio profitability, customer risk, insurance products, claim characteristics, operational performance, and financial exposure while demonstrating advanced SQL techniques commonly used in the insurance and healthcare industries.

Python is used only to establish the DuckDB connection, load the datasets, and visualize SQL query results. All analytical transformations and business logic are written in SQL.

---

# Business Problem

Insurance companies process thousands of claims across multiple products, customers, agents, and vendors.

Poor portfolio profitability may result from numerous interacting factors, including:

* High-loss insurance products
* Ineffective customer risk segmentation
* Large-loss claims
* Claim severity
* Delayed reporting
* Operational inefficiencies
* Vendor performance
* Agent portfolio composition

Without understanding these drivers, organizations cannot effectively improve underwriting performance or reduce financial exposure.

---

# Central Business Question

### Which factors are driving poor profitability in the insurance claims portfolio, and where should the company intervene first?

---

# Project Objectives

* Evaluate overall portfolio profitability
* Identify products with the highest financial exposure
* Measure customer risk performance
* Analyze claim severity and reporting behavior
* Evaluate policy age at loss
* Benchmark agent portfolios
* Benchmark vendor performance
* Analyze monthly claim trends
* Measure claim concentration
* Build an explainable claim intervention model
* Provide executive-level business recommendations

---

# Project Workflow

```
Insurance Claims Data
        │
        ▼
Employee Data
        │
        ▼
Vendor Data
        │
        ▼
───────────────────────────────
Data Validation
───────────────────────────────
        │
        ▼
Data Cleaning & Standardization
        │
        ▼
Relational SQL Joins
        │
        ▼
Feature Engineering
        │
        ▼
Portfolio KPI Development
        │
        ▼
Profitability Analysis
        │
        ▼
Customer Risk Analysis
        │
        ▼
Claim Characteristics Analysis
        │
        ▼
Monthly Trend Analysis
        │
        ▼
Agent Performance Analysis
        │
        ▼
Vendor Performance Analysis
        │
        ▼
Claim Concentration Analysis
        │
        ▼
Claim Intervention Model
        │
        ▼
Executive Business Recommendations
```

---

# Dataset Information

The project combines three datasets.

### Insurance Claims

Contains claim transactions, policy information, customer demographics, claim status, premiums, claim amounts, incident characteristics, and reporting information.

### Employee Data

Contains insurance agent information including identifiers, names, state, and employment details.

### Vendor Data

Contains vendor identifiers, vendor names, and vendor location information.

---

# Technologies Used

* SQL
* DuckDB
* Jupyter Notebook
* Python
* Pandas
* Matplotlib

---

# SQL Skills Demonstrated

* SELECT
* WHERE
* CASE Statements
* Aggregate Functions
* GROUP BY
* ORDER BY
* INNER JOIN
* LEFT JOIN
* Common Table Expressions (CTEs)
* Window Functions
* DENSE_RANK()
* ROW_NUMBER()
* LAG()
* Date Functions
* Feature Engineering
* Financial KPI Development
* Risk Segmentation
* Data Validation
* Data Cleaning

---

# Analytical Techniques

* Portfolio Analysis
* Insurance Profitability Analysis
* Financial KPI Analysis
* Customer Segmentation
* Operational Performance Analysis
* Trend Analysis
* Large-Loss Analysis
* Claim Prioritization
* Executive Reporting

---

# Key Metrics

* Approved Claim Cost
* Underwriting Margin Proxy
* Loss Ratio Proxy
* Claim-to-Premium Ratio
* Reporting Delay
* Policy Age at Loss
* Denial Rate
* Average Claim Amount
* Median Claim Amount
* Claim Intervention Score

---

# Visualizations

The notebook includes executive-level visualizations that summarize the primary findings of the analysis.

* Loss Ratio by Insurance Product
* Customer Risk Segment Performance
* Monthly Approved Claim Costs
* Claim Intervention Priority Distribution

---

# Key Findings

* Insurance products demonstrate varying levels of financial performance and loss ratios.
* Customer risk segmentation contributes to differences in claim costs and financial exposure.
* Large claims account for a significant portion of total portfolio losses.
* Claim severity, reporting delay, and policy age influence profitability.
* Agent and vendor scorecards identify portfolios requiring additional review.
* An explainable intervention model prioritizes claims requiring human investigation.

---

# Business Recommendations

* Review pricing strategies for products with the highest loss ratios.
* Strengthen underwriting guidelines for high-risk portfolios.
* Improve customer risk segmentation using additional historical variables.
* Expand monitoring of agent and vendor performance.
* Prioritize high-risk claims for specialized review.
* Enhance claim documentation and reporting processes.
* Incorporate additional financial variables such as policy limits, reserves, earned premium, and reinsurance into future profitability models.

---

# Repository Structure

```
Insurance-Claims-Profitability-Analysis
│
├── README.md
├── requirements.txt
├── insurance_claims_profitability_analysis.ipynb
├── insurance_data.csv
├── employee_data.csv
├── vendor_data.csv
│
└── images
    ├── loss_ratio_by_product.png
    ├── customer_risk_segment.png
    ├── monthly_claim_costs.png
    └── intervention_priority.png
```

---

# Future Enhancements

Future versions of this project may include:

* Power BI dashboard
* Tableau dashboard
* Predictive machine learning models
* Fraud detection modeling
* Geographic claim analysis
* Interactive SQL dashboards
* Automated reporting pipeline

---

# About the Author

**Ajnur Sivac**

Master of Science in Data Science

Healthcare Data Analytics | Business Intelligence | SQL | Python | DuckDB | Power BI

Passionate about transforming complex data into actionable business insights through analytics, statistical thinking, and data-driven decision making.

