# QuickLoan Mobile — Ethical Data Governance Review

## Project Overview

This repository contains a comprehensive data governance review for QuickLoan Mobile, a fintech startup offering instant micro-loans via a mobile app in Ghana.

As an **Independent Data Governance Consultant**, I identified critical risks in their data pipeline and proposed practical, compliant solutions aligned with **Ghana's Data Protection Act (Act 843)**.

---

## Deliverables

| # | Deliverable | Description |
|---|-------------|-------------|
| 1 | **Governance Review Card** | Risk analysis covering Data Quality, Legal Compliance, and Algorithmic Fairness |
| 2 | **Corrected Data Flow Diagram** | Annotated corrections to the flawed data pipeline |
| 3 | **Summary Essay** | 200-300 word explanation of review methodology |

---

## Key Findings

### 🔴 Risks Identified
- **Data Quality:** Incomplete/inconsistent customer records affecting ML model accuracy
- **Legal Compliance:** Excessive data collection without explicit consent (violates Act 843)
- **Algorithmic Bias:** No demographic monitoring on automated loan decisions

### 🟢 Solutions Proposed
- Schema validation at API Gateway
- Consent capture gate before data storage
- Data classification (Sensitive tier) with encryption
- **DARD Metric** — Demographic Approval Rate Disparity monitoring

---

## Proposed Metric: DARD

**Demographic Approval Rate Disparity (DARD)**

```
DARD = Approval Rate (highest group) − Approval Rate (lowest group)
```

- Calculated monthly across all automated decisions
- Threshold: Flag if DARD exceeds 10 percentage points
- Visualization: Grouped Bar Chart

---

## Technologies & Frameworks

- Ghana Data Protection Act (Act 843)
- Data Minimization Principles
- SHAP (Model Explainability)
- Role-Based Access Control (RBAC)

---

## Author

**Illona** — Data Governance Consultant

---

## License

This project is for educational purposes as part of the AmaliTech program.