# UAE Cancer Patient Analysis & Outcome Prediction

## Project Overview
This project analyzes a **UAE Cancer Patient Dataset** containing 10,000 patients. The goal is to explore patient demographics, cancer types, stages, treatments, and outcomes, and to build a **predictive model** to classify patient outcomes (alive vs deceased).

**Tech Stack:** Python, Pandas, Seaborn, Matplotlib, scikit-learn, imbalanced-learn  

---

## Dataset
- **Source:** Kaggle UAE Cancer Patient Dataset  
- **Number of Patients:** 10,000  
- **Features:**  
  - Patient_ID, Age, Gender, Nationality, Emirate  
  - Cancer_Type, Cancer_Stage, Treatment_Type, Hospital, Primary_Physician  
  - Outcome, Death_Date, Smoking_Status, Comorbidities, Weight, Height, Is_Deceased  

---

## Key Steps in the Project

1. **Data Cleaning & Preprocessing**
   - Converted date columns to datetime
   - Handled missing values (e.g., Comorbidities)
   - Created target column `Is_Deceased`  

2. **Exploratory Data Analysis (EDA)**
   - Visualized demographics (Gender, Age, Nationality, Emirate)
   - Analyzed cancer types, stages, hospital distribution
   - Explored treatment types and patient outcomes  

3. **Predictive Modeling**
   - Features selected: Age, Gender, Cancer_Type, Cancer_Stage, Treatment_Type, Hospital, Comorbidities, Smoking_Status
   - **Handled class imbalance using SMOTE**
   - **Logistic Regression model**: F1 Score ~0.63, ROC AUC ~0.68

4. **Feature Importance**
   - Random Forest used to rank features
   - Top features: Age, Cancer Type, Cancer Stage, Comorbidities, Treatment Type

5. **Executive Dashboard**
   - One-page dashboard combining demographics, top cancers, and feature importance
   - Provides a clear **visual story** of UAE cancer patient trends  

---

## Key Insights
- Age, Cancer Type, and Cancer Stage are the **most influential factors** in patient outcomes
- Balanced predictive modeling improves accuracy for deceased patients
- Visualization reveals **UAE-specific trends** in cancer type, treatment, and outcomes

---

## Portfolio & Use Case
This project demonstrates:
- **Data Cleaning & EDA**
- **Handling imbalanced datasets**
- **Predictive modeling for healthcare analytics**
- **Feature importance visualization for interpretability**
- **Professional dashboards for portfolio showcase**

It can be showcased for **data science roles in UAE**, particularly in **healthcare analytics, hospitals, or health-tech companies**.

---

## Files in Repository
- `UAE_Cancer_Patient_Analysis_and_Prediction.ipynb` → Full notebook  
- `UAE_Cancer_Executive_Summary.png` → Dashboard image  
- `README.md` → Project overview and portfolio description
