# GoogleAdvancedDataAnalyticsCapstone
This repository is dedicated to the code for the Google Advance Data Analytics Cert Capstone Project
### Executive Summary:

#### **Objective:**
The principal aim of this project was to build a predictive model to analyze employee churn within a company. The intent was to understand the significant features affecting employee turnover and predict which employees are likely to leave next, facilitating proactive retention strategies. 

#### **Data Overview:**
The dataset incorporated multiple features including satisfaction levels, the number of projects, average monthly hours, time spent at the company, whether the employee had a work accident, if they left the company, and if they received a promotion in the last 5 years, among others.

#### **Methods and Models:**
Various models were employed to address this business problem, including Logistic Regression, Random Forest, and XGBoost. Each model was evaluated based on its performance metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC Score, to ensure the most suitable model is selected.

#### **Key Findings:**
- **Model Selection:**
  - Random Forest and XGBoost demonstrated superior performance compared to Logistic Regression, making them more reliable for this specific scenario.
  - The ROC-AUC scores and the feature importance plots from both models facilitated understanding the contribution of each feature in determining employee churn.
  
- **Feature Importance:**
  - Satisfaction Level was the most critical feature influencing employee departure in both models, demonstrating a strong negative correlation with the target variable.
  - Last evaluation, number of projects, and average monthly hours were also considerable factors affecting the likelihood of an employee leaving.
 
 - <img width="607" alt="image" src="https://github.com/SuburbanSaturn/GoogleAdvancedDataAnalyticsCapstone/assets/112595259/c3ce08ee-4c7a-4ef3-ae2d-5e51b04e2d6c">


  - <img width="607" alt="image" src="https://github.com/SuburbanSaturn/GoogleAdvancedDataAnalyticsCapstone/assets/112595259/7c89af66-c4ca-4c64-bb54-89ef916e39d7">

  
- **Correlation Insights:**
  - Employee satisfaction showed a strong negative correlation with leaving, implying lower satisfaction leads to higher chances of leaving.
  - Features like last evaluation, number of projects, and average monthly hours showed significant positive correlations with each other, affecting employee satisfaction inversely.
  - Promotions in the last 5 years and work accidents had notable impacts on employee departure, though comparatively minor.
 
<img width="607" alt="image" src="https://github.com/SuburbanSaturn/GoogleAdvancedDataAnalyticsCapstone/assets/112595259/8c4065ef-dd34-4684-b35b-f4c0fc943a01">


#### **Recommendations:**
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
   
   - <img width="583" alt="RandomForestClassiger" src="https://github.com/SuburbanSaturn/GoogleAdvancedDataAnalyticsCapstone/assets/112595259/9f5a3456-8c2c-4f49-948c-46c90fb22583">

   - <img width="514" alt="image" src="https://github.com/SuburbanSaturn/GoogleAdvancedDataAnalyticsCapstone/assets/112595259/be68fba2-292f-436a-af42-e133eea61403">

   - <img width="514" alt="image" src="https://github.com/SuburbanSaturn/GoogleAdvancedDataAnalyticsCapstone/assets/112595259/3cbdb0b3-c0e8-49c9-bd01-6a723f79edb3">



#### **Conclusion:**
This project has successfully achieved its goals of identifying crucial factors influencing employee churn and establishing robust models to predict future turnovers. The derived insights and the predictive models can empower the company to cultivate a more conducive work environment and implement effective retention strategies, thus reducing employee turnover and fostering organizational growth.
