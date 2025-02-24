# INTRO

Hola, today we are tackling this bank attrition dataset and for me, anything bank or finance just makes me happy because as a banking and finance student and as someone who has had the opportunity of working at the bank, this takes me back and I just love this dataset. Now this dataset is all about this particular bank's attrition rate. when we say attrition, we mean the rate at which the customers are leaving the bank alright. So yhh we want to analyze the reasons behind this today and possibly what this bank can do okay.

Again the source of this dataset comes from kaggle. It's actually my go to place for datasets so yes. There is so much to this dataset, I cant wait.

So first and foremost, I downloaded the dataset as usual, created a database in Microsoft SQL server and name it Bank_Attrition and the lined up my procedure for this project; 

### Data Cleaning & Transformation
### Data analyzing
### Recommendations

# Data Cleaning
The first step of my cleaning process was to remove duplicates using ROW_NUMBER(), PARTITION BY. This is among my favourite thing when I'm using sql to clean a dataset so yhh: ![duplicates bk](https://github.com/user-attachments/assets/924c04dd-4ac7-46c6-909d-b15f1f1f874f)
So this was how we checked and removed our duplicate values. After this, I went ahead to standardize my dataset by first checking through the various columns like this: ![attrition standa1](https://github.com/user-attachments/assets/fe5a3fe1-8555-4483-af0d-3ca9fbb89aa5) ![Attrition standa2](https://github.com/user-attachments/assets/7ad4e2fc-6ee2-48f4-8dfb-ac5f6bb26d33)

so this is how I cleaned and transformed my dataset

# Data Analysis

I then moved on to creating my analysis, answering some really insightful and important questions

#### HOW MANY CUSTOMERS DOES THIS BANK HAVE?
#### FIND THE NUMBER OF CUSTOMERS PER REGION AND THE ESTIMATED SALARIES OR WHICH REGION IS CONTRIBUTING THE HIGHEST AMOUNT
#### FIND THE TOTAL, AVERAGE, HIGHEST AND LOWEST ESTIMATED SALARY DETAIL
#### FIND THE TOTAL, AVERAGE, HIGHEST AND LOWEST BALANCES DETAILS
#### HOW MANY CUSTOMERS PURCHASED HOW MANY PRODUCTS FROM THE BANK?
#### FIND THE TOTAL CUSTOMERS PER CARD TYPE AND GEOGRAPHY
#### WHAT IS THE TOTAL ATTRITION NUMBER?
#### WHICH AGE BRACKET HAS THE HIGHEST NUMBER OF ATTRITION?
### HOW MANY ATTRITION CUSTOMERS HAD CREDIT CARDS?
just to mention a few and this was my formulas or queries for this exciting project: ![analysis bk1](https://github.com/user-attachments/assets/abb4c550-6ee0-4f53-b217-d1f9772103d1) ![analysis bk2](https://github.com/user-attachments/assets/2e1094eb-d84f-459f-9b5f-f154ca33516e)
So yhh this was my queries and more business questions answered

# Conclusion

As already stated, this was an exciting project that challenged my domain knowledge in the field and challenge me to take my sql skills to a whole new level. 

if you ask me, it was a fun project.
