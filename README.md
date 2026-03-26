🏥 Healthcare Data Engineering Project
📌 Overview
This project demonstrates advanced data manipulation and feature engineering using a synthetic healthcare dataset. Designed to mimic real-world Electronic Health Records (EHR), the dataset provides a high-fidelity environment for practicing data science skills—such as predictive modeling and population health analysis—without the privacy or compliance concerns (HIPAA/GDPR) associated with real Protected Health Information (PHI). 

📊 Dataset Specifications
Scale: 20,000 records.
Original Structure: 25 initial columns (demographics, billing, and clinical basics).
Engineered Structure: 42 columns following extensive feature engineering.
Data Type: Synthetic tabular data (CSV). 

🛠️ Feature Engineering (25 → 42 Columns)
The dataset was expanded by 17 columns to extract deeper clinical and operational insights. Key engineered features include:
Temporal Analytics: Derived Length of Stay (LOS) by calculating the difference between admission and discharge dates.
Demographic Segmentation: Categorized age into Age_Groups (e.g., Pediatric, Adult, Geriatric) for cohort analysis.
Clinical Indicators: Added binary Comorbidity_Flags and severity scores based on primary medical conditions.
Financial Insights: Created Daily_Cost metrics and insurance coverage ratios from raw billing data.
Machine Learning Readiness: Implemented encoding (One-Hot, Ordinal) and handled numerical transformations for model compatibility
