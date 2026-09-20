# 🏥 HealthConnect Experience Lab

![Python](https://img.shields.io/badge/Python-3.x-blue)

![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)

![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualisation-orange)


## Improving Patient Appointment Attendance and Healthcare Support Using Data and AI

This repository contains my work for the **HealthConnect Experience Lab** as part of the **AnalystLab Africa Data Analytics Internship**.

The project focuses on analysing healthcare appointment data to better understand appointment attendance patterns and identify factors that may contribute to patient no-shows. The long-term objective is to generate data-driven insights that can help improve clinic operations, patient engagement, and appointment management.

---

## Week 4 Objective

Week 4 focused on understanding the business problem and preparing for the analysis rather than developing a final solution.

The main objectives were to:

* Review the HealthConnect business scenario.
* Explore the appointment dataset.
* Assess the quality of the available data.
* Identify business questions.
* Propose relevant Key Performance Indicators (KPIs).
* Develop an initial analytical approach for the project.

---

## Week 5 Objective

Week 5 focused on practical implementation.

Completed activities included:

* Extended exploratory data analysis.
* KPI development and calculation.
* Business insight generation.
* Interactive Power BI dashboard development.
* Business recommendations based on analytical findings.

---

## Week 6 Objective

Building on the Week 5 exploratory analysis and dashboard development, Week 6 focused on advancing the HealthConnect analytics solution from descriptive reporting towards decision support. Activities included:

* Validates the most important appointment attendance patterns
* Investigated relationships between key factors influencing no-show behaviour
* Improved the dashboard with insights that could support operational decision-making.

The analysis focused on identifying higher-risk appointment groups, evaluating reminder effectiveness and translating analytical findings into actionable recommendations for reducing missed appointments.

---

## Week 7 Objective
Week 7 focused on analytical testing, refinement and validation. The main objectives were:

* Validate the analytical findings identified during Week 6 to determine whether they remained consistent when tested against additional evidence.
* Test and refine the HealthConnect dashboard to improve usability and decision support.
* Validate key KPIs and attendance patterns using the underlying appointment dataset.
* Collaborate with the Data Science track to assess how analytical findings could support predictive modelling decisions.
* Identify remaining limitations and prepare the project for final integration.

---

## 🛠️ Tools Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib

---

## 📁 Repository Structure

```text
## 📁 Repository Structure

│
├── dashboard/
│   └── HealthConnect Appointment Attendance & Risk Analysis Dashboard
│       └── Dashboard screenshots / Power BI file
│
├── data/
│   └── HealthConnect_Appointment_Data.csv
│
├── notebook/
│   ├── Week4_HealthConnect_Analysis.ipynb
│   ├── Week5_HealthConnect_Analysis.ipynb
│   └── Week6_HealthConnect_Analysis.ipynb
│
├── Week4/
│   └── Week4 project documentation and outputs
│
├── Week5/
│   └── Week5 project documentation and outputs
│
├── Week6/
│   └── Week6 analytics report, dashboard updates and supporting files
│
├── Week7/
│   └── Week7 analytics testing, refinement and validation outputs
│
├── .gitignore
│
├── LICENSE
│
└── README.md
```

---

## Week 4 Highlights

During this week's analysis, I:

* Explored the structure of the appointment dataset.
* Performed an initial data quality assessment.
* Identified missing values and reviewed variable types.
* Conducted exploratory data analysis using Python.
* Identified key business questions for future investigation.
* Proposed KPIs to evaluate appointment attendance and no-show patterns.
* Developed an initial analysis plan for the next stage of the project.

---

## Week 5 Highlights

Some of the main findings include:

* Patients with previous no-shows were considerably more likely to miss future appointments.
* Longer booking lead times were associated with higher no-show rates.
* Appointment reminders were associated with slightly improved attendance.
* No-show rates remained consistently high across appointment types.
* Age, waiting time and distance to the clinic appeared to have relatively little influence on appointment attendance.
  
---

## Week 6 Highlights

* Validated Week 5 findings by investigating the relationship between previous no-show behaviour and future appointment attendance.
* Developed patient risk categories based on previous no-show history to identify groups requiring different levels of administrative support.
* Enhanced the Week 5 dashboard by adding decision-support visuals:
  - Patient Risk Classification Matrix
  - Previous No-Shows × Reminder Sent analysis
  - Booking Lead Days by Appointment Type
  - Attendance Rate by Appointment Type
  - Average Booking Lead Days × Reminder Sent analysis
* Developed analytical outputs that can support future testing, predictive modelling and administrative decision-making.

--- 

## Week 7 Highlights

* Validated the key Week 6 findings related to appointment attendance behaviour, including:
  - Previous no-show history as a strong indicator of future missed appointments.
  - Increased no-show rates among appointments booked further in advance.
  - The limited predictive value of reminder status for modelling purposes, while remaining relevant as an operational intervention.
* Performed cross-track validation with the Data Science track by sharing analytical findings that informed feature selection and model refinement.
* Supported model validation by providing evidence on:
  - Previous no-show behaviour.
  - Booking lead-time patterns.
  - Attendance trends across appointment segments.
* Refined the Power BI dashboard by adding interactive slicers to improve exploration of:Appointment type, Appointment outcome, Booking lead group and Patient risk classification.
* Tested dashboard functionality and confirmed that KPI calculations and visualisations remained consistent after refinement.

---

### 🔎 Key Insights:

Through progressive analysis, dashboard refinement and validation activities, several important patterns were identified:

### 1. Previous attendance behaviour is the strongest indicator of future no-shows

Patients with previous missed appointments showed substantially higher no-show rates in future appointments. No-show rates increased from approximately 43.5% among patients without previous no-shows to nearly 68% among patients with multiple previous no-shows.

**Implication:** Previous attendance behaviour can be used to identify higher-risk patients who may benefit from targeted follow-up strategies.

### 2. Longer booking lead times are associated with increased no-show risk

Appointments scheduled further in advance showed higher missed appointment rates. No-show rates increased from approximately 29% for appointments booked 0–7 days in advance to over 71% for appointments booked 46–60 days in advance.

**Implication:** Earlier confirmation strategies may help reduce missed appointments for appointments scheduled further in advance.

### 3. Reminder usage supports attendance improvement but requires further evaluation

Patients who received reminders showed slightly improved attendance compared with those who did not. However, reminder status was not retained as a predictive modelling feature due to potential prediction-time limitations.

**Implication:** Reminders remain valuable as an operational intervention rather than a direct predictor of no-show behaviour.

### 4. No-show behaviour represents a clinic-wide challenge

No-show rates remained consistently high across appointment types, suggesting the issue is not isolated to a specific service area.

**Implication:** HealthConnect should focus on broader patient engagement strategies rather than targeting only one appointment category.

### 5. Risk-based segmentation can support targeted interventions

Combining behavioural indicators such as previous no-shows and booking patterns allows patients to be grouped into different risk categories.

**Implication:** HealthConnect can allocate administrative resources more effectively by applying different follow-up approaches based on patient risk level.


---

## Key Business Questions

The analysis was guided by the following questions:

* Which patient and appointment factors are associated with missed appointments?
* Are patients with previous no-shows more likely to miss future appointments?
* Does booking lead time influence appointment attendance?
* Do appointment reminders contribute to improved attendance?
* Can patient and appointment characteristics be used to identify higher-risk groups?
* How can analytical findings support strategies to improve attendance and reduce missed appointments?

---

## 👤 Author

**Claudia Nomagugu Moyo**

Aspiring Data Analyst | Business Intelligence | Healthcare Analytics

Data Analytics Intern – AnalystLab Africa
