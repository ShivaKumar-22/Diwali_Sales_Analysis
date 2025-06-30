# Diwali_Sales_Analysis

✅ Step-by-Step Process of the Project
Importing Libraries

Used: pandas, numpy, matplotlib, seaborn

Purpose: Data manipulation and visualization

Loading the Dataset

File: 'Diwali Sales Data.csv'(DIWALI_SALES_ANALYSIS.ipynb)

Encoding used: unicode_escape to handle special characters.

Basic Data Exploration

Checked shape, used .info(), .head(), .describe()

Identified missing values and data types

Data Cleaning

Removed unnecessary columns like 'Status', 'unnamed1'

Dropped null values to ensure clean analysis

Data Transformation

Converted Amount column to int type using:


df['Amount'] = df['Amount'].astype('int')
Exploratory Data Analysis (EDA)

Gender-wise Analysis:

Countplot and barplot to analyze purchases and total spending by gender

Age-wise Analysis:

Compared age groups in terms of total purchases and spending

State-wise Analysis:

Identified top states by total orders and revenue

Marital Status Analysis:

Checked the impact of marital status on spending

Occupation Analysis:

Visualized which professions spend more

Product Categories:

Found top-selling categories and products

Visualization Tools Used

seaborn barplots and countplots

matplotlib for customized plotting

📊 Key Insights from the Project
Females spent slightly more than males despite fewer purchases.

Young Adults (26–35 years) were the top buyers in terms of both quantity and amount.

Uttar Pradesh, Maharashtra, and Karnataka were the top 3 states with the highest revenue.

Married people purchased more, contributing higher to sales.

Working Professionals and Entrepreneurs were the top spenders.

Food, Clothing, and Electronics were the most popular product categories.

The "Laptop" and "Smartphone" categories appeared frequently among top products.
