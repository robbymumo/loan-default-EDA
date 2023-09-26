## EDA 
### Section 1: Summary Statistics and Distributions:

#### 1. Calculate basic summary statistics 
(mean, median, mode, standard deviation) for numerical columns like loan_amnt, annual_inc, etc.
Create histograms and box plots to visualize the distribution of loan amounts, annual income, and other key variables.
Calculate and visualize the percentage of loans that were fully repaid (loan_status) versus those that defaulted.
#### 2. Categorical Variables Analysis:
Explore the distribution of categorical variables like home_ownership, purpose, and verification_status.
Calculate the count and percentage of loans for each category within these variables.
Visualize these distributions using bar plots or pie charts.

#### 3. Time-Series Analysis:
Convert date columns (issue_d, last_pymnt_d, etc.) to datetime objects.
Create a time-series plot of loan issuance over time to identify trends.
Analyze loan performance over time, such as the percentage of loans that default or are paid off.

### Section 2: Advanced and Interesting EDA Activities:
#### 1. Loan Default Analysis by Features:

Perform a deeper analysis of loan defaults by exploring relationships between default rates and features like int_rate, emp_length, dti, and annual_inc.
Use statistical tests or visualizations to identify significant differences in default rates among different groups.

#### 2. Feature Engineering and Correlation Analysis:
Create new features or transformations based on domain knowledge, such as debt-to-income ratio (dti) or loan-to-income ratio.
Compute correlations between features and the target variable (repay_fail) to identify which features are most influential in loan repayment.

#### 3. Geospatial Analysis:
Utilize geographical information such as zip_code and addr_state to perform geospatial analysis.
Visualize loan distribution and loan performance on a map to identify geographic trends and hotspots.
Analyze whether the location has an impact on loan defaults or interest rates.