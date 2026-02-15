# Healthcare Analytics: Predicting Hospital Readmissions for Diabetes Patients
**Instructor:** Dr. Ashok Kumar Sharma (Bioinformatics Scientist)  
**Project Scope:** End-to-End Analytics (Python ➔ Power BI ➔ GitHub)

## 🎯 Project Overview
This project addresses a critical healthcare challenge: **predicting 30-day hospital readmissions.** By analyzing clinical data from 130 US hospitals, we aim to identify high-risk patients, reduce healthcare costs, and improve patient outcomes.

---

## 📊 Executive Dashboard


## 🏗️ Project Structure (The 5-Segment Plan)

### **Segment 1: Introduction & Data Acquisition**
* **Objective:** Establish the environment and load the dataset.
* **Dataset:** Diabetes 130-US Hospitals Database (1999-2008) from the UCI Machine Learning Repository.
* **Environment:** Python (Pandas/NumPy) for initial exploration and handling 101k+ records.

### **Segment 2: Data Preprocessing & Cleaning**
* **Quality Assessment:** Standardized missing values and handled clinical mapping.
* **Cleaning:** Processed and validated **47 clinical columns**.
* **Feature Engineering:** * Converted age ranges to `age_numeric` (e.g., `[70-80)` became `75`).
    * Generated readmission risk flags to assist in clinical decision-making.

### **Segment 3: Exploratory Data Analysis (EDA)**
* **Univariate Analysis:** Analyzed patient demographics and stay duration.
* **Top Conditions:** Identified **Circulatory**, **Diabetes**, and **Respiratory** as the primary diagnoses using ICD-9 code grouping.
* **Key Trend:** Patients with higher laboratory involvement showed a direct correlation with complex diagnosis profiles.

### **Segment 4: Model Building & Feature Importance**
* **Analysis:** Using the `Feature_Importance_Results.csv`, we identified the top drivers for hospital readmission.
* **Top 3 Predictors:**
    1. **Lab Procedures (31.7%):** Most significant predictor of patient tracking.
    2. **Number of Medications (23.2%):** Indicates patient complexity.
    3. **Time in Hospital (11.4%):** Longer stays correlate with higher readmission risk.



### **Segment 5: Reporting & Documentation**
* **Visualization:** Built an interactive **Power BI Dashboard** with a modern lavender aesthetic.
* **UX Features:** Implemented a custom **Reset Filters** button and Top N filtering for condition analysis.
* **Documentation:** This repository serves as a professional technical portfolio.

---

## 🛠️ Technical Stack
* **Data Processing:** Python (Pandas, NumPy, Scikit-Learn)
* **Visualization:** Power BI (Advanced DAX)
* **Project Tracking:** GitHub Version Control

---

## 📂 Repository Contents
* `Data/`: Raw datasets, `IDS_mapping.csv`, and `Feature_Importance_Results.csv`.
* `Notebooks/`: `Healthcare_Readmission_Prediction.ipynb` containing the Python logic.
* `Dashboard/`: `HealthCare_Dashboard.pbix` (Power BI Report).
