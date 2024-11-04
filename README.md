# Loan Portfolio Insights

## Overview
This project provides an interactive Power BI dashboard for analyzing loan portfolio data from a financial institution. The dashboard offers insights into loan issuance trends, loan statuses, risk indicators, and borrower demographics. It is designed to help loan officers, risk managers, product development teams, and executives make data-driven decisions to improve loan product offerings and manage risk.

## Table of Contents
- [Overview](#overview)
- [Project Objectives](#project-objectives)
- [Dataset Description](#dataset-description)
- [Key Visualizations](#key-visualizations)
- [Insights and Findings](#insights-and-findings)
- [Usage](#usage)
- [Target Audience](#target-audience)
- [Recommendations](#recommendations)
- [Technologies Used](#technologies-used)
- [Future Enhancements](#future-enhancements)

## Project Objectives
- To understand loan issuance trends and borrower profiles.
- To identify key loan purposes and borrower income levels.
- To analyze loan statuses and risk metrics (e.g., Debt-to-Income (DTI) ratio) for better risk management.
- To provide actionable insights to enhance loan product offerings and manage the loan portfolio.

## Dataset Description
This analysis uses two main tables:
1. **Customer Data**: Contains borrower demographic information, employment details, loan grade, loan status, etc.
2. **Loan Data**: Provides details on loan amounts, interest rates, loan terms, loan issuance dates, and other financial information.

### Key Columns in the Dataset
- `loan_id`: Unique identifier for each loan.
- `loan_amnt`: Original loan amount.
- `term_months`: Loan term in months.
- `int_rate`: Interest rate of the loan.
- `loan_status`: Current status of the loan (e.g., Current, Fully Paid, Charged Off).
- `dti`: Debt-to-Income ratio, indicating the borrower's financial stability.
- `reason`: Purpose of the loan (e.g., Debt consolidation, Home improvement).
- `grade` and `sub_grade`: Credit risk grade assigned to each loan.

## Key Visualizations
1. **Summary Cards**: 
   - Total Loan Applications
   - Total Funded Amount
   - Average Interest Rate
   - Average DTI

2. **Slicers**:
   - Date Range: Filter loans by issuance date.
   - Loan Grade: View metrics for specific loan grades.
   - Loan Term: Select 36- or 60-month loans.
   
3. **Charts**:
   - **Trend Line for Loan Issuance**: Displays loan issuance over time.
   - **Loan Status Breakdown**: Pie chart to show distribution of loan statuses.
   - **Loan Purpose Distribution**: Bar chart for primary reasons for loan applications.
   - **Loan Grade Analysis**: Median loan amounts across grades to analyze credit risk.
   - **DTI and Loan Status**: Bar chart showing the average DTI ratio for each loan status.
   - **Interest Rate by Loan Purpose**: Average interest rate per loan purpose.

## Insights and Findings
1. **Loan Issuance Trends**: Visualize seasonal patterns and growth in loan issuance over time.
2. **Loan Purpose and Risk**: Debt consolidation is the most common loan purpose, highlighting borrower needs.
3. **Credit Risk Levels**: Loan grades and sub-grades provide insights into creditworthiness, with higher-grade loans generally having lower interest rates.
4. **Loan Status and DTI**: Higher DTI ratios are associated with loans that are late or charged off, indicating potential risk.

## Usage
1. Clone this repository.
   ```bash
   git clone https://github.com/8787r/Loan-Porfolio-Insights
   ```
2. Open the Power BI file (`LoanPortfolioDashboard.pbix`) in Power BI Desktop.
3. Review the dashboard and interact with the slicers to filter the data.

## Target Audience
The primary audience for this dashboard includes:
- Loan Officers and Underwriting Teams
- Risk Management Team
- Product Development and Marketing Teams
- Senior Management and Strategy Planners
- Compliance and Financial Analysts

## Recommendations
- **Focus on High-Demand Loan Purposes**: Develop specialized loan products or promotional strategies for top purposes like debt consolidation and credit card refinancing.
- **Monitor High-Risk Segments**: Pay closer attention to high-DTI loans and lower-grade loans to mitigate default risks.
- **Optimize Loan Terms and Interest Rates**: Adjust loan terms and rates for riskier grades to improve portfolio health.

## Technologies Used
- **Power BI**: For data visualization and dashboard creation.

## Future Enhancements
- **Real-Time Data Refresh**: Implement automated data refresh to provide real-time loan portfolio insights.
- **Advanced Risk Analysis**: Include machine learning models to predict default probabilities based on borrower demographics and loan characteristics.
- **Enhanced User Interactivity**: Add more detailed drill-downs and interactive elements to allow users to explore data at a granular level.
