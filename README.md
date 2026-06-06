# 🏥 Northlake Healthcare Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![DAX](https://img.shields.io/badge/DAX-30%2B%20Measures-blue)
![Healthcare](https://img.shields.io/badge/Industry-Healthcare-green)
![Status](https://img.shields.io/badge/Project-Complete-success)

A Power BI healthcare analytics project analyzing clinical performance, patient outcomes, operational efficiency, and financial sustainability across six Canadian provinces.

---

## 📷 Dashboard Preview

![Northlake Healthcare Dashboard](images/dashboard1.png)

---

## 📌 Project Overview

Northlake Healthcare experienced significant growth between 2021 and 2025, with patient encounters increasing by **83%**. Despite this growth, the organization faced rising readmission rates, declining treatment outcomes, escalating costs, insurance claim denials, and physician workload imbalance.

This project delivers a **4-page executive Power BI dashboard** designed to help healthcare leaders identify root causes, prioritize interventions, and improve both clinical and financial performance.

---

## 📊 Executive Summary

| KPI | Value |
|------|------|
| Patient Encounters | 3,830 |
| Encounter Growth | 83% |
| Readmission Rate | 15.09% |
| Treatment Success Rate | 67% |
| Cost Growth | 88% |
| Claim Denial / Dispute Rate | 11.4% |
| Revenue Recovery Opportunity | $373K |
| Provinces Analyzed | 6 |
| Physicians Analyzed | 25 |

---

## 🎯 Business Problem

Leadership needed a centralized analytics solution to answer key operational and financial questions:

- Why are readmission rates remaining high?
- Which medical units are driving cost increases?
- Where are insurance claims being denied or disputed?
- Which physicians are carrying the highest workload?
- How should resources be allocated across provinces?

---

## 🧩 Dashboard Pages

| Dashboard Page | Focus Area |
|---|---|
| Healthcare Overview | Encounters, readmissions, wait times, discharge outcomes |
| Clinical Performance | Treatment success, disease trends, physician workload |
| Patient Demographics | Age groups, insurance type, province demand, risk profile |
| Financial Performance | Cost trends, claims, procedure costs, insurer performance |

---

## 🚨 Key Findings

### Clinical Performance

- Readmission rate remained high at **15.09%**
- Treatment success rate was only **67%**
- 1 in 3 patients did not achieve full recovery
- Knee Replacement recorded the highest disease encounter volume
- Oncology, Cardiovascular, and Orthopedics showed major performance pressure

### Physician Workload

- Dr. Chen handled **93 cases**
- Dr. Brown handled **92 cases**
- Both physicians carried almost double the average workload, creating burnout and quality-of-care risks

### Financial Performance

- Total costs increased by **88%**
- Encounter volume increased by **83%**
- Cost growth outpaced patient volume growth
- **11.4%** of claims were disputed or denied
- **$373K** in recoverable revenue was identified

### Patient Demographics

- Ontario accounted for **39%** of all encounters
- Ontario and Quebec represented more than **60%** of total demand
- Patients aged **18–35** represented the largest patient group

---

## 🔍 Root Cause Analysis

| Root Cause | Business Impact |
|---|---|
| High readmission rate | Increased cost per encounter and reduced care effectiveness |
| Physician workload imbalance | Burnout risk and possible decline in patient care quality |
| Claim denials and disputes | Revenue leakage and delayed cash recovery |
| Provincial demand concentration | Resource allocation mismatch across regions |
| Procedure-level cost pressure | Rising operating costs and margin pressure |

---

## 💡 Strategic Recommendations

### 1. Clinical Care Improvement

- Implement structured post-discharge follow-up
- Launch a 30-day readmission review board
- Audit partially successful treatment outcomes
- Prioritize Oncology, Cardiovascular, and Knee Replacement patients

### 2. Doctor Workload Rebalancing

- Redistribute caseloads across medical teams
- Cap physician workload at 1.3x team average
- Add or rotate physicians into high-pressure units
- Monitor workload through quarterly dashboards

### 3. Insurance Claim Recovery

- Introduce pre-authorization checks for high-value procedures
- Assign a dedicated claims resolution contact
- Focus on insurers with lower approval rates
- Reduce disputed and denied claims below 6%

### 4. Province-Based Capacity Expansion

- Prioritize Ontario and Quebec for staffing and capacity investment
- Launch prevention programs for the 18–35 age group
- Align resources with actual province-level patient demand

---

## 🎯 6–12 Week Recovery Targets

| Metric | Target |
|---|---|
| Readmission Rate | Reduce from 15.09% to 12% |
| Claim Denial Rate | Reduce from 11.4% to below 8% |
| Doctor Workload | Rebalance top 2 physicians within 8 weeks |
| Revenue Recovery | Recover $186K of disputed claims |
| Treatment Success | Improve from 67% to 72% |
| Wait Time | Maintain below 16 days |

---

## 🏗️ Data Model

The project uses a synthetic healthcare dataset designed to reflect realistic Canadian healthcare operations.

| Dataset | Description |
|---|---|
| Fact_Encounters | 3,830 patient encounters linking all dimensions |
| Dim_Patients | 300 patients with demographics, risk profile, and insurance type |
| Dim_Doctors | 25 physicians across 11 medical units |
| Dim_Medical_Units | 11 units including Orthopedics, Oncology, Cardiovascular, and Mental Health |
| Dim_Diseases | 10 conditions including Knee Replacement, Lung Cancer, Pneumonia, and Type 2 Diabetes |
| Dim_Insurance | 8 insurers including OHIP, Manulife, Sun Life, RAMQ, and Veterans Affairs Canada |
| Dim_Province | 6 Canadian provinces |
| Dim_Date | Date intelligence table covering 2021–2025 |

---

## 🛠️ Tools & Technologies

| Layer | Tool |
|---|---|
| Data Source | Synthetic 23-table healthcare dataset |
| Data Preparation | Microsoft Excel, Power Query |
| Data Modeling | Power BI Desktop, Star Schema |
| Calculations | DAX, Time Intelligence, YoY Measures |
| Visualization | Power BI |
| Analytics | KPI Analysis, Root Cause Analysis, Segmentation |

---

## 📈 Business Impact

This dashboard helped identify:

- **$373K** in recoverable insurance revenue
- Readmission rate **51% above benchmark**
- Physician workload imbalance across high-pressure units
- Cost growth exceeding encounter growth
- Ontario and Quebec as the highest-demand provinces
- Priority areas for clinical, financial, and operational improvement

---

## 📷 Dashboard Screenshots

### Healthcare Overview

![Healthcare Overview](images/dashboard1.png)

### Clinical Performance

![Clinical Performance](images/dashboard2.png)

### Patient Demographics

![Patient Demographics](images/dashboard3.png)

### Financial Performance

![Financial Performance](images/dashboard4.png)

---

## ✅ What This Project Demonstrates

- End-to-end Power BI dashboard development
- Healthcare data analysis and KPI reporting
- DAX measure creation
- Power Query data transformation
- Star schema data modeling
- Executive-level data storytelling
- Root cause analysis
- Financial performance analysis
- Strategic recommendation development

---

## 📁 Repository Structure

```text
Northlake-Healthcare-Analytics/
│
├── README.md
├── Northlake-Healthcare-Dashboard.pbix
├── Northlake-Healthcare-Dataset.xlsx
│
├── images/
│   ├── dashboard1.png
│   ├── dashboard2.png
│   ├── dashboard3.png
│   └── dashboard4.png
