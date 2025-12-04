# Code4Change Hackathon - NyayaDrishti
Interactive dashboard built at Code4Change Hackathon to make court case data accessible and actionable.

# Overview
Nyayadrishti is an interactive, role-specific case management system designed to provide descriptive analytics, AI-powered predictions, and anomaly detection for the Indian judiciary. It leverages NJDG data (Karnataka High Court – civil cases) to deliver insights for judges, lawyers, courts, and the public.

# Team
1. Manya Sinha
2. Tejaswini Ponnada
3. L. Swanditha Reddy
4. Keerthana Ramesh Velan 

# Features
1. Homepage
   Total cases, civil cases, criminal cases (currently zero), pending cases (>1 year)
   Quick access buttons:
   - Analytics Dashboard – descriptive insights
   - AI Predictions – predictive forecasts for hearings, delays, disposal patterns
   - Anomaly Detection – highlights unusual case durations or irregularities

2. Analytics Dashboard
   - Case progression and stage funnel
   - Disposal trends (line graphs)
   - Judge workload (bar graphs)
   - Distribution of disposal days (histograms)
   - Filters to see yearwise progress 

3. AI Predictions
   - Predicts upcoming hearing dates and delays
   - Forecasts disposal patterns

4. Anomaly Detection
   - Identifies irregular case durations using Isolation Forest

5. Role-based Dashboards
   - Judge:
     a) Filterable case lists, alerts for cases pending >365 days
     b) Overview of today, upcoming and rescheduled hearings
     c) Disposal trends and workload insights
   - Lawyer:
     a) Case portfolio tracking
     b) Option to save personalized notes, reminders, alerts for upcoming hearings
6. Public/Researcher:
   India follows an open court system so the anaytics dashboard, AI predictions and Anomaly detection is available to the public



# Problem Addressed

1. Judges: Manual cause list prep, lack of quick overview, difficulty prioritizing cases
2. Lawyers: Inefficient portfolio tracking, reminders, and navigation
3. Public: Limited transparency and visual anaytics of the case 

# Technology Stack

1. Framework: Streamlit
2. Data Processing: Pandas, NumPy
3. Visualization: Plotly Express, Matplotlib, Seaborn
4. Machine Learning: Scikit-learn (IsolationForest)
5. Security: Encrypted cookie-based login
6. Utilities: OS, Pathlib, JSON, Logging, Warnings

# Dataset
Our dataset was provided by Code4Change Hakcathon and it only contains civil cases which are disposed in the High Court of Karnataka
1. ISDMHack_Cases_students.csv – civil, disposed cases from Karnataka High Court
2. ISDMHack_Hear_students.csv – hearing dates for civil cases

# Benefits & Impact

1. Judges: Prioritize cases, manage workload, identify bottlenecks
2. Lawyers: Strategic planning, reminders, improved productivity
3. Courts: Reduced delays, improved workflow discipline
4. Public: Accessible visualizations for research and transparency


# Future Work

1. Include criminal cases and pending cases analytics
2. Expand to other states and jurisdictions
3. Enhanced AI predictions with historical data trends
4. Real-time updates and integration with NJDG portal

# References
Other than our NJDG website we referred to other dashboards for inspiration 
1. Court Statistics Project (CSP) – US
2. HMCTS Data & Transparency Dashboards – UK
3. DAKSH Judicial Dashboards – India
