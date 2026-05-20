# Loan-Risk-Customer-Default-Analysis-For-CrediTrust-

## INTRODUCTION
This project analyzes customer loan risk data to identify factors associated with loan default. The analysis aims to help  CrediTrust improve loan approval decisions, reduce financial risk, and develop better lending strategies.

 
## OBJECTIVES
The objectives of this analysis are:
* To identify risky customer profiles 
* To evaluate factors influencing loan default 
* To determine whether loan conditions should be stricter 
* To assess if loan amounts should be reduced for certain customers 
* To build a simple predictive model for default risk


## DATA CLEANING AND PREPARATION
The dataset was cleaned and prepared before analysis. Initial exploration was performed using functions such as head(), info(), and shape() to understand the dataset structure. Missing values were identified and handled appropriately to improve data quality. Customer risk categories were created based on credit score and previous default history. Credit scores were also grouped into categories to simplify analysis. Finally, grouped summaries and aggregations were prepared to support visualization and default risk analysis.


## Credit Score Distribution
<img width="503" height="239" alt="Screenshot 2026-05-20 112155" src="https://github.com/user-attachments/assets/9477e360-75fe-4194-9149-d6fe876c3a84" />


## Default Rate by Credit Score Group 
<img width="365" height="276" alt="Screenshot 2026-05-20 112452" src="https://github.com/user-attachments/assets/7ffaa487-fc22-4b5b-b8b8-b6ea66bd110f" />


## 'Default Rate by Previous Default History
<img width="395" height="272" alt="Screenshot 2026-05-20 112513" src="https://github.com/user-attachments/assets/b2cd6ee4-e338-4ddd-b24b-6fcd3a84aa57" />

## Default Rate by Employment Status
<img width="365" height="289" alt="Screenshot 2026-05-20 112640" src="https://github.com/user-attachments/assets/cd90204a-4b36-412c-a7f7-6a5acddb0efa" />



 ## Insight

1. What type of customers should the company avoid?

The company should avoid or carefully review customers with:
* Previous default history 
*	Low credit scores 
*	Unstable employment status 
*	High-risk classifications
  
These customers demonstrated significantly higher default rates and therefore pose greater financial risk to the company.
 
2. What loan conditions should be stricter?
   
Loan conditions should be stricter for customers identified as high risk. The company should:
* Require higher credit score thresholds
* Conduct stricter background checks 
* Request additional financial documentation 
*	Apply shorter repayment periods 
*	Increase monitoring for customers with previous defaults
  
These measures can help reduce the probability of loan default.

3. Should the company reduce loan amounts for certain customers?
 
Yes. Loan amounts should be reduced for customers with:
*	Poor credit scores 
*	Previous default records 
*	High debt risk indicators 
*	Unstable employment status
  
Reducing loan exposure for high-risk customers can minimize potential financial losses while still allowing controlled access to credit.


## Conclusion

The analysis revealed that previous default history, low credit scores, and unstable employment are strong indicators of loan default risk. The company should strengthen approval policies and reduce exposure to high-risk customers.




 

