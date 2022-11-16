# Machine learning to improve the sign-up rate of a credit card offer 
<img src="https://github.com/hollyjanedalton/mid_bootcamp_project/blob/master/Screen%20Shot%202022-11-15%20at%201.35.52%20PM.png" width="400">


[Click for recording of final presentation](https://ironhack.zoom.us/rec/play/c6ucxea0L1FRymi22-HQIhLXEd0XXUEZ-UA09dp6-fEhTWg85DyzrGk4PDZh_OIgtkmFjIVaJAETo3Es.OP5nsmMXammFuYxH?startTime=1659442370000&_x_zm_rtaid=6Tdq7qw8T7SqVo45JcLH7w.1659608455628.2584d09c99ce9303c53496b1812d7126&_x_zm_rhtaid=554)

[Click to view presentation slides](https://slides.com/hollydalton/minimal/fullscreen)

---

### Background 

I'm a risk analyst for Hawkins Bank in Hawkins, Indiana. In order to better understand the demographics of its clients that accept a credit card offer, Hawkins Bank has designed a focused marketing study, where they sent 18,000 current bank clients a credit card offer in the mail. This focused approach allows the bank to know who does and does not respond to the offer, and to analyze this data with existing demographic data of each customer.

### Objective:  

In this mailer campaign, 6% (or about 1,000 customers) signed up for the credit card after receiving the offer. How can we increase this number next time? 

I will build a classification model to predict which bank customers will sign up for a credit card offer sent by mail. Then I will use this model along with my analysis to suggest actionable insights to Hawkins Bank to improve the sign-up rate of their next credit card mailer campaign.

---

### Main Insights:

#### Type of mailer
50% of customers were sent the offer by postcard and 50% by mailed envelope. 
Customers responded better to the credit card offer sent by postcard rather than by mailed envelope. 70% of customers who took the credit card offer had been sent the offer by postcard. 

<img src="https://github.com/hollyjanedalton/mid_bootcamp_project/blob/master/postcard%20vs%20letter.png" width="300">

##### Action: Save money and paper by sending 100% of the offers by postcard next time. 

#### Type of Rewards Program
The bank offers three Rewards programs to go along with the credit card- Cash back, Points, or Air Miles. 
The majority of customers who accepted the credit card offer were those sent the Air Miles Rewards program. 

<img src="https://github.com/hollyjanedalton/mid_bootcamp_project/blob/master/rewards%20program.png" width="150">


##### Action: Instead of offering each rewards program equally, offer a higher proportion of the Travel Rewards. 

#### Demographic Features of Bank Customers 
For this part of the analysis, we will be comparing the two demographics of the 2 groups of customers- those customers who signed up for the credit card offer after receiving the mailer (about 1,000 customers, or 6%) verses those customers who didn't sign up for the credit card offer after recieving the mailer (about 17,000 customers, or 94%)

Quick reminder: the objective of this project is to provide actionable insights to increase this percentage from 6% to 15%

The data contained 14 demographic features of each client, such as their average annual account balance, household size, and whether or not they have overdraft protection. However, two features seemed particularly indicative of determining whether or not a customer would sign up for the credit card offer:

#### Income Level and Credit Rating

<img src="https://github.com/hollyjanedalton/mid_bootcamp_project/blob/master/income%20levels%20comparison.png" width="400">


---

#### Data: The data set consists of 14 demographic features on 18,000 current bank customers:

- **Customer Number**: A sequential number assigned to the customers.
- **Offer Accepted**: Did the customer accept (Yes) or reject (No) the offer. 
- **Reward**: The type of reward program offered for the card.
- **Mailer Type**: Letter or postcard.
- **Income Level**: Low, Medium or High.
- **Number of Bank Accounts**: How many non-credit-card accounts are held by the customer.
- **Overdraft Protection**: Does the customer have overdraft protection on their checking account(s) (Yes or No).
- **Credit Rating**: Low, Medium or High.
- **Number of Credit Cards Held**: The number of credit cards held at the bank.
- **Number of Homes Owned**: The number of homes owned by the customer.
- **Household Size**: Number of individuals in the family.
- **Own Your Home**: Does the customer own their home? (Yes or No).
- **Average Balance**: Average account balance (across all accounts over time). Q1, Q2, Q3 and Q4
- **Balance**: Average balance for each quarter in the last year

---

#### Process
1. Exploratory Data Analysis and Visualizations using Python 
2. Cleaning data (dealing with NaN values, empty values, duplicate rows, standardizing heading names, checking outliers, etc.)
3. Querying in SQL 
4. Pre-processing data for modeling (X/y split, train/test split, encoding categoricals and scaling numericals)
5. Defining and running the model (Logistic Regression) and choosing which metric is most important (precision, recall, or f1)
6. Treating data imbalance (upsampling, downsampling, SMOTE) to improve model scores 
7. Re-running model with each data balance technique and comparing their confusion matrix and metrics
8. Drawing conclusions about data from the model
9. Hypothesis testing : Is the (average) average account balance of all Hawkins Bank customers the same as the (average) average account balance of customers who didn't take the credit card offer?
10. Data visualizations in Tableau comparing demographics of customers who did and didn't take the offer
11. Preparation of presentation to explain findings and actions to be taken by the bank to increase the percentage of customers who will take a credit card offer sent in the mail. 
12. 7-minute live presentation to 12 colleagues to present project and data-driven insights followed by 10-minute discussion
