# Risk Analytics Exploratory Data Analysis
![Python](https://img.shields.io/badge/python-3670A0?style=plastic&logo=python&logoColor=yellow)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=plastic&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=plastic&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=plastic&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-%23ffffff.svg?style=plastic&logo=Matplotlib&logoColor=black)


## Introduction 

The loan providing companies find it hard to give loans to the people due to their insufficient or non-existent credit history. Because of that, some consumers use it to their advantage by becoming a defaulter. 

In this project, we will use Exploratory Data Analysis(EDA) to help a consumer finance company which specialises in lending various types of loans to urban customers in identifying the risk factors involved with clients having high defaulter rate and help the company to make a decision for loan approval. Identify if the applicant is likely to repay the loan so it does not result in loss of business to the company or financial loss of the company.

## Problem Statement

When a company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
  - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
  - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the   company.
  
## Business Objectives 

- Ensuring that customers capable of repaying the loan are not rejected. 
- Find the driving factors behind loan default. 
- Identify patterns which indicate if a client has difficulty paying their instalments so the company can take decisions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate. 

## Approach

### 1. Data Import and Inspection 
- There are two datasets:
    * First, contains all the information of the client at the time of application. The data is about whether a client has payment difficulties.
    * Second, contains information about the client’s previous loan data. It contains the data on whether the previous application had been Approved,   Cancelled, Refused or Unused offer.
      
- Understanding the data
     
### 2. Sanity Check 
- Outlier/missing value treated.
- Upon deciding the threshold for missing values columns having more than 35% missing values were dropped.
    
### 3. Data Visualization
- Univariate analysis 
- Bivariate analysis
- Segmented univariate analysis 
    
## Key Findings 

   - Higher percentage of female defaulters, contributing to 57%. Also, their number is high in Non - defaulters category, making higher number of female taking out loan. 
   - We see a higher percentage of clients defaulting who do not own a car. But even for non defaulters the percentage is higher who do not own a car. We can deduce that the chances of a person not owning a car can default is more.
   - We see that higher percentage of defaulters do not own a real state where as non defaulters who own a real state percentage is higher. We can make an assumption that people taking out loan for real state do not default as often due to higher loan amount.
   - Clients belonging to very low and low income category range constitutes of 49.7%(in total) of all defaulters.
   - People in the age group 20-40 default more compared to other age group. We can say that number of defaulters decrease for age more than 40.
   - 73% of defaulters are from client city rating 2. But we also see that approx 75% from client city with rating 2 are non defaulters. We can say that clients from city rating 2 take loan more often. From city rating 3 also we have 20% defaulters which should also be looked at while deciding for giving loan.
   - Married people have highest percentage of defaulters. As the percentage is high in non defaulters as well we can say that married clients apply for loan more compared any other.
   - We see a slight higher percentage of Single/Unmarried defaulters as well, which requires are attention for more data gathering for such individuals.
   - People with House/apartment apply for more loans for e.g home loans etc so their defaulter percentage is high as well. We see 7% people living with parents contribute to defaulters. We can assume their living cost to be high due to more family members and hence defaulters.
   - Major defaulters are from occupations Labour, sales staff and drivers. Also, the non defaulter percentage from labourers is high so we can say they take out loan more often.
   - We can observe that for family count more than 3 is more likely to take a loan as well as more likely to defaulter.
   - We can see that credit amount and the goods price are positively correlated, and we get the correlation between them as 98.7%.
   - More defaulters are present when Credit Amount is low.
   - For Higher Goods price and higher Credit Amount, number of non defaulters are more so they are less likely to default.
   - It is interesting to see that for a consumer loan the approved number is quite high where as very low cancelled loan for the consumer loans. There is good number of cash loan also getting cancelled.
   - We observe that clients who are repeater are more likely to get their loan approved as compared to New or Refreshed client.
   - High number of female loans getting approved compared to male. On contrary more female would have applied for loan as well.
   - Clients whose loan got approved but they defaulted is highest among approved loan amounts. We also see clients whose loans have gotten cancelled and refused might default more.

## Conclusion 

  - Clients who are more likely to repay the loan:
      * Female clients
      * Clients whose previous loan has been approved.
      * Clients with high income category.
      * Clients with age more than 40.
      * Consumer loans
      * Repeater clients of the company.
      * High credit amount
      * Clients who own a car or a real state.
  - Clients who are less likely to repay the loan:
      * Male Clients
      * Labourers, drivers and sales staff have high defaulter percentage.
      * Clients with age between 20-40
      * Low credit amount
      * Cash loans
      * Low income category
