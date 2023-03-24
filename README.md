# <font color = 'teal'>Prosper Loan Data Exploration
***

- ## <font color = 'teal'>Dataset

The data set consists of a data set from Prosper Loans and carries and index of around 114, 000 anonymous borrowers and 81 details of their interaction with the loan company.The data contains general information about the borrowers loan, and in-house Prosper ratings to corroborate their findings on each borrower. The dataset is found attached in the files. Prosper Loan Data - Variable Definitions.xlsx while the link to download the csv is [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)

- ## <font color = 'teal'>General description of the project
    
 This project aims to assess a dataset and derive insights from it. There are 2 parts to it:
    
1. The exploratory data analysis: This exploration does not exclude the usual data wrangling and clean up, but its most important goal is to derive no less than 15 insights through visualizations from a dataset without being given any prior areas to look out for. It can be considered a test of skill and understanding of data visualization methods and practices.
    
2. The explanatory data analysis: This exploration digs deeper into the exploratory analysis if need be, but it is in this analysis that the key findings of the exploration are reported in a way that is comprehensive and purposeful. Additionally, I prepared a slide show to communicate the findings.
    
- ## <font color = 'teal'>Relevant and required software
    
The analysis was done with software that emphasized speed and ease of use. I used:
    
1. Anaconda - This is a package manager that links data analysis packages and libraries seamlessly
2. Jupyter Notebook
3. Matplotlib
4. Pandas
5. Seaborn
6. Python
7. Jupyer Notebook
    
- ## <font color = 'teal'>Summary of Findings

In the exploration, I found relationships between the APR and DTI of most of the features I wanted to explore. I also uncovered the relationship between credit score, and the loan and APR. The credit score was the major determinant of APR, as higher credit scores got lower APR and access to larger loans irregardless of the borrowers debt-to-income ratio.
    
I also observed the relationship between the loan term and the amount of the loan, and the delinquent amount of borrowers. The longer the loan term, the more money was given in the loan; meanwhile the less the money that was loaned, the more delinquent the account of the borrower.

Employment status was a good tell of what the DTI ratio would be like, as unemplyed people had the highest debt-to-income ratio though they were recipients of loans to a relatively similar degree as the employed.
    
The most common loan term was the 36 month term, and it was used across all credit ratings. Those with higher income and credit scores were offered the shortest loan of 12 months.

Surprisingly, those who seemed to need a loan for things like cosmetic proceedures turned out to have high credit scores and the lowest debt to income ratio, whileborrowers who needed loans for things like education turned out to be quite delinquent and were the least likely to receive loans.


- ## <font color = 'teal'>Key Insights for Presentation

For the presentation, I touched on the questions I wanted to ask most and put them out in different ways in order to show the features with the most correlation that had an actual effect on income and loan term. I looked at the BorrowerAPI, CreditScoreRangeLower and the OriginalLoanAmount.

I introduced my findings by category of plot (i.e. bivariate and multivariate) because that is where the variables began to have more meaning. I then showed the findings for each of these findings then moved on to another one, in order to create more rounded observations.
    
- ## <font color = 'teal'>Acknowledgements and credits
 
    
It goes without saying that the pandas, matplotlib and Python docs are the kings of any coding done here. A shout out to the wonderful platform Stack Overflow without which ones questions would largely be left unsolvable.
