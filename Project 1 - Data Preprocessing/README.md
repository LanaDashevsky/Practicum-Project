
# Project - Report for a bank’s loan division

**Project Description**
Our customer - the bank loan division. We want to figure out whether specified customers' characteristic affects the repaying of a loan on time. The data we work with is customers’ creditworthiness from the bank. The result of the research will be taken in the credit scoring model - a special system that evaluates the ability of a potential borrower to repay the loan.

**Technologies and Tools** - Python, Jupyter, Pandas, Numpy, Seaborn, Matplotlib, Plotly

**Goal:** To prepare a report for a bank’s loan division.

## Tasks
The main goal of the project was to test the following hypotheses:
  1. Is there a connection between having kids and repaying a loan on time?
  2. Is there a connection between marital status and repaying a loan on time?
  3. Is there a connection between income and repaying a loan on time?
  4. Is there a connection between education and repaying a loan on time?
  5. Is there a connection between income type and repaying a loan on time?
  6. How do different loan purposes affect on-time loan repayment?

## Overall Conclusion
We worked with data on bank clients' total income, loan purpose, age, marital status, and number of children to prove our hypotheses. We filled in the missing values in the total income column with the median by age category, we separated the purpose of the loan into car purchase, marriage, education, and real estate. We prepared the data for work and changed about 10% of all missing values in data. We grouped the main data table by purpose, marital status, numbers of children and income category. We found default rates for each category in each of these columns.

## Recommendations
The lowest default rate for loans for the purchase of real estate - 7.23%, the next default rate goes for wedding loans - 8%. Car and education loans are the most problematic, with a default rate of just over 9%.
People with high (32k+) and low (less 17k) total incomes return the best loans - about 7.5%, people with the medium total income ranging from 17k to 32k have a default rate of about 8.5%.
The highest default rate for people who are unmarried or in "civil partnership" - about 9% for both groups, the lowest default rating for widows/widowers is 6.6%, and the lowest rate is for married and divorced groups (7.5% and 7.1%)
People who do not have children have a lower default rate (7.5%) than those who have children (range 9-9.5% depending on the number of children)
Based on our data, the bank should pay attention to the categories - married, divorced or widows / widowers, without children, with a high(32k+) or less 17k total income, the purpose of which is to buy real estate. The problematic group is - unmarried or civil partnership, with children, with an average income (18-32k), as well as for the purpose of a loan - education or buying a car.

LINK: [Detailed Project](Project_1_Data_Preprocessing.ipynb)

## Scope of activities 
Banking / FinTech, Startups, Tech-company, Business services [b2b], Lending, Financial analyst.


## Tags 
Exploratory Data Analysis, Python, Pandas, Numpy, Matplotlib, Seaborn, Research, Data processing, Duplicates, Missing values, Categorization, Decomposition, Lemmatization.

