**Customer Churn Prediction & Retention Analysis**

**Project Overview**
Customer churn is a major challenge for subscription-based businesses. When customers leave, companies lose recurring revenue and acquisition costs increase.
This project analyzes telecom customer data to identify the key factors behind churn and builds a machine learning model to predict which customers are likely to leave.
The goal is to help businesses take proactive steps to improve customer retention.

**Dataset**

The dataset contains telecom customer information including:
  Customer demographics
  Account details
  Service subscriptions
  Monthly and total charges
  Customer tenure
  Churn status
Each row represents a customer and whether they have churned or not.

**Target variable:**

**Churn Value**

1 → Customer churned  
0 → Customer stayed

**Project Workflow**

**1. Data Understanding**
Loaded the dataset using Python and explored the structure of the data.
Key checks performed:
  Dataset shape,
  Column data types,
  Summary statistics.
  
**2. Data Cleaning**
Cleaned the dataset to ensure accurate analysis.
Steps included:
  Handling missing values,
  Removing unnecessary columns,
  Checking for duplicate records,
  Converting categorical variables.
  
**3. Exploratory Data Analysis (EDA)**
Explored the data to understand customer behavior and churn patterns.
Key analyses:
  Churn distribution,
  Churn by contract type,
  Churn by monthly charges,
  Churn by customer tenure,
  Service usage impact on churn,
  Visualizations were created using:
  Matplotlib,
  Seaborn,
  
**4. Feature Engineering**
Prepared the data for machine learning by:
  Encoding categorical variables,
  Selecting relevant features,
  Separating features and target variables,
X → Customer features/
y → Churn Value

**5. Train Test Split**
The dataset was split into training and testing sets.
    Training data: 80%
    Testing data: 20%
This ensures the model is evaluated on unseen data.

**6. Machine Learning Model**
A Logistic Regression model was used to predict customer churn.
Why Logistic Regression?
     - Because churn prediction is a binary classification problem.
                Churn → Yes / No
The model was trained using the training dataset and evaluated on the test dataset.

**7. Model Evaluation**
Model performance was evaluated using:
  Accuracy Score
  Confusion Matrix
These metrics help measure how well the model predicts churned and retained customers.

**Key Insights**

**The analysis revealed several factors influencing customer churn:**
                  Customers with month-to-month contracts churn more frequently,
                  New customers are more likely to churn,
                  Higher monthly charges increase churn probability,
                  Customers without technical support show higher churn rates,
                  Retention Strategies.
**Based on the analysis, businesses can reduce churn by:**
                  Encouraging customers to move to long-term contracts,
                  Offering early retention incentives for new customers,
                  Providing better support services,
                  Creating bundle packages for high-charge customers.

**Tools & Technologies**
        Python
        Pandas
        NumPy
        Matplotlib
        Seaborn
        Scikit-learn
        Jupyter Notebook
