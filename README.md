# 🏥 Healthcare Analytics Portfolio Project  
**Hospital Visits & Immunization Insights (2022)**  
**Author:** Daniel Groza | [🔗 LinkedIn](https://www.linkedin.com/in/danielgroza) | [📊 Tableau Public](https://public.tableau.com/app/profile/daniel.groza)

---

## 📌 Project Summary  
This end-to-end healthcare analytics project uses SQL, Excel, and Tableau to analyze 2022 patient records related to hospital admissions, emergency visits, outpatient procedures, and flu immunization coverage. It merges structured datasets and SQL queries into four interactive dashboards that highlight clinical inefficiencies, care gaps, payer distribution patterns, and seasonal surges—offering a blueprint for improving operational outcomes, equity, and patient engagement.

---

## 📁 Files Included  
- `Healthcare_Data_Analysis.sql` – SQL logic for admissions, cost breakdowns, and visit types  
- `Hospital ER.csv`  
- `Healthcare Demo Data.csv`  
- `Flu shot 2019.xlsx`  
- Tableau Dashboards (4 total)  
- `README.md` – This documentation file  

---

## 🔗 Dashboard Links

| Dashboard Name                             | Tableau Public Link |
|-------------------------------------------|---------------------|
| 🏥 Hospital Admissions & Coverage (Pt. 1)  | [View Dashboard](https://public.tableau.com/app/profile/daniel.groza8136/viz/HospitalVisitPatientRecords2022Pt_1/Dashboard1?publish=yes) |
| 💰 Visit Type & Cost Breakdown (Pt. 2)     | [View Dashboard](https://public.tableau.com/app/profile/daniel.groza8136/viz/HospitalVisitPatientRecords2022Pt_2/Dashboard2?publish=yes) |
| 🚨 Emergency Room Visits Dashboard         | [View Dashboard](https://public.tableau.com/app/profile/daniel.groza8136/viz/EmergencyRoomVisitsDashboard_17580565550800/Dashboard1) |
| 💉 Flu Shots Compliance Analysis (2022)    | [View Dashboard](https://public.tableau.com/app/profile/daniel.groza8136/viz/HealthcareSystemFluShotsAnalysis2022/Dashboard) |

---

## 🔍 Dashboard 1: Hospital Admissions & Coverage (Pt. 1)

### 💡 Key Insights  
- Total Admissions: **21,669** across **3,286** unique patients → **6.6 avg. admissions per patient**  
- **42.1%** of all admissions were due to **Stage IV Chronic Kidney Disease (CKD)**  
- **28.4%** due to **Pregnancy (status, not complication)**  
- Average Length of Stay (ALOS): **4.5 days**, ER Median Time: **60.0 min**  
- Government-funded insurance (Medicare, Medicaid, Dual Eligible): **52.2%**  
- **4.8%** uninsured population—nearly 1,040 patients  

### ✅ Implementation Plan  
- **Nephrology Program Expansion**  
  → Open two additional nephrology clinics and add 40 dialysis chairs system-wide  
  → Target: Reduce CKD-related inpatient admissions by **15% in 12 months**  

- **Prenatal Care Scheduling Protocol**  
  → Auto-trigger referral to OB-GYN for all pregnancy-status admissions  
  → Target: Reduce repeat ER visits among pregnant patients by **25%**  

- **High Utilizer Strategy**  
  → Enroll top **5%** of repeat users in chronic care management; introduce case managers  
  → Outcome: Prevent over **1,000 avoidable admissions** per year  

- **Insurance Outreach Kiosk**  
  → Implement financial counseling booth at discharge for uninsured patients  
  → Goal: Convert **50%** of self-pay patients into Medicaid or ACA coverage

---

## 🔍 Dashboard 2: Visit Type & Cost Breakdown (Pt. 2)

### 💡 Key Insights  
- Outpatient Encounters with Problems: **12,217** (nearly **57%** of all encounters)  
- Prenatal Care: **4,710** → **22%** of outpatient volume  
- Monthly cost trend: **$1.4M in January** → **$2.1M by December**  
- Despite stable visit volume (~1,700–1,900/month), total hospital costs rose **50%**  
- Virtual visits: Less than **1.5%** of total volume  

### ✅ Implementation Plan  
- **Virtual Prenatal Program Rollout**  
  → Shift **30%** of prenatal care to telehealth with wearable fetal monitors  
  → Projected Savings: $250K in Q3-Q4  

- **High-Cost Encounter Bundling**  
  → Introduce flat-rate pricing for common issues like abdominal pain, high BP  
  → Goal: Lower per-encounter cost by **8-10%** while improving care standardization  

- **Seasonal Staffing Model**  
  → Hire temporary RNs for peak summer ER wait times (**123.6 min in July**)  
  → Expected: Reduce July ER average time below **105 minutes**

- **Insurer Partnership Alignment**  
  → Negotiate with Humana and Cigna for value-based payment on outpatient adherence  
  → Focus on prenatal and CKD follow-through metrics

---

## 🔍 Dashboard 3: Emergency Room Visits Dashboard

### 💡 Key Insights  
- Total ER Patients: **9,216**  
- Wait Time: **35.26 min**, Satisfaction Score: **4.99 / 10**  
- ER Visits Peak: **3 AM–6 AM**, Tuesday–Thursday  
- 58.6% of patients (5,400) had **no post-visit referral**  
- Top referred specialties: General Practice (1,840), Orthopedics (995), Neurology (193)  

### ✅ Implementation Plan  
- **Staff Scheduling Alignment**  
  → Deploy cross-functional ER team coverage for 3–6 AM peak window  
  → Target: Reduce overnight waiting room load by **20%**  

- **Referral Completion Automation**  
  → EHR rule triggers auto-referrals for top 10 chronic ER diagnoses  
  → Goal: Increase specialty referrals from **41.4% → 60%** in 6 months  

- **Post-ER Engagement System**  
  → SMS discharge instructions, nurse call-backs in 48 hours  
  → Metric: Raise satisfaction from **4.99 → 6.5+** by next reporting cycle  

- **Chronic Disease Referral Flagging**  
  → Highlight patients with repeat visits tied to renal, GI, or behavioral health  
  → Enroll flagged patients into specialty referral tracking workflow

---

## 🔍 Dashboard 4: Flu Shots Compliance Analysis (2022)

### 💡 Key Insights  
- Total Flu Shots: **4,023**, System-wide Compliance: **81.7%**  
- Age Breakdown:  
  - **Highest**: 50–64 (95.6%), 0–17 (92.2%), 65+ (90.5%)  
  - **Lowest**: 18–34 (64.8%), 35–49 (68.9%)  
- Race Breakdown:  
  - **Highest**: Native (93.8%), Hawaiian (86.8%)  
  - **Lowest**: “Other” (75.0%)  
- Running Sum: Rapid increase from March–July; slowed Q4  
- Geographic Variation: Lower compliance in rural MA and coastal CT counties  

### ✅ Implementation Plan  
- **Targeted Outreach for Young Adults (18–34)**  
  → Run workplace and university-based flu clinics in October  
  → Aim to raise compliance by **10 percentage points** for this group  

- **Equity-Focused Language Access Campaign**  
  → Community liaisons + multilingual signage for “Other” race group  
  → Goal: Improve compliance from **75% → 83%**  

- **Last-Mile Flu Shot Drive (Q4)**  
  → Partner with local pharmacies for walk-in boosters in Nov-Dec  
  → Metric: Increase flu shots in Q4 by **20% YoY**

---

## 🧠 BI Value & Strategic Impact  

| Area                | Strategic Value                                                                 |
|---------------------|---------------------------------------------------------------------------------|
| Immunization        | Reduces preventable hospitalizations and improves seasonal capacity planning     |
| ER Optimization     | Reduces early-morning congestion and improves care continuity                    |
| Outpatient Strategy | Enhances operational efficiency and lowers per-patient cost burden               |
| Payer Coordination  | Enables value-based contracts linked to real clinical KPIs                       |
| Resource Planning   | Aligns staff supply with clinical demand and cost trends                         |

---

## 🛠️ Tools Used  

| Tool       | Purpose                                      |
|------------|----------------------------------------------|
| SQL        | Querying, joins, data modeling, subqueries    |
| Excel      | Cleaning, reshaping, export prep             |
| Tableau    | Visual design, maps, bubble charts, dashboards |
| GitHub     | Documentation and project publishing         |

---

## 📌 Next Steps & Enhancements  
- Implement ARIMA-based forecasting on ER volumes and admissions  
- Develop Tableau auto-refresh using CSV pipelines or database hooks  
- Integrate COVID + flu co-infection tracking by zip code and age  
- Embed into Carrd-based portfolio site with full dashboard interactivity  

---

## 📫 Contact  

**Daniel Groza**  
Charlotte, NC  
🔗 [LinkedIn](https://www.linkedin.com/in/danielgroza)  
📊 [Tableau Public](https://public.tableau.com/app/profile/daniel.groza)
