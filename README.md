# Capstone Project
###### Investment or Bond Calculator
>>For this task, you have been approached small financial company has asked to create a program
>>that allows the user to access two different financial calculators:
>>an investment calculator and a home loan repayment calculator

---
__Contents__
1. Link to file
2. Instructions
---

**The [Project's original link]*(https://github.com/DJOLA0/Djolportfolio/blob/a739d9abd9007b996f1987b05f6ba726e2318769/DRE%20PYTHON%20VSCODE/finance_calculators.py)

## Instructions for the code
The user should be allowed to choose which calculation they want to do.
>>If the user selects 'investment', the user should be asked to input:
>>1. The amount of money that they are depositing.
>>2. The interest rate (as a percentage). Only the number should be entered, not the (%) sign.
>>3. The number of years they plan on investing.

>>Then ask the user to input if they want the "simple" or "compound" method.
>>store this in a variable called interest.

If the user selects 'bond', do the following:
>>Ask the user to input:
>>1. The present value of the house. e.g. 100000
>>2. The interest rate e.g. 7
>>3. The number of months they plan to take to repay the bond e.g. 120.

Calculate how much money the user will have to repay each month and output the answer

## Formulas
##### All the different formulas in python to help you calculate Investment.
*'r'* is the interest entered above divided by 100, e.g. if 8% is entered, then *'r'* is 0.08.
*'P'* is the amount that the user deposits.
*'t'* is the number of years that the money is being invested.
*'A'* is the total amount once the interest has been applied.

simple interest:
>>A = P*(1 + r*t)

compound interest
>>*A* = *P* * math.pow(1+*r*),t)

##### All the different formulas in python to help you calculate Bond Repayment.
*'P'* is the present value of the house
'i' is the monthly interest rate, calculated by dividing the annual interest rate by 12
'n' is the number of months  over which the bond will be repaid.

Bond repayment formula:
repayment = (i * *P*)/(1 - (1 + i)**(-n))

