# 🏦 AI Fraud Detection — Regulatory Compliance Mapper

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOURUSERNAME/7cs525-fraud-ai-compliance/blob/main/AI_Fraud_Compliance_Mapper.ipynb)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Framework](https://img.shields.io/badge/Framework-EU%20AI%20Act%20%7C%20UK%20AI%20White%20Paper-red)
![Module](https://img.shields.io/badge/Module-7CS525-navy)
![License](https://img.shields.io/badge/License-MIT-green)

> **7CS525 Human and Legal Aspects of Cyber Security**  
> University of Derby 2025/26 — Component 5 Automation Artefact

---
## 🚀 Run It Instantly

Click the badge above — no setup, no installation. Opens directly in Google Colab.

Or run locally:

```bash
git clone https://github.com/YOURUSERNAME/7cs525-fraud-ai-compliance
cd 7cs525-fraud-ai-compliance
pip install -r requirements.txt
jupyter notebook AI_Fraud_Compliance_Mapper.ipynb
```

---

## 📊 What the Notebook Generates

| Output | Description |
|--------|-------------|
| `eu_ai_act_requirements_graph.png` | NetworkX graph of all applicable EU AI Act articles and their relationships |
| `risk_heatmap.png` | 5×5 Likelihood × Impact matrix with 10 risks plotted |
| `uk_ai_whitepaper_gap_analysis.png` | Compliance status across all 5 UK AI White Paper principles |
| `risk_register.html` | Interactive Plotly risk register table |
| `regulatory_obligations.png` | Regulatory obligations by priority and deadline |

---

## 🔴 System Assessment Result

| Metric | Result |
|--------|--------|
| **EU AI Act Classification** | 🔴 **HIGH RISK** — Annex III §5(b) |
| **UK AI White Paper Gaps** | 3/5 principles have compliance gaps |
| **Critical Risks** | 3 (score ≥ 16) |
| **High Risks** | 4 (score 12–15) |
| **Regulations Mapped** | 7 |
| **EU AI Act Deadline** | August 2026 |

---

## 🗺 System Under Analysis

**AI-Driven Transaction Fraud Detection System** — UK Retail Banking

A real-time ML system (Gradient Boosting + Neural Network ensemble) that scores every incoming payment transaction, automatically blocking or flagging suspicious ones. Processes ~50,000 transactions/day affecting millions of retail banking customers.

---

## 📋 Regulatory Frameworks Covered

- **EU AI Act (2024)** — Annex III §5(b) High-Risk classification; Articles 9–17 obligations
- **UK AI White Paper (2023)** — Five cross-sector principles gap analysis
- **UK GDPR** — Article 22 (automated decisions); Articles 13–14 (transparency)
- **FCA Consumer Duty (PS22/9)** — Good customer outcomes
- **Equality Act 2010** — Section 19 indirect discrimination
- **NIS2 / NCSC ML Guidelines** — Pipeline security

---

## 📁 Repository Structure

```
7cs525-fraud-ai-compliance/
├── AI_Fraud_Compliance_Mapper.ipynb   ← Main notebook (run this)
├── requirements.txt                   ← Python dependencies
└── README.md                          ← This file
```

---

## 🎓 Academic Context

**Module:** 7CS525 Human and Legal Aspects of Cyber Security  
**Programme:** MSc Cybersecurity, University of Derby  
**Component:** 5 — Automation Artefacts (15% weighting)

**Why this is relevant:** EU AI Act Article 9 mandates a documented risk management system throughout the AI lifecycle. This notebook operationalises that requirement — producing a reproducible, auditable compliance assessment. The requirements graph makes the relationships between obligations visible in a way that static text cannot, directly supporting Components 1 and 3 of the portfolio.

---

*This repository is an academic artefact. Not legal advice.*
