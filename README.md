# LendingClubCaseStudy
In this case study we’ll be analyzing past loan applicants of a company which is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures for approving loan applications. Borrowers, can easily access lower interest rate loans through a fast online interface exposed by the company. Therefore, we can assume that large number of transactions takes place in the company w.r.t the loans applications.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
LendingClub is a financial technology company that operates a peer-to-peer (P2P) lending platform. Founded in 2006, it initially allowed individuals to lend money directly to other individuals seeking personal loans, bypassing traditional financial institutions. Over time, LendingClub expanded its offerings and services.
Here’s a brief overview of what they do:
- Personal Loans: LendingClub connects borrowers with investors willing to fund their personal loans. Borrowers can use these loans for various purposes like consolidating debt, making large purchases, or covering unexpected expenses
- Business Loans: They also offer loans to small businesses. These loans help businesses with capital needs such as expansion, equipment purchases, or working capital
- Auto Refinancing: LendingClub provides refinancing options for auto loans, allowing borrowers to potentially lower their interest rates and reduce monthly payments
- Medical Financing: They offer loans specifically for medical expenses, helping patients manage costs for procedures or treatments
- Investor Opportunities: On the flip side, investors can invest in fractional shares of loans, allowing them to diversify their investments and potentially earn returns based on the interest payments from the borrowers
  
## Business Problem Statement
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss) to a bank/lender therefore we need to perform analysis w.r.t below mentioned points and provide action plans & recommendations to minimize the risk of the potential defaulters from the provided past loans comma seperated file as much as possible:

- How many risky loan applicants?
- Driving factors (or driver variables) behind loan default i.e. the variables which are strong indicators of default?
- Assess any changes in borrowers' creditworthiness
- The Cs of credit - capacity, capital, conditions, and character  

The dataset is provided by the LendingClub financial technology company that contains the complete loan data for all loans issued through the time period 2007 to 2011.

## Conclusions
- DTI impacts the repayment of the loans
- Most of the analysis confirm that loans which are approved with higher Grades has high probability of repayment therefore this concludes that banker should approve more loans with higher grades
- Customers who are taking loans for debt consolidation or credit card should be thoroughly verified against other factors such as loan Grades and DTI
- We have observed that there is negative correlation between Public recorded bankruptcies & Installments
- We have observed that there is negative correlation between Public records & loan amounts

## Technologies Used
- Python - version 3.10
- pandas - version 1.5.3
- seaborn - version 0.13.2
- matplotlib - version 3.7.0
- plotly - version 5.23.0
- numpy - version 1.23.5

## Refrences
- Pandas, Matplotlib, Plotly, Numpy offical documentation & Stackoverflow
- This project was based on Lending Club Website: https://www.lendingclub.com/


## Contact
Created by [@sahilavasthi & @saketingale] - feel free to contact us!
