# Liver-Cancer-Prediction-Using-Machine-Learning-Enhancing-Early-Detection-and-Survival-Analysis-25252
## 📌 Project Overview  
Liver cancer is one of the leading causes of cancer-related deaths worldwide. Early detection and accurate prediction of liver cancer can significantly improve survival rates and help healthcare professionals make timely decisions. This project applies machine learning techniques to predict liver cancer risk and survival outcomes using various patient-related and environmental features.  

The dataset contains **160,292 records** with features like demographics, medical history, lifestyle factors, and healthcare access. Three machine learning models — **Random Forest**, **XGBoost**, and **Logistic Regression** — were applied to develop a robust classification pipeline, and their performance was compared using key metrics like accuracy, precision, recall, and F1-score.  

---

## 📊 Business Impact  
1. **Early Detection:** Helps identify high-risk patients for timely medical intervention.  
2. **Resource Allocation:** Assists healthcare institutions in allocating resources efficiently based on patient risk.  
3. **Personalized Treatment Plans:** Supports personalized medicine by identifying key factors contributing to liver cancer risk.  
4. **Cost Reduction:** Reduces medical costs by optimizing screening and prevention strategies.  

---

## 📦 Dataset Overview  
- **Records:** 160,292  
- **Target Variable:** `Prediction` (Liver Cancer Risk Classification)  
- **Features:**  
  - **Demographics:** `Country`, `Region`, `Gender`, `Age`, `Ethnicity`  
  - **Lifestyle Factors:** `Alcohol_Consumption`, `Smoking_Status`, `Seafood_Consumption`, `Herbal_Medicine_Use`  
  - **Medical History:** `Hepatitis_B_Status`, `Hepatitis_C_Status`, `Obesity`, `Diabetes`  
  - **Healthcare Access:** `Screening_Availability`, `Treatment_Availability`, `Liver_Transplant_Access`  
  - **Environmental Factors:** `Rural_or_Urban`, `Healthcare_Access`  
  - **Outcomes:** `Incidence_Rate`, `Mortality_Rate`, `Survival_Rate`, `Cost_of_Treatment`  

---

## ⚙️ Data Preprocessing  
- Handled missing values and categorical variables with appropriate encoding techniques.  
- Balanced the dataset using **SMOTE (Synthetic Minority Over-sampling Technique)** to address class imbalance.  
- Split the data into **75% training** and **25% testing** to train the models and validate performance.  

---

## 🏗️ Modeling Approach  
1. **Random Forest:** An ensemble learning method that builds multiple decision trees and merges them to get more accurate and stable predictions.  
2. **XGBoost:** An optimized gradient boosting library that is highly efficient and commonly used in structured data.  
3. **Logistic Regression:** A simple yet effective linear model for binary classification, often used as a baseline.  

---

## 📈 Model Performance Comparison  

| Model                  | Accuracy | Precision | Recall | F1 Score |  
|------------------------|----------|------------|--------|----------|  
| **Random Forest**      | 0.7687   | High       | High   | High     |  
| **XGBoost**            | 0.7946   | High       | High   | High     |  
| **Logistic Regression**| 0.7098   | Moderate   | Moderate| Moderate|  

### Key Insights  
- **XGBoost achieved the highest accuracy (79.45%)** and overall better performance across metrics.  
- **Random Forest performed well (76.87%)** and provided a good balance between accuracy and interpretability.  
- **Logistic Regression (70.98%)** showed lower accuracy, indicating that the relationship between features and the target variable is likely nonlinear.  

---

## 📌 Business Recommendations  
1. **Adopt XGBoost for Deployment:** Its high accuracy makes it suitable for early warning systems in healthcare.  
2. **Focus on Key Risk Factors:** Features like **Hepatitis Status**, **Alcohol Consumption**, and **Healthcare Access** showed significant influence on the predictions.  
3. **Improve Data Collection:** Increasing the dataset size and enhancing feature quality can further improve model performance.  

---

