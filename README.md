# Introduction
The Australian mortgage market has become intensely competitive, leading to agressive lending practices and potential risks to both the banking sector and borrowers. As banks engage in fierce battle to attract and retain customers, they may inadvertently lock in riskier customers on thin margins, affecting their long-term profitability. Additionally, the current home loan climate in Australia, characterized by rising interest rates, higher funding costs, and the approaching fixed-rate cliff, presents unique challenges for lenders and borrowers alike. 

To navigage these complex dynamics and mitigate potential risks, it is crucial to develop data-drive home loan origination models, segmentation, and other analytical outputs. By targeting this issue, I aim to enhance decision-making, risk management, and overall performance in the mortgage industry, ultimately benefiting banks, financial institutions, and their customers

# Challenge Overview
SAS Viya For Learners Challenge is a 5-day competition designed for students who are looking to get into and engage with machine learning problems. 

The task was to build a machine learning model using the Home Equity Loans dataset (hmeq) to predict which individuals might default on a loan. The dataset included various features, including loan amounts, existing mortgage amounts, and delinquency status. 

# Dataset Description
The dataset includes the following fields:
| Field               | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| **id**              | Row Identifier                                                             |
| **default**         | Loan outcome (`1` = client defaulted, `0` = loan repaid)                   |
| **loan_amount**     | Amount of the loan request                                                 |
| **mortgage_amount** | Amount due on the existing mortgage                                        |
| **property_value**  | Value of the current property                                              |
| **loan_reason**     | Reason for loan (`DebtCon` = debt consolidation, `HomeImp` = home improvement) |
| **occupation**      | Type of occupation                                                         |
| **occupation_length** | Years at present job                                                      |
| **derogatory_reports** | Number of major derogatory reports                                      |
| **late_payments**   | Number of delinquent credit lines                                          |
| **oldest_credit_line** | Age of oldest trade line (in months)                                    |
| **recent_credit**   | Number of recent credit lines                                              |
| **credit_number**   | Total number of credit lines                                               |
| **ratio**           | Debt-to-income ratio        
