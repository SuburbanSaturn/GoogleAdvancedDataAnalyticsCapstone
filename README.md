# GoogleAdvancedDataAnalyticsCapstone
This repository is dedicated to the code for the Google Advance Data Analytics Cert Capstone Project
## Executive Summary:

### **Objective:**
The principal aim of this project was to build a predictive model to analyze employee churn within a company. The intent was to understand the significant features affecting employee turnover and predict which employees are likely to leave next, facilitating proactive retention strategies. 

### **Data Overview:**
The dataset incorporated multiple features including satisfaction levels, the number of projects, average monthly hours, time spent at the company, whether the employee had a work accident, if they left the company, and if they received a promotion in the last 5 years, among others.

### **Methods and Models:**
Various models were employed to address this business problem, including Logistic Regression, Random Forest, and XGBoost. Each model was evaluated based on its performance metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC Score, to ensure the most suitable model is selected.

### **Key Findings:**
- **Model Selection:**
  - Random Forest and XGBoost demonstrated superior performance compared to Logistic Regression, making them more reliable for this specific scenario.
  - The ROC-AUC scores and the feature importance plots from both models facilitated understanding the contribution of each feature in determining employee churn.
  
- **Feature Importance:**
  - Satisfaction Level was the most critical feature influencing employee departure in both models, demonstrating a strong negative correlation with the target variable.
  - Last evaluation, number of projects, and average monthly hours were also considerable factors affecting the likelihood of an employee leaving.
 
<p float="left">
  <img src="https://github.com/SuburbanSaturn/GoogleAdvancedDataAnalyticsCapstone/assets/112595259/c3ce08ee-4c7a-4ef3-ae2d-5e51b04e2d6c" alt="image" style="width:45%; border:1px solid black; margin-right:10%;" />
  <img src="https://github.com/SuburbanSaturn/GoogleAdvancedDataAnalyticsCapstone/assets/112595259/7c89af66-c4ca-4c64-bb54-89ef916e39d7" alt="image" style="width:45%; border:1px solid black;" />
</p>
  
- **Correlation Insights:**
  - Employee satisfaction showed a strong negative correlation with leaving, implying lower satisfaction leads to higher chances of leaving.
  - Features like last evaluation, number of projects, and average monthly hours showed significant positive correlations with each other, affecting employee satisfaction inversely.
  - Promotions in the last 5 years and work accidents had notable impacts on employee departure, though comparatively minor.
 
<div style="text-align:center;">
    <img src="https://github.com/SuburbanSaturn/GoogleAdvancedDataAnalyticsCapstone/assets/112595259/8c4065ef-dd34-4684-b35b-f4c0fc943a01" alt="image" style="width:70%; border:1px solid black;"/>
</div>

### **Recommendations:**
1. **Employee Satisfaction:**
   - Focus on strategies to enhance employee satisfaction, addressing specific concerns and improving the overall work environment.
   - Regularly assess employee satisfaction levels to identify and mitigate potential issues proactively.

2. **Workload Management:**
   - Establish a balanced workload by managing the number of projects and average monthly hours to prevent employee burnout and dissatisfaction.

3. **Employee Development:**
   - Foster career development opportunities, ensuring that promotions and recognitions are distributed fairly and transparently.

4. **Model Utilization:**
   - Employ the predictive models, particularly Random Forest or XGBoost, to forecast potential employee churn, allowing for timely interventions.
   - Continuously update and refine the models to adapt to evolving organizational dynamics and employee behaviors.

<div style="display: flex; justify-content: center; align-items: center;">
    <img src="https://github.com/SuburbanSaturn/GoogleAdvancedDataAnalyticsCapstone/assets/112595259/0b3b3427-709d-4c1d-b6e3-70c6cc56a228" alt="RandomForestTune" style="width:400px; margin-right:2%; border:1px solid black;"/>
    <img src="https://github.com/SuburbanSaturn/GoogleAdvancedDataAnalyticsCapstone/assets/112595259/0bd72521-3faf-44af-ab92-4a8f53040813" alt="XGBOOSTTUNE" style="width:400px; border:1px solid black;"/>
</div>

<div style="display: flex; justify-content: center; align-items: center;">
    <img src="https://github.com/SuburbanSaturn/GoogleAdvancedDataAnalyticsCapstone/assets/112595259/a569c13e-f317-4211-8f5b-9c1542067c14" alt="RandomForestConfusion Matrix" style="width:400px; margin-right:2%; border:1px solid black;"/>
    <img src="https://github.com/SuburbanSaturn/GoogleAdvancedDataAnalyticsCapstone/assets/112595259/64ed3be0-c4dc-4bce-aa5c-4cb657ec7003" alt="Screenshot 2023-09-27 at 1 08 24 PM" style="width:400px; border:1px solid black;"/>
</div> 

<div style="display: flex; justify-content: center; align-items: center;">
    <img src="https://github.com/SuburbanSaturn/GoogleAdvancedDataAnalyticsCapstone/assets/112595259/4cdf6d34-705d-4cf2-9f6f-8c1beedeeb0f" alt="Random Forest ROC" style="width:400px; margin-right:2%; border:1px solid black;"/>
    <img src="https://github.com/SuburbanSaturn/GoogleAdvancedDataAnalyticsCapstone/assets/112595259/c3cfee6a-0306-46b1-9c39-511d97578380" alt="XGBOOSTROC" style="width:400px; border:1px solid black;"/>
</div>


## **Conclusion:**
This project has successfully achieved its goals of identifying crucial factors influencing employee churn and establishing robust models to predict future turnovers. The derived insights and the predictive models can empower the company to cultivate a more conducive work environment and implement effective retention strategies, thus reducing employee turnover and fostering organizational growth.
