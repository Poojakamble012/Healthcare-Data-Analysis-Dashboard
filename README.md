# 🫁 Smoking Health Risk Analysis — Power BI Dashboard

## 📌 Project Overview
This Power BI project explores the relationship between smoking habits 
and health outcomes across a diverse patient population. The dashboard 
provides a multi-dimensional view of smoking status, organ condition, 
cholesterol levels, hypertension risk, and BMI — enabling data-driven 
insights into public health risk patterns.

---

## 📊 Dashboard Features

### Page 1 — Risk Overview
- **Damaged vs Healthy toggle** — Filter entire dashboard by organ condition
- **KPI Card** — Total patient count (193), vs Average Age (54.9), vs Avg BMI
- **% of Smoking Status** — Donut chart showing Never (40.93%), 
  Former (30.57%), Current (28.5%) smokers
- **Smoking Duration & Daily Intake by Age Group** — 
  Line chart (YOS = Years of Smoking, CPR = Cigarettes Per Day) 
  across age bands 18–28 to 69+
- **Smoking Status by Gender** — Clustered bar chart comparing 
  Female vs Male across Never / Current / Former categories
- **Cholesterol & Hypertension Risk by Age Group** — 
  Stacked bar chart (High / Low / Normal) across all age groups
- **Organ Condition Panel** — Visual selector for Heart, Lungs, 
  Kidney, Liver analysis

---

## 🗂️ Dataset Fields
| Field | Description |
|---|---|
| Patient_ID | Unique patient identifier |
| Age / Age_Group | Patient age and binned group |
| Gender | Male / Female |
| BMI | Body Mass Index |
| Smoking_Status | Never / Current / Former |
| Cigarettes_Per_Day | Daily smoking quantity |
| Years_of_Smoking | Smoking duration |
| BP_Risk | Blood pressure risk level |
| Cholesterol_Level | Cholesterol reading |
| Organ | Organ being analyzed |
| Organ_Condition | Damaged / Healthy |
| Alcohol_Consumption | Alcohol intake data |
| Family_History | Family medical history flag |

---

## 🔧 Tools & Technologies
- **Power BI Desktop** — Dashboard development & DAX calculations
- **DAX** — Custom measures: vs Avg Age, vs Avg BMI, Age Group bins
- **Data Modeling** — Single table model with calculated columns
- **Power Query (M)** — Data cleaning and transformation

---

## 💡 Key Insights
- Nearly 59% of patients are current or former smokers
- Cholesterol and hypertension risk peaks in the 49–58 age group
- Male patients show higher rates of current smoking vs females
- Smoking duration (YOS) increases steadily with age group, 
  with daily intake (CPR) highest in the 39–48 bracket
- Organ damage is most prevalent in the Heart and Lungs categories

---

## 📁 Files in this Repository
| File | Description |
|---|---|
| `Smoking_Health_Risk.pbix` | Power BI project file |
| `health_dataset.csv` | Raw dataset used |
| `dashboard_screenshot.png` | Dashboard preview image |
| `README.md` | Project documentation |

---

## 🚀 How to Use
1. Download and open `Smoking_Health_Risk.pbix` in Power BI Desktop
2. Use the **Damaged / Healthy** toggle to filter by organ condition
3. Click any organ in the left panel to drill into organ-specific data
4. Use age group filters to explore demographic trends

---

## 👩‍💻 Author
**Pooja Kamble**  
Data Analyst | SQL · Python · Power BI · Tableau  
[LinkedIn](https://www.linkedin.com/in/pooja-kamble-7144aa230)
