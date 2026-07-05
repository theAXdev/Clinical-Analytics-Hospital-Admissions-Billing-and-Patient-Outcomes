# 🏥 Clinical Analytics — Hospital Admissions, Billing & Patient Outcomes

> A Microsoft Excel analytics project investigating hospital admissions, patient demographics, billing patterns, and clinical outcomes across 55,500 patient records from 10 major U.S. hospitals between 2019 and 2024. Built with Pivot Tables, calculated fields, conditional formatting, and an interactive dashboard with slicers — delivering actionable clinical and operational intelligence for hospital administrators, capacity planners, and healthcare policy stakeholders.

---

<img width="1389" height="885" alt="BR_Clinical_Analytics_Dashboard" src="https://github.com/user-attachments/assets/7b172ca9-8d98-42e6-a628-8fe996a26422" />


---

## 📌 Project Background

Healthcare analytics has become one of the most strategically important applications of data science. Hospital administrators, clinical directors, and health policy makers increasingly rely on data-driven intelligence to optimise capacity planning, reduce patient wait times, identify high-risk population segments, and manage the financial sustainability of healthcare delivery.

This project applies structured analytical methodology to 55,500 patient admission records from the **Lifewell General Hospital network** — a consortium of ten nationally recognised U.S. hospitals spanning eight states. The analysis moves from raw admission data through Pivot Table construction, calculated field design, and conditional formatting to a fully interactive Excel dashboard — producing clinical and operational insights directly applicable to hospital management, capacity planning, and patient care strategy.

The project demonstrates healthcare data literacy — the ability to work with sensitive, multi-field clinical datasets using Excel analytics tools — and targets data analyst roles in NHS analytics teams, private healthcare operators, health tech firms, and life sciences organisations.

---

## 🎯 Project Objectives

- Identify the most prevalent medical conditions across the hospital network and their distribution by patient demographics
- Analyse patient age distribution and determine which age cohorts drive the highest admission volumes
- Examine gender distribution across all six medical conditions to identify demographic risk patterns
- Profile blood type distribution and its relationship to medical condition prevalence
- Investigate the three admission types (Elective, Urgent, Emergency) and their distribution
- Analyse test result patterns (Normal, Abnormal, Inconclusive) across conditions and patient groups
- Track admission volume trends over time (2019–2024) to identify year-on-year growth patterns and anomalies
- Examine geographic distribution across U.S. states and hospital facilities
- Profile billing amounts across conditions, hospitals, and insurance providers

---

## ⚙️ Tools & Techniques

| Tool | Role in This Project |
|---|---|
| **Microsoft Excel** | Full analysis environment — data preparation, Pivot Tables, calculated fields, dashboard |
| **Pivot Tables** | Aggregating patient counts by condition, age, gender, blood type, hospital, and time period |
| **Calculated Fields** | Days of Admission (Discharge Date − Admission Date), State (derived from hospital name) |
| **Conditional Formatting** | Highlighting key patterns across medical condition and billing distributions |
| **Data Visualisations** | Bar charts, pie charts, donut charts, line chart, map visual, KPI cards |
| **Slicer Controls** | Interactive filtering by Medical Condition, Gender, Hospital, State, Date of Admission |
| **Map Visual** | U.S. state-level geographic distribution using hospital latitude and longitude coordinates |

---

## 📊 Key Metrics at a Glance

| Metric | Value |
|---|---|
| Total Patient Records | 55,500 |
| Total Billing Revenue | $1.42 Billion |
| Average Billing Amount | $25,539 per admission |
| Average Days of Admission | 16 days |
| Most Common Medical Condition | Hypertension — 13,875 patients |
| Most Admitted Age Group | 51–60 — 8,297 patients |
| Most Common Blood Type | A+ — 19,425 patients (35%) |
| Peak Admission Year | 2020 — 11,285 admissions |
| Abnormal Test Result Rate | 55% of all test results |
| Date Range | May 2019 – May 2024 |

---

## 🗄️ Dataset

| Field | Detail |
|---|---|
| Source | Lifewell General Hospital Network — Patient Admission Records |
| Coverage | 55,500 patient records, 10 hospitals, 8 U.S. states |
| Format | Microsoft Excel (.xlsx) |

### Variable Categories

**Patient Demographics**
- Patient ID, Age, Gender (Female / Male / Non-binary), Blood Type (8 categories)

**Clinical Variables**
- Medical Condition (Hypertension / Diabetes / Obesity / Arthritis / Cancer / Asthma)
- Medication (Lipitor / Ibuprofen / Aspirin / Paracetamol / Penicillin)
- Test Results (Normal / Abnormal / Inconclusive)

**Admission Variables**
- Date of Admission, Discharge Date, Days of Admission (calculated), Room Number
- Admission Type (Elective / Urgent / Emergency)

**Financial Variables**
- Billing Amount, Insurance Provider (Medicare / UnitedHealthCare / Aetna / Cigna)

**Geographic Variables**
- Hospital (10 facilities), Doctor, Hospital Latitude, Hospital Longitude, State (derived)

---

## 📈 Medical Condition Distribution

| Medical Condition | Patient Count | Share % | Clinical Insight |
|---|---|---|---|
| **Hypertension** | **13,875** | **25.0%** | Joint highest — lifestyle-linked, strong Diabetes co-morbidity |
| **Diabetes** | **13,875** | **25.0%** | Joint highest — peak co-morbidity overlap with Hypertension |
| Obesity | 12,765 | 23.0% | Third — directly linked to both Hypertension and Diabetes |
| Arthritis | 5,550 | 10.0% | Fourth — predominantly affects the 51–70 age cohort |
| Cancer | 5,550 | 10.0% | Fifth — equal to Arthritis; diverse age and gender spread |
| Asthma | 3,885 | 7.0% | Lowest — but disproportionately present in younger patients |
| **Total** | **55,500** | **100%** | |

**Hypertension, Diabetes, and Obesity together account for 73% of all admissions** — confirming that chronic disease management is the dominant clinical challenge across this hospital network.

---

## 📅 Age Distribution

| Age Group | 11–20 | 21–30 | 31–40 | 41–50 | **51–60** | 61–70 | 71–80 | 81–90 |
|---|---|---|---|---|---|---|---|---|
| Patients | 2,443 | 8,056 | 8,125 | 8,209 | **8,297** | 8,228 | 8,107 | 4,035 |

The distribution shows a near-normal curve peaking at 51–60 — consistent with the clinical profile of the three dominant conditions. The sharp drop at 81–90 reflects reduced population size and the shift toward palliative and community-based care in the oldest patient group.

---

## 🏧 Admission Type Breakdown

| Admission Type | Count | Share % | Operational Significance |
|---|---|---|---|
| Elective | 18,655 | 33.6% | Planned admissions — scheduled procedures |
| Urgent | 18,576 | 33.5% | Semi-urgent — prompt but non-emergency response |
| Emergency | 18,269 | 32.9% | Acute presentations — immediate care required |

The near-perfect three-way split is one of the most analytically significant findings in the dataset. It means the network must simultaneously manage predictable scheduled demand and unpredictable acute demand at equal scale — a more operationally complex challenge than emergency-dominated networks.

---

## 🏥 Hospital Network — Admission Distribution

| Hospital | Admissions | State | Share % |
|---|---|---|---|
| **Houston Methodist Hospital** | **20,402** | Texas | **36.7%** |
| Johns Hopkins Hospital | 11,268 | Maryland | 20.3% |
| UCLA Medical Center | 6,853 | California | 12.3% |
| Northwestern Memorial Hospital | 2,511 | Illinois | 4.5% |
| Massachusetts General Hospital | 2,471 | Massachusetts | 4.5% |
| UCSF Medical Center | 2,432 | California | 4.4% |
| Cleveland Clinic | 2,424 | Ohio | 4.4% |
| Cedars-Sinai Medical Center | 2,405 | California | 4.3% |
| Mayo Clinic | 2,400 | Minnesota | 4.3% |
| NewYork-Presbyterian Hospital | 2,334 | New York | 4.2% |

Houston Methodist processes more than **3x the volume** of any hospital outside the top two — a concentration that represents a significant single-point operational risk for the network.

---

## 📊 Dashboard Structure

### KPI Cards — Five Headline Indicators
- **Most Common Medical Condition:** Hypertension
- **Most Admitted Age Group:** 51–60
- **Most Common Blood Type:** A+
- **Year with Most Admissions:** 2020
- **Average Days of Admission:** 16

### Visuals Inventory

| Visual | Chart Type | Key Finding |
|---|---|---|
| Medical Condition by Count of Patients | Horizontal Bar Chart | Hypertension and Diabetes lead jointly at 13,875 each |
| Gender Distribution | Pie Chart | Female (50%), Male (40%), Non-binary (10%) |
| State Distribution | U.S. Map Visual | Texas dominates through Houston Methodist volume |
| Age Distribution | Column Chart | Bell-curve peaking at 51–60; sharp drop at 81–90 |
| Count of Admissions over Time | Quarterly Line Chart | 2020 pandemic peak clearly visible; 2021–2023 plateau |
| Test Results Summary | Donut Chart | Abnormal (55%), Inconclusive (35%), Normal (10%) |
| Medical Condition by Gender | Clustered Bar Chart | Differential condition prevalence by gender |
| Medical Condition by Blood Group | Stacked Bar Chart | Blood type risk profiling per condition |

---

## 🔍 Key Findings

### 1. Chronic Disease Is the Dominant Clinical Challenge
Hypertension, Diabetes, and Obesity collectively account for 73% of all 55,500 admissions. This concentration in lifestyle-linked chronic conditions signals that this network's primary clinical resource challenge is chronic disease management — not acute trauma or specialist surgical care.

### 2. 2020 Marked a Permanent Shift in Admission Volume
The 52.8% year-on-year jump from 2019 (7,387) to 2020 (11,285) was not temporary — it was sustained at near-identical levels through 2021 (10,931), 2022 (11,017), and 2023 (11,026). The pandemic appears to have permanently elevated the admission baseline by approximately 49% above pre-pandemic levels.

### 3. Abnormal Test Results Dominate
55% of all test results are Abnormal (30,525 patients) — the largest single result category. The 35% Inconclusive rate is particularly noteworthy: one in three tests fails to produce a definitive result, representing a significant diagnostic efficiency gap that warrants clinical protocol review.

### 4. Admission Type Balance Is Strategically Significant
The near-perfect three-way split (33.6% / 33.5% / 32.9%) means the network must manage predictable scheduled demand and unpredictable acute demand at equal scale simultaneously — requiring a formal three-track admission management system.

### 5. Houston Methodist Carries Disproportionate Network Load
At 36.7% of all admissions (20,402), Houston Methodist processes more than three times the volume of any hospital outside the top two. This concentration creates a single-point operational risk — any disruption has a disproportionate network-wide impact.

### 6. Medicare Covers Half the Patient Population
Medicare accounts for 27,750 patients — exactly 50% of all admissions. This concentration in a single insurance provider creates significant policy risk if Medicare reimbursement rates change, and warrants a payer diversification strategy.

### 7. The 51–60 Cohort Is the Peak Clinical Demand Group
The 51–60 age group leads all bands at 8,297 admissions, with 31–40 through 71–80 all exceeding 8,000. Children and young adults (11–30) and the oldest patients (81–90) are significantly underrepresented — confirming middle-aged adults as the overwhelming driver of hospital demand.

### 8. Female Patients Account for the Majority of Admissions
27,750 female patients (50%) versus 22,200 male (40%) and 5,550 non-binary (10%). The female majority reflects known gender differences in healthcare utilisation — women access healthcare services at higher rates across all age groups.

---

## ✅ Recommendations

### Clinical & Patient Care

1. **Establish Dedicated Chronic Disease Clinics** — Given that Hypertension, Diabetes, and Obesity account for 73% of admissions, establish multi-disciplinary chronic disease management clinics integrating endocrinology, cardiology, and nutrition services under a single care pathway.

2. **Implement Integrated Hypertension-Diabetes Screening** — Given the strong co-morbidity overlap, implement a dual-condition screening protocol so patients presenting with either condition are automatically tested for the other at point of admission.

3. **Review Inconclusive Test Result Protocols** — A 35% Inconclusive rate represents a significant diagnostic inefficiency. Conduct a clinical audit to identify whether threshold adjustments or enhanced diagnostic tools would reduce this rate.

4. **Target the 51–60 Age Group with Preventive Care** — As the peak admission cohort, the 51–60 group should be the primary target for preventive care investment including annual health screenings and lifestyle intervention programmes.

### Operational & Capacity

5. **Rebalance Network Capacity Away from Houston Methodist** — Invest in capacity expansion at lower-volume facilities to better distribute network demand and reduce single-hospital dependency.

6. **Plan for Sustained Elevated Demand** — Use the 2021–2023 plateau (~11,000 admissions/year) as the new planning baseline — not the pre-pandemic 2019 figure (7,387). The elevated demand is structural.

7. **Implement Three-Track Admission Management** — With Elective, Urgent, and Emergency at near-equal volume, implement formal dedicated scheduling pathways, staffing models, and bed allocation strategies for each admission type.

8. **Diversify Insurance Payer Mix** — Medicare at 50% of admissions creates policy risk. Develop strategies to grow UnitedHealthCare, Aetna, and Cigna patient volumes to reduce single-payer concentration.

---

## ⚠️ Limitations

- **Simulated dataset** — findings are demonstrative of analytical capability; real-world application requires validation against live EHR data
- **No patient-level longitudinal tracking** — readmission rates, treatment progression, and patient outcomes over time cannot be analysed
- **Negative billing values** — a small number of negative amounts (minimum: -$2,008.49) likely represent billing adjustments; these require clinical finance review in a production context
- **2024 data is partial** — only January–May 2024 is included; full-year 2024 benchmarking is not possible
- **No outcome or mortality data** — the dataset measures inputs and process metrics but not final patient health outcomes
- **No ICD-10 codes** — medical conditions are categorical labels, limiting clinical precision and cross-dataset comparability

---

## 🔭 Future Extensions

- Integrate ICD-10 diagnosis codes for standardised clinical condition mapping and international benchmarking
- Add patient outcome variables (mortality, readmission, recovery time) to extend analysis from inputs to outcomes
- Build a predictive model to identify patients at high risk of readmission within 30 days — a key NHS and U.S. CMS performance metric
- Extend geographic analysis to include socioeconomic deprivation indices by ZIP code for health equity analysis
- Develop a live Power BI dashboard connected to EHR data feeds for real-time clinical operations monitoring

---

## 📁 Repository Structure
📦 Clinical-Analytics-Hospital-Admissions-Billing-and-Patient-Outcomes
┣ 📊 Clinical_Analytics.xlsx                    ← Full Excel workbook — raw data, Pivot Tables, and dashboard
┣ 📄 Clinical_Analytics_Technical_Report.docx   ← Full technical report with methodology and findings
┣ 🖼️ Clinical_Analytics_Dashboard.jpg           ← Dashboard preview image (displayed in this README)
┗ 📝 README.md                                  ← Project documentation (you are here)


### How to Use This Repository

1. **To explore the dashboard** — download `Clinical_Analytics.xlsx` and open in Microsoft Excel (2016 or later recommended for full slicer functionality)
2. **To read the full analysis** — open `Clinical_Analytics_Technical_Report.docx` in Microsoft Word or Google Docs
3. **To work with the raw data** — the `Data` and `Cleaned Data` sheets in the workbook contain all 55,500 patient records ready for further analysis

---

## 🏷️ Tags

`excel` `pivot-tables` `healthcare-analytics` `clinical-analytics` `hospital-admissions` `data-visualisation` `patient-outcomes` `portfolio` `nhs-analytics` `health-intelligence`

---

*  Healthcare & Clinical Analytics Project*


