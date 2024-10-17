# Software-Engineering Minor Project
# ASSIGNMENT 1
### Objective:
The goal of this assignment is to demonstrate that the C programming language only supports Call by Value. This means that when a function is called in C, the values of the arguments are passed to the function, 
not the original variables themselves.

### Problem Statement:
Write a C program to show that the C programming language supports Call by Value only.

### Business scenario:
AssetZen, a financial firm, provides an investment risk assessment tool for clients to evaluate their portfolio performance. It needs to develop a reliable investment risk assessment tool that
allows financial analysts to calculate the squared values of investment returns while ensuring that the original client data remains unchanged to maintain data integrity and support informed decision-making..

### Business Use Case:
In portfolio management, evaluating the volatility of investment returns is a critical aspect of assessing risk. Squaring the returns amplifies the impact of both large gains and large losses,
making it easier to detect volatility. AssetZen’s tool will empower financial analysts to

1)Calculate squared returns for different assets in the client’s portfolio.

2)Preserve original data, ensuring that no modification occurs to the client’s historical data, which could lead to faulty assessments.

3)Provide risk insights to clients based on these calculations to guide investment strategies.

Example of Squared Returns:
To illustrate the calculation, consider an investment with a return of 5%. The squared value would be:
(0.05)*(0.05)=0.0025
For a negative return of -5%, the squared value would be:
(-0.05)*(-0.05)=0.0025
By squaring both positive and negative returns, the tool helps analysts give more weight to extreme values and make accurate risk assessments.
