# Summary
This project involves predicting customer churn for a telecommunications company using machine learning techniques. The objective is to build a predictive model that accurately classifies whether a customer will churn based on various features. I performed exploratory data analysis (EDA) to understand the dataset, processed and encoded categorical variables, handled missing values, and engineered new features to enhance model performance. Various models, including Logistic Regression, Random Forest, and Gradient Boosting, were compared, with Gradient Boosting emerging as the best-performing model. Hyperparameter tuning was conducted to further refine the Gradient Boosting model, and cross-validation was used to evaluate its performance.

# Problem Definition
Customer churn is a critical issue for telecommunications companies, as losing customers directly impacts revenue and business sustainability. The goal of this project is to predict customer churn using historical data, enabling the company to identify customers at risk of leaving and take proactive measures to improve retention. By developing an accurate churn prediction model, the company can optimize marketing strategies, enhance customer service, and ultimately reduce churn rates.

# Data Source
The dataset used in this project is the "Telco Customer Churn" dataset, which is publicly available on Kaggle. It contains information about customer demographics, account details, and service usage. Key features include tenure, monthly charges, total charges, and various categorical variables related to customer subscriptions and services. This dataset provides a comprehensive view of customer behavior and service usage, making it suitable for churn prediction modeling.

# Methodology
**Data Cleaning and Preprocessing:** The dataset was first cleaned to handle missing values, specifically in the TotalCharges column, which was converted to numeric and imputed with the median value. Categorical variables were encoded using One-Hot Encoding to convert them into a numerical format suitable for machine learning models.

**Exploratory Data Analysis (EDA):** EDA was conducted to understand the distribution of key features and their correlations. Histograms and a correlation matrix were used to visualize and interpret the data.
Feature Engineering: New features were created to enhance model performance, including aggregating service subscriptions and creating interaction features such as the product of tenure and monthly charges.

**Data Splitting and Standardization:** The dataset was split into training and test sets. Features were standardized using StandardScaler to ensure that all features contribute equally to the model.

**Model Training and Evaluation:** Several machine learning models were compared, including Logistic Regression, Random Forest, and Gradient Boosting. The Gradient Boosting model was selected as the best performer. Hyperparameter tuning was performed using Grid Search to optimize the model's performance. Cross-validation was used to assess the reliability of the models.

**Final Model Assessment:** The final model's performance was evaluated on the test set, and metrics such as accuracy, classification report, and confusion matrix were used to assess its effectiveness in predicting customer churn.
