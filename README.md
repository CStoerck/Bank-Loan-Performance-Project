# Bank Loan Analysis Portfolio Project

## Table of Contents

- [Project Overview](#project-overview)
- [Data Overview](#data-overview)
- [Tools Used](#tools-used)
- [Methodology](#methodology)
  - [Data Cleaning and Preparation](#data-cleaning-and-preparation)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Dashboard Components](#dashboard-components)
- [Key Metrics and Insights](#key-metrics-and-insights)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [Contact](#contact)

## Project Overview
This project analyzes a bank's loan portfolio to gain insights into key financial metrics and assess the risk associated with different loans. The primary KPIs analyzed are total loan applications, total funded amount, total received amount, average interest rate, and average debt-to-income ratio (DTI). The analysis aims to provide actionable recommendations for improving loan management and decision-making.

![bank-loan-dashboard-preview](https://github.com/user-attachments/assets/ccaf7eab-4467-4edc-bb4b-498f3c775569)

## Data Overview
The dataset used in this project includes the following columns:

- **address_state**: State where the borrower resides
- **application_type**: Type of loan application (individual or group)
- **employee_length**: Duration of the borrower's employment
- **employee_title**: Job title of the borrower
- **grade**: Risk classification based on creditworthiness
- **home_ownership**: Indicates if the borrower rents, owns, or has a mortgage
- **issue_date**: Date the loan was issued
- **last_credit_pull**: Date of the last credit check
- **last_payment_date**: Most recent loan payment date
- **loan_status**: Current state of the loan
- **next_payment_date**: Estimated date of the next loan payment
- **purpose**: Reason for the loan
- **sub_grade**: Refined risk assessment within a grade
- **term**: Duration of the loan
- **verification_status**: Indicates if the borrower's financial information has been verified
- **annual_income**: Borrower's yearly earnings
- **DTI (Debt to Income Ratio)**: Measures the borrower's capacity to take on additional debt
- **installment**: Fixed payment amount for loan repayment
- **interest_rate**: Rate charged on the loan
- **loan_amount**: Total amount of the loan
- **total_amount_paid**: Total amount repaid by the borrower

## Tools Used
- **Excel**: For data cleaning, preparation, and preliminary analysis.
- **SQL**: For querying and managing the data.
- **Tableau**: For data visualization and dashboard creation.

## Methodology
#### Data Cleaning and Preparation
Data cleaning and preparation were performed in Excel, ensuring the dataset was free of inconsistencies and missing values. This step involved:
- Validating data integrity.
- Removing duplicate values.
- Normalizing data formats.
- Filtering out irrelevant records.
- Preparing the dataset for analysis and visualization.

#### Exploratory Data Analysis
EDA was conducted to uncover trends, patterns, and key insights. The focus areas included:
- **Loan Applications:** Analysis of application trends over time and across states.
- **Funded Amount vs. Received Amount:** Assessing the bank’s liquidity and loan performance.
- **Loan Grade:** Examining borrower financial health and its affect on loan performance.
- **Loan Categorization:** Segmenting loans into 'Good' and 'Bad' based on repayment status.

#### Dashboard Components
- **Interactive Filters:** Explore data by various dimensions, such as loan status, purpose, and geographical location.
- **Advanced Visualizations:** Uncover complex relationships and trends within the loan portfolio.

## Key Metrics and Insights
- **Total Loan Applications:** Insights into monthly application trends.
- **Total Funded Amount vs. Received Amount:** Identification of discrepancies in loan funding and actual repayment.
- **Average Interest Rate and DTI:** Assessment of borrowers' ability to manage debt.
- **Loan Categorization:** Classification of loans into performing and non-performing, highlighting potential risks.

## Results
The analysis revealed crucial insights into loan application trends, funding patterns, and repayment behaviors. Key findings include:
- Seasonal trends in loan applications with the end of the year exhibiting more loan applications.
- Geographical disparities in loan funding and approval rates. States with larger populations naturally have more loan applications and funded amounts.
- The impact of DTI and interest rates on loan performance.

## Recommendations
Based on the analysis, the following recommendations are made:
- **Optimize Loan Terms:** Tailor loan offerings based on borrower profiles to minimize defaults.
- **Enhance Risk Management:** Focus on improving the accuracy of credit risk assessments.
- **Targeted Marketing:** Use geographic and demographic insights to develop more effective loan products.

## Limitations
- The analysis is based on historical data, which may not fully predict future trends.
- Certain data fields may have inherent biases, affecting the accuracy of insights.

## Contact
- **Cody Stoerck**: [LinkedIn](https://www.linkedin.com/in/codystoerck/) | cstoerck@gmail.com

---

[**Link to visualization**](https://public.tableau.com/app/profile/cody.stoerck/viz/BankLoanAnalysisDashboard_17091319168180/SUMMARY)

