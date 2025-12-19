Customer Churn Prediction for a Telecom Company
Overview
This project predicts customer churn for a telecom company using historical customer data. Churn refers to customers leaving a service or company. By predicting churn, the company can take proactive steps to retain customers and improve overall business performance.
The project involves data cleaning, exploratory data analysis (EDA), feature engineering, model building, and evaluation using Python and popular libraries like Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

Dataset
The dataset contains customer information, including demographics, subscription details, and usage patterns. Key features include:


customerID – Unique ID for each customer


gender – Customer gender


SeniorCitizen – Whether the customer is a senior citizen


Partner – Whether the customer has a partner


Dependents – Whether the customer has dependents


tenure – Number of months the customer has stayed


PhoneService, InternetService, Contract, PaymentMethod, etc.


MonthlyCharges – Monthly payment


TotalCharges – Total payment


Churn – Target variable (Yes/No)



You can download the dataset from Kaggle Telecom Churn Dataset or include a local CSV file.


Features


Exploratory Data Analysis (EDA): Understand patterns, distributions, and relationships between features and churn.


Data Cleaning: Handle missing values, encode categorical variables, normalize numeric features.


Modeling: Train machine learning models (Logistic Regression, Random Forest, XGBoost, etc.) to predict churn.


Evaluation: Evaluate models using accuracy, confusion matrix, precision, recall, F1-score, and ROC-AUC.


Visualization: Use plots like histograms, bar charts, pie charts, and correlation heatmaps to identify trends.



Installation


Clone the repository:
git clone <repository-link>



Install required packages:
pip install -r requirements.txt



Open Customer_Churn_Prediction.ipynb in Jupyter Notebook or Google Colab.



Usage


Load the dataset.


Perform data cleaning and preprocessing.


Conduct exploratory data analysis (EDA) to identify trends.


Train and evaluate machine learning models.


Churn distribution


Monthly charges vs churn


Tenure distribution


Correlation heatmap


Contract type vs churn pie chart



Results


Best performing model: Random Forest Classifier


Accuracy: ~80–85%


Confusion matrix shows model successfully distinguishes churners from non-churners.


Insights:


Customers on month-to-month contracts are more likely to churn.


High monthly charges correlate with increased churn.


Tenure is inversely related to churn likelihood.








Author
Ronit Kumar
GitHub | LinkedIn
