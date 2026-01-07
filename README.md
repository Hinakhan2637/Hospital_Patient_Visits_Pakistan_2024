🏥 Hospital Patient Visits – Pakistan (2024) | Power BI Analytics & Prediction
📌 Project Overview

This project analyzes hospital patient visits in Pakistan for the year 2024 using Power BI.
It provides descriptive, diagnostic, and predictive insights to improve hospital operations, patient experience, and decision-making.

The dashboard integrates hospital details, patient visit data, and predictive analysis to identify trends, inefficiencies, and future risks.

🎯 Objectives

Analyze patient visit patterns across hospitals and departments

Identify operational issues such as long waiting times and no-shows

Compare hospital and department performance

Generate predictive insights for proactive healthcare planning

📂 Dataset Description
1️⃣ Patient Visit Details

Each record represents a single patient visit.

Column	Description
visit_id	Unique identifier for each visit
visit_date	Date of visit
visit_time	Patient arrival time
consultation_start_time	Consultation start time
consultation_end_time	Consultation end time
wait_time_minutes	Waiting time before consultation
treatment_time_minutes	Duration of treatment
visit_type	New, Follow-up, Emergency
no_show	Indicates missed appointment
patient_id	Unique patient identifier
2️⃣ Hospital Details
Column	Description
hospital_id	Unique hospital identifier
city	Hospital location
department	Medical department
3️⃣ Financial Information
Column	Description
total_cost_pkr	Total treatment cost (PKR)
📊 Dashboard Pages
🔹 Title Page

Project overview

Navigation buttons:

Basic of Dataset

Patients

Hospitals

Prediction

🔹 Basic of Dataset

Total visits

Average waiting time

Average treatment time

Total revenue

Monthly patient trends

🔹 Patients Page

Visit type distribution

No-show analysis

Waiting time vs treatment time

Patient flow patterns

🔹 Hospitals Page

Hospital-wise patient load

Department-wise performance

City-wise healthcare demand

Resource utilization insights

🔮 Prediction Page (Core Innovation)

The prediction page transforms historical data into future-focused insights.

1️⃣ Patient Visit Volume Prediction

Forecasts future patient demand by:

Hospital

Department

City

Time (monthly trends)

Impact: Better staff and resource planning.

2️⃣ Waiting Time Prediction

Predicts expected waiting time based on:

Department

Visit type

Historical congestion patterns

Improvement Identified:
Average waiting time ≈ 65 minutes, with peaks up to 240 minutes.

Impact: Reduced overcrowding and improved patient satisfaction.

3️⃣ Treatment Duration Prediction

Forecasts treatment duration using:

Department

Visit type

Impact: Optimized scheduling and improved operational flow.

4️⃣ Cost Prediction per Visit

Predicts expected treatment cost based on:

Department

Treatment time

Visit type

Impact: Financial planning and cost transparency.

5️⃣ No-Show Risk Prediction

Identifies probability of missed appointments.

Current no-show rate: ~9%

Impact: Appointment optimization and revenue protection.

📈 Key Findings & Improvement Areas
Area	Insight	Improvement
Waiting Time	High in Emergency & OPD	Predictive staffing
Department Load	Uneven distribution	Demand forecasting
Costs	High variability	Cost prediction
No-Shows	~9%	Risk-based reminders
🛠 Tools & Technologies

Power BI Desktop

Excel (Data Source)

DAX (Measures & KPIs)

Predictive Forecasting (Trend-based)

📌 Business Value

Proactive hospital management

Reduced patient waiting time

Improved healthcare accessibility

Data-driven decision making

🚀 Future Enhancements

Machine learning integration (Random Forest / ARIMA)

Real-time hospital data connection

Patient satisfaction analysis

Automated alert system for high-risk periods

