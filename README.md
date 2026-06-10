
---

**TeleClinic Platform — Month 3 Learning Review**
*Data Analyst & MEL Associate Assessment | Clemence Ingabire*

---

**Project Overview**

This repository contains the full analysis for the TeleClinic Platform Month 3 Learning Review, prepared for the Clinical Governance Committee and Gates Foundation quarterly reporting call. The analysis covers 1,200 registered patients across 12 Rwandan districts over a three-month period (February to April 2026) and assesses platform performance across data quality, clinical metrics, equity, and patient safety.

---

**Repository Structure**

```
├── irembo.ipynb          # Main analysis notebook
├── README.md             # This file
├── dashboard/            # Clinical Governance Dashboard screenshot
├── written_responses/    # Parts 1-5 and Reflection as PDF
```

---

**Tools Used**
- Python (pandas, numpy, matplotlib, seaborn)
- Jupyter Notebook

---

**Key Findings**

- 491 of 1,200 registered patients (40.9%) never accessed any clinical service, making the platform's true active reach 709 patients
- 62 lab results were uploaded but never reviewed by the ordering clinician, including 21 Malaria RDTs and 2 HIV tests
- Musanze recorded the lowest consultation volume (21 patients) and lowest conversion rate (28.6%) with standard explanations ruled out by the data
- The urban/rural classification is coded at province level making it analytically misleading for equity analysis
- Insurance validation failure is a direct access barrier — unvalidated patients consulted at 0% versus 71.8% for validated patients

---

**How to Run**

1. Clone the repository
2. Place the TeleClinic dataset Excel file in the same directory as the notebook
3. Install dependencies:
```
pip install pandas numpy matplotlib seaborn jupyter
```
4. Open and run irembo.ipynb from top to bottom

---

**Data**

The dataset is synthetic and was provided as part of the assessment. It is not included in this repository for confidentiality reasons. The workbook contains eight tabs: Patients, Consultations, Follow-Ups, Lab Tests, Prescriptions, Referrals, Insurance Log, and Data Dictionary.

---

**Assessment Structure**

| Part | Topic | Points |
|---|---|---|
| Part 1 | Data Quality Audit | 20 |
| Part 2 | Metrics and Analysis | 25 |
| Part 3 | Equity Analysis | 20 |
| Part 4 | Dashboard Design | 20 |
| Part 5 | Learning Review Brief | 15 |
| Reflection | North Star Metric | Unscored |

---

**Process Note**

The analysis prioritised data quality and join integrity first, as these findings underpinned every subsequent part. Null values were retained rather than dropped where they carried clinical or structural meaning. All clinical metrics use 709 active patients as the denominator rather than 1,200 registered patients. The urban/rural variable was excluded from equity analysis and replaced with district-level disaggregation. Full process notes are included in the written responses document. .pr.

---

**Contact**

Clemence Ingabire
cingabir@alumni.cmu.edu
linkedin.com/in/clemence-ingabire-ai-engineer# Irembo_Teleclinic