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
- Analysis to find high-quantity data with univariate, bivariate, and multivariate with `Churn` as predictor 
- Use deep dive questions to find high-quality data

