# Bank-Loan-Analysis
Bank Loan Analysis Project

Overview
This is end to end  Data Analysis Python project that provides an analysis of bank loan data, including key insights into loan applications, funding amounts, loan statuses, and borrower characteristics. The dataset contains various details like loan amounts, applicant information, repayment history, and more, which are used to generate visual insights and key metrics.

Key Features
Loan Applications Overview: Total number of loan applications and MTD (Month-to-Date) applications.
Total Funded Amount: Analyzes the total loan amount funded, both overall and MTD.
Repayment Overview: Total payments received, and MTD payments.
Loan Status Breakdown: Good loans (Fully Paid, Current) vs. Bad loans (Charged Off).
Interest Rate and Debt-to-Income Ratio: Average interest rates and debt-to-income ratios.
Time-Series Analysis: Monthly trends for loan applications, funded amounts, and repayments.
Geographic Breakdown: Total funded amounts by state.
Loan Purpose and Home Ownership: Funded amount breakdown by loan purpose and home ownership.

Dataset Columns
The dataset contains the following key columns:
id: Unique identifier for each loan application.
address_state: The state where the borrower resides.
application_type: Type of loan application (individual or joint).
emp_length: Number of years the borrower has been employed.
emp_title: Job title of the borrower.
grade: Loan grade indicating creditworthiness.
home_ownership: Type of home ownership (rent, own, mortgage).
issue_date: Date when the loan was issued.
last_credit_pull_date: Date when the borrower's credit was last pulled.
last_payment_date: Date when the last payment was made.
loan_status: Current status of the loan (e.g., Fully Paid, Charged Off).
next_payment_date: Next payment due date.
member_id: Unique identifier for the borrower.
purpose: Purpose of the loan (e.g., debt consolidation, home improvement).
sub_grade: Loan grade classification.
term: Loan term in months (e.g., 36, 60 months).
verification_status: Income verification status.
annual_income: Borrower's annual income.
dti: Debt-to-income ratio.
installment: Monthly installment amount.
int_rate: Loan interest rate.
loan_amount: Amount of the loan.
total_acc: Total number of credit accounts the borrower has.
total_payment: Total amount received from the borrower.

Visualizations and Insights
The analysis generates various visualizations to help understand loan funding, repayments, and applications:
Total Funded Amount by Month: Shows trends in the total amount funded each month.
Total Received Amount by Month: Illustrates the repayments received each month.

Loan Applications by Month: Displays the number of loan applications received each month.
Good vs. Bad Loans: Breakdown of good loans (Fully Paid/Current) vs. bad loans (Charged Off).

Total Funded Amount by State: A bar chart showing funded amounts by state.

Loan Purpose Breakdown: Shows the amount funded based on loan purpose.

Home Ownership Breakdown: Treemap showing funded amounts by home ownership type.

Technologies Used
Python: Programming language used for data analysis.
pandas, numpy: Libraries for data manipulation and calculations.
matplotlib, seaborn: Libraries for creating visualizations.
plotly: For interactive visualizations.

