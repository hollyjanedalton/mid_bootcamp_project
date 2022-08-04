# Hawkins Bank 


### Background 

I work for Hawkins Bank in Hawkins, Indiana as an analyst. Apart from the other banking and loan services, the bank also provides credit card services which is a very important source of revenue for the bank. The bank wants to understand the demographics and other characteristics of its customers that accept a credit card offer and that do not accept a credit card. Usually the observational data for these kinds of problems is somewhat limited in that often the company sees only those who respond to an offer. To get around this, the bank designs a focused marketing study, with 18,000 current bank customers. This focused approach allows the bank to know who does and does not respond to the offer, and to use existing demographic data that is already available on each customer.

### Objective: Build a model that will provide insight into why some bank customers accept credit card offers.



### Data: The data set consists of information on 18,000 current bank customers in the study. These are the definitions of data points provided:

Customer Number: A sequential number assigned to the customers (this column is hidden and excluded – this unique identifier will not be used directly).
Offer Accepted: Did the customer accept (Yes) or reject (No) the offer. 
Reward: The type of reward program offered for the card.
Mailer Type: Letter or postcard.
Income Level: Low, Medium or High.
#Bank Accounts Open: How many non-credit-card accounts are held by the customer.
Overdraft Protection: Does the customer have overdraft protection on their checking account(s) (Yes or No).
Credit Rating: Low, Medium or High.
#Credit Cards Held: The number of credit cards held at the bank.
#Homes Owned: The number of homes owned by the customer.
Household Size: Number of individuals in the family.
Own Your Home: Does the customer own their home? (Yes or No).
Average Balance: Average account balance (across all accounts over time). Q1, Q2, Q3 and Q4
Balance: Average balance for each quarter in the last year


### Process
1. Exploratory Data Analysis and Visualizations using Python 
2. Cleaning data (dealing with NaN values, empty values, duplicate rows, standardizing heading names, checking outliers, etc.)
3. Pre-processing data for modeling (X/y split, train/test split, encoding categoricals and scaling numericals)
4. Defining and running the model (Logistic Regression) and choosing which metric is most important (precision, recall, or f1)
5. Treating data imbalance (upsampling, downsampling, SMOTE) to improve model scores 
6. Re-running model with each data balance technique and comparing their confusion matrix and metrics
7. Drawing conclusions about data from the model
8. Hypothesis testing : Is the (average) average account balance of all Hawkins Bank customers the same as the (average) average account balance of customers who didn't take the credit card offer?
9. Data visualizations in Tableau comparing demographics of customers who did and didn't take the offer
10. Preparation of presentation to explain findings and actions to be taken by the bank to increase the percentage of customers who will take a credit card offer sent in the mail. 
11. Live Presentation in class to instructor, TA, and 10 colleagues

[Link to Tableau](https://public.tableau.com/shared/PGJZYQ4D3?:display_count=n&:origin=viz_share_link)


[Link to final presentation](https://slides.com/hollydalton/minimal)

