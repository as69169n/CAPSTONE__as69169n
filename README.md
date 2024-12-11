# Heart Disease Risk Prediction Project

## **Overview**

Heart disease is the leading cause of mortality in the United States, responsible for approximately 647,000 deaths annually. This project leverages the **Heart Disease Health Indicators Dataset** from the 2015 BRFSS survey to explore health indicators influencing heart disease risk and develop machine learning models for prediction. By combining statistical hypothesis testing and predictive modeling, the study aims to provide actionable insights for early detection and prevention.

---

## **Key Features**
1. **Statistical Analysis**:
   - Conduct hypothesis testing to identify significant correlations between health indicators and heart disease risk.
   - Explore relationships between factors such as mental health, physical activity, and healthcare accessibility.
   
2. **Machine Learning Models**:
   - Regression models to predict mental health outcomes.
   - Classification models to predict heart disease occurrence based on health indicators like blood pressure, cholesterol levels, and smoking status.
   
3. **Model Optimization**:
   - Employ hyperparameter tuning and validation to enhance model accuracy and generalizability.

4. **Actionable Insights**:
   - Provide healthcare professionals with data-driven recommendations for early intervention and risk reduction.

---

## **Dataset**

**Source**: Behavioral Risk Factor Surveillance System (BRFSS) 2015 Survey  
**Size**: ~250,000 records  
**Key Variables**:
- **Demographics**: Age, Sex, Income, Education Level
- **Health Indicators**: 
  - Physical health metrics: BMI, High Blood Pressure, High Cholesterol
  - Behavioral factors: Smoking, Physical Activity, Diet
  - Accessibility: Ability to afford healthcare
  - Target Variable: History of heart disease or myocardial infarction

---

## **Analysis Highlights**

### **Statistical Insights**
- Significant associations identified between heart disease and:
  - **Lifestyle factors**: Smoking, healthy eating, physical activity
  - **Socioeconomic indicators**: Education and income levels
  - **Physical and mental health**: High blood pressure, difficulty walking, poor mental health

### **Modeling Results**
1. **Regression Models**:
   - Predict mental health outcomes with selected health indicators.
   - Achieved limited explanatory power (R² = 0.161), indicating the need for additional features.

2. **Classification Models**:
   - **XGBoost** outperformed other models, achieving the highest ROC-AUC score of **0.92**.
   - PCA improved model performance by balancing precision and recall, particularly in minority class predictions.

---

## **Key Findings**
- **Risk Factors**:
  - High Blood Pressure, General Health, and Difficulty Walking are the strongest predictors of heart disease.
  - Lifestyle changes (e.g., healthy eating, regular exercise) significantly reduce risk.

- **Model Limitations**:
  - Class imbalance (minority representation for heart disease cases) hindered model performance, despite oversampling techniques.

- **Socioeconomic Impact**:
  - Income and education levels influence heart disease risk, highlighting the importance of accessible healthcare and education.

---

## **Future Scope**
1. **Advanced Resampling Techniques**:
   - Implement SMOTE to improve minority class representation and prediction accuracy.
2. **Deep Learning Models**:
   - Explore neural networks for capturing complex, non-linear relationships.
3. **Expanded Datasets**:
   - Integrate additional years of BRFSS data or datasets from other healthcare studies for broader generalizability.
4. **Feature Engineering**:
   - Investigate new features to improve regression model explanatory power.
