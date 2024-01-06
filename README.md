# Customer-Dismissal_Log_Regressione
machine Learning, Python



### Introduction
- **Title:** Customer Churn with Logistic Regression
- **Purpose:** To predict when customers of a telecommunications company will leave for a competitor, enabling the company to take action to retain customers.

### Data Description
- **Data Source:** The dataset is hypothetical and is used to predict which customers will stay with the company.
- **Contents:**
  - Churn: Indicates customers who left within the last month.
  - Services: Lists services each customer has signed up for, such as phone, internet, online security, and streaming services.
  - Customer Account Information: Includes tenure, contract type, payment method, billing status, and charges.
  - Demographic Information: Covers gender, age range, and family status of the customers.

### Methodology
1. **Data Loading and Preprocessing:**
   - Libraries for data manipulation (pandas, numpy) and visualization (matplotlib) are imported.
   - The churn dataset is loaded into a pandas DataFrame for analysis.

2. **Exploratory Data Analysis:**
   - Preliminary data exploration is likely conducted to understand the dataset's structure and to summarize its main characteristics.

3. **Model Development:**
   - Logistic regression is used to create a predictive model.
   - The model is trained to identify patterns that indicate potential churn.

4. **Model Evaluation:**
   - A confusion matrix is used to evaluate the model's performance.
   - Classification metrics such as precision, recall, f1-score, and support are calculated for each class.
   - The evaluation provides insights into the model's ability to predict churn accurately.

### Evaluation Results
- **Confusion Matrix:**
  - Class 0 (Non-Churn): 31 instances with a precision of 0.93 and recall of 0.84.
  - Class 1 (Churn): 9 instances with a precision of 0.58 and recall of 0.78.
- **Performance Metrics:**
  - Accuracy: 82% of the instances were correctly classified.
  - Macro Average: Precision of 0.76, Recall of 0.81, and F1-score of 0.77.
  - Weighted Average: Precision of 0.85, Recall of 0.82, and F1-score of 0.83.

The F1 score and log loss are also discussed as performance metrics, with F1 score being the harmonic average of precision and recall, and log loss measuring the performance of a classifier with output probability values between 0 and 1.

### Conclusion
The logistic regression model shows reasonable accuracy in predicting customer churn. The model's strengths and limitations are reflected in the precision and recall scores for both classes. The high precision in predicting non-churn customers and the good recall in predicting churn customers suggest the model is useful for the company's objective to retain customers. However, the lower precision for churn predictions indicates room for improvement, possibly through more detailed feature engineering or alternative modeling techniques.
