# OLA_DRIVER_ATTRITION_ANALYSIS

Overview

This project explores the problem of high driver attrition at Ola using exploratory data analysis (EDA) and data engineering techniques. The goal is to understand key patterns in driver churn using historical data and propose actionable strategies to reduce attrition.

⸻

📁 Dataset
	•	Source: Ola driver monthly records (2019–2020)
	•	Features Include:
	•	Driver ID, Age, Gender, City, Education Level
	•	Monthly Income, Date of Joining, Last Working Date
	•	Quarterly Rating, Total Business Value, Grade

⸻

🎯 Objectives
	•	Analyze historical data to uncover patterns in driver churn
	•	Engineer meaningful features like tenure and income/rating trends
	•	Identify key factors that influence attrition
	•	Recommend actionable business strategies for driver retention

⸻

🧪 Tools & Technologies
	•	Language: Python
	•	Libraries: Pandas, NumPy, Seaborn, Matplotlib
	•	Platform: Jupyter Notebook

⸻

🔍 Key Steps

1. Data Cleaning & Preprocessing
	•	Removed or imputed missing values
	•	Converted Dateofjoining and LastWorkingDate to datetime format
	•	Created new features like:
	•	Attrition (1 if the driver left, else 0)
	•	Tenure_Days (driver’s length of stay)
	•	Income_Increased and Rating_Increased (binary indicators)

2. Exploratory Data Analysis (EDA)
	•	Visualized distributions of age, income, total business value
	•	Analyzed joining and leaving trends month-wise
	•	Compared tenure and ratings of active vs. exited drivers

3. Feature Insights
	•	Drivers with short tenure (< 90 days) were more likely to leave
	•	Poor quarterly ratings were linked to high attrition
	•	Decreasing income trends correlated with increased risk of churn
	•	City and education level influenced business value

⸻

💡 Business Recommendations
	•	Offer bonuses for completing 90+ days
	•	Identify and support low-rated drivers early
	•	Introduce minimum guaranteed earnings for new joiners
	•	Launch city-specific engagement programs based on churn trends
	•	Use income trends as early warning signals for disengagement

 Outcomes
	•	Discovered key churn indicators from EDA
	•	Translated data patterns into strategic HR recommendations
	•	Built a strong foundation for further predictive modeling (if needed)

⸻

🙌 Acknowledgements

Special thanks to the Ola team (case study context) for providing a practical real-world problem to analyze.
