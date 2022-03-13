# Welcome to my Exploratory Data Analysis for Telco Customer Churn
In this project, I explored data set from Telco Customer Churn to give maximum insight into the dataset and its structure, and identified influential variables. It can also help choose the most appropriate data analysis technique for a given project. The full dataset can be downloaded here: https://www.kaggle.com/blastchar/telco-customer-churn 

# Data Understanding
The Telco customer churn data contains information about a fictional telco company that provided home phone and Internet services to 7,043 customers in California. It shows which customers have left, stayed, or signed up for their service.
The data set includes information about:
- Churn is a column that list customers who left within the last month.
- Phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies are all services that each user has signed up for 
- Customer account details, such as length of service as customer, contract, payment method, paperless billing, monthly costs, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents

# Data Preparation 
- Code Used:
- Python Version: 3.7.12
- Packages: Pandas, Numpy, Matplotlib, Seaborn

# Data Cleansing
- There is numerical feature in a column which detected as float and convert to be numerical is needed 
- Missing data is detected in column `Total Charge` and since the value is less then 5%, it will be dropped
- No duplicated date is found in the dataset 

# Standard Exploratory Data Analysis
- Statistical summary of each column: numerical and categorical features 
- Univariate analysis: no outlier is detected in numerical features but imbalance ratio between categorical features  
- Bivariate analysis: using `Churn` as predictor 
- Multivariate analysis: using `Churn` as predictor

# Conclusion Finding EDA:
- Each categorical shows churn rate is always there with high user churn rate
- Most users with Month-to-month contract and Fiber optic Internet Service are churned
- Correlation netween numerical features and churn is quite strong

# Deep Dive Questions
- How is monthly count user per gender according to churn?
- How is user counted with `Internet service` and how big the ration between `Churn` YES or NO?
- How does does `PaymentMethod` and `InternetService` type affect churn?

# Conclusion Deep Dive Questions
- Monthly distribution by `gender` between `tenure` and `churn` YES and NO is similiar and no significant difference
- `Churn` YES or NO, user are coming from people with partner either with or without fiber optic the difference/ratio is not high
- In `PaymentMethod` shows electronical check with Fiber optic is likely to `Churn`
