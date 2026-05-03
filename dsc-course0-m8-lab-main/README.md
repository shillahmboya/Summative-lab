# Aviation Accident Analysis
✈️ Aircraft Safety Analysis (1948–2023)
📌 Project Overview

This project analyzes aviation accident data to identify aircraft makes and models with the lowest risk of:

Fatal injuries
Serious injuries
Aircraft destruction

The goal is to support airline and insurance decision-making by identifying safer aircraft types.

📊 Dataset
Source: Aviation accident database (1948–2023)
Filtered period: 1983–2023 (to reflect active aircraft lifecycle)
Key variables: aircraft make, model, injuries, weather conditions, flight phase, and aircraft damage
🧹 Data Cleaning
Removed columns with excessive missing values (>50%)
Handled missing values in injury and operational fields
Created derived features:
Severe injury rate (fatal + serious injuries per occupant)
Aircraft destruction flag
Aircraft size classification (small vs large)
✈️ Analysis Performed
Injury risk by aircraft make and model
Small vs large aircraft comparison
Weather condition impact on accident severity
Phase of flight risk analysis
Aircraft destruction rates by manufacturer
📈 Key Findings
Large aircraft show more stable and lower injury risk
Small aircraft exhibit higher variability in safety outcomes
Takeoff and landing phases are the most dangerous
Poor weather conditions increase accident severity
Certain manufacturers consistently show lower risk profiles
 Recommendations

Aircraft with consistently low injury and destruction rates are recommended for insurance portfolios due to lower risk exposure. Large commercial aircraft generally demonstrate the safest and most stable performance profiles.

 Tools Used
Python (Pandas, NumPy)
Matplotlib & Seaborn
Jupyter Notebook
Git & GitHub

