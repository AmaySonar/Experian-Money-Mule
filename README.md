# Experian - "Fast Cash, Hidden Crimes : are you being used as a Money Mule ?"


# Project Description 

This project was developed as a part of data science challenge with Experian, a global leader in data and analytics, serving over **1 billion individuals** and **25 million business** across more than ** 40 countries**. Whith around **22,000 employees**, Experian uses data to empower individuals and business supporting responsible lending, fraud prevention, identity verification and personalised marketing. 

In recent years, **money mule fraud** has become a rapidly growing threat in the financial sector. According to **Santander UK**, there were ****22,467 money mule cases** reported between October 2023 and September 2024 a **32% increase** from the previous year. Particularly alarming is the **26% rise** in cases involving **young adults aged 18 to 24**. Many are misled into believing that “lending a bank account” for a quick cash reward is harmless. In reality, these transactions often facilitate **serious criminal activity**, including **child trafficking** and **drug distribution**.

This project focuses on identifying suspicious accounts likely to be involved in money mule operations using a structured data analytics approach. Given anonymized datasets by a high-profile bank, our goal was to  
•	Audit and clean the data  
•	Engineer meaningful features  
•	Conduct exploratory data analysis    
•	Build predictive models to classify potential mule accounts   
•	Visualize key patterns and insights    

The work supports Experian’s mission to detect and prevent financial fraud, protect vulnerable individuals, and ensure a safer financial ecosystem.   



[More about Experian’s efforts to combat money mule fraud](https://www.experianplc.com/newsroom/press-releases/2023/experian-launches-new-service-to-prevent-money-mule-account-fraud)





Table of Contents: 








Installation Setup: 




Data ( Describe the DataSource, Columns, Format) 

**Data Dictionary **

Here is a clean and structured Data Dictionary you can add to your GitHub README.md file under a section titled 📘 Data Dictionary:

⸻

📘 Data Dictionary

The project uses three datasets, each containing anonymized account-related information. Below is a description of the key variables across all files:  

1. Mule Flag Dataset  

Column Name	      Description  
Identifier	      Unique ID for the account  
MuleAccount	      Binary indicator: 1 = Money Mule, 0 = Not a Mule       


⸻

2. Account Holder Data  

Column Name	                  Description   
Identifier	                  Unique ID for the account   
DateOfBirth	                  Date of birth of the account holder   
Gender	                      Gender of the account holder (Male / Female)  
Income	                      Annual income of the account holder  
CreditScore	                  Credit score of the account holder  
LoanAmount	                  Total loan amount held by the account holder  
EmploymentStatus	            Employment status (Employed, Student, Retired, etc.)  
MaritalStatus	                Marital status (Single, Married, Divorced, etc.)  
OccupancyStatus	              Home occupancy status (Owner / Renter)  
NumDependents	                Number of dependents under 18  
SocialMediaUsageHours	        Weekly hours spent on social media  
ShoppingFrequencyPerMonth	    Number of shopping days in a month  
HealthInsuranceStatus	        Binary flag indicating if the holder has health insurance (Yes / No)     

⸻   

3. Account Data   

Column Name	      | Description   
Identifier	      | Unique ID for the account   
AccountLength	    | Number of months the account has been active   
AverageBalance	  | Average balance maintained in the account   
NumTransactions	  | Total number of transactions since account opening   
NumDeposits	      | Total number of deposits    
NumWithdrawals	  | Total number of withdrawals  
NumTransfers	    | Number of transfers to other accounts   
NumLoans	        | Number of loans associated with this account   
NumCreditCards	  | Number of credit cards held   
NumSavingsAccounts|	Number of savings accounts linked to this account   


⸻


Project Structure 






Results and Screen Shots 




