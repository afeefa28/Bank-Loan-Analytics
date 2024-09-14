Loan Application Data Analysis

Project Description:
You are a data analyst at a finance company specializing in urban loans. 
The company faces two critical risks: rejecting capable applicants (losing business) and approving risky applicants (resulting in financial losses). 
This project involves using Exploratory Data Analysis (EDA) to identify patterns in loan application data that can help predict whether customers will face difficulties in repaying their loans.

The goal is to analyze customer and loan attributes to understand the key factors influencing loan defaults. This information will aid in better loan approval decisions, reducing risk while capturing more business opportunities.

Business Objectives:
  - Reduce Business Risk: Ensure capable applicants are not rejected, preventing loss of business.
  - Mitigate Financial Loss: Identify applicants at risk of default and adjust loan approval strategies (e.g., deny loan, reduce loan amount, or increase interest 
    rate).

Dataset Overview:
The dataset contains information about loan applications with various customer and loan attributes. It includes:

  - Customers with payment difficulties: Applicants with late payments of more than X days on at least one of the first Y installments.
  - Other cases: Applicants who made timely payments.

The possible outcomes for loan applications are:

  - Approved: Loan approved.
  - Cancelled: Loan application cancelled by the customer.
  - Refused: Loan application rejected by the company.
  - Unused Offer: Loan approved, but not used by the customer.
    
Analytical Tasks

1. Handle Missing Data
   Objective: Identify and address missing data to ensure data quality.
     - Use Excel functions like COUNT, ISBLANK, and IF to identify missing data.
     - Impute missing values using methods such as AVERAGE or MEDIAN.
     - Suggested Visualization: Bar/column chart showing the proportion of missing values per variable.

2. Identify Outliers
   Objective: Detect outliers that may distort analysis and decide how to handle them.
     - Use QUARTILE, IQR, and conditional formatting to identify outliers in numerical variables.
     - Apply business rules or thresholds to decide if outliers are valid or need further investigation.
     - Suggested Visualization: Box plots or scatter plots showing the distribution of numerical variables and highlighting outliers.

3. Analyze Data Imbalance
   Objective: Check for class imbalance, particularly in the target variable (loan default).
     - Use COUNTIF and SUM to calculate proportions of each class (e.g., default vs. no default).
     - Assess the degree of imbalance and its impact on the analysis.
     - Suggested Visualization: Pie chart or bar chart to visualize the distribution of the target variable.

4. Perform Univariate, Segmented Univariate, and Bivariate Analysis
   Objective: Explore the relationships between customer/loan attributes and the likelihood of default.
     - Univariate Analysis: Examine distributions of individual variables using COUNT, AVERAGE, and MEDIAN.
     - Segmented Univariate Analysis: Compare distributions across different scenarios (e.g., payment difficulties vs. no difficulties).
     - Bivariate Analysis: Explore relationships between variables using pivot tables and scatter plots.
     - Suggested Visualization: Histograms, bar charts, stacked/grouped bar charts for segmented analysis, scatter plots for bivariate analysis.

5. Identify Top Correlations for Different Scenarios
   Objective: Identify key indicators of loan default by examining correlations.
     - Segment the dataset (e.g., clients with payment difficulties vs. all other cases).
     - Use the CORREL function to calculate correlation coefficients between variables and the target.
     - Rank correlations to highlight top indicators of default for each segment.
     - Suggested Visualization: Correlation matrices or heatmaps to highlight top correlations.

By completing this project, the finance company will gain insights into customer behaviors and loan attributes that influence default risk. This analysis will help make informed decisions about loan approvals, reducing financial risks and improving business outcomes.
