# RFM-Analysis

### Project Overview
The aim of this project was to analyse E-commerce application performance to help the management identify the main groups (segments) of the clients for further data-driven decisions.

### Approach
Since it was required to get a snapshot of the customer-base I segmented the customers using RFM Analysis.
All the customers were divided into groups on the basis of three different segments: Recency, Frequency and Monetary Value. In each segment the customers were further divided into 4 groups (using quantiles). 
As a result of the analysis, we will have customers in groups from '111' to '444', where '111' would be ‘the best class’ with higher frequency and monetary value and less recency.

### Data Source
Data set including information on 
- customer code
- invoice no
- invoice date
- invoice amount

### Tools
- Python
- Libraries: pandas, numpy, matplotlib, seaborn

### RFM Analysis
- table with Recency, Frequency and Monetary Value for each customer
- creation of 4 groups for each parameter (Recency, Frequency and Monetary Value) using quantiles 
- function distributing all clients into classes (from 1 to 4) in all 3 parameters (Recency, Frequency and Monetary Value)
- visualization of Segmentation Table using heatmap

### Exploring Results of Segmentation
Some of the questions that can be answered with the help of resulting table:
-	What are the upper and lower borders of invoice amount for users of different classes
-	What is the maximum number of days from the last purchase required the customer to be placed one class higher 
-	How many users are in each class
-	In which RFM class there are more customers
-	Which class has the minimum number of customers

### Conclusion
From the analysis we have seen how the customers are segmented/groupped. The most populated Class is '444', which is not good for the product/app as this Class represents the customers on the point of churn. With presentation of the results of the analysis, the managemnt can take decisions what actions and/or marketing stategies are required to convert customers into 'higher' class or to retain customers. E.g. the efforts can be concentrated on the classes with high number of customers so that the such customers will move to a 'better' category (i.e. group with higher frequency or monetary value and less recency). Other options include conducting A/B tests for certain groups, trying various mechanisms to retain the clients. To sum up, depending of the RFM Class the company can design strategies to improve the class, to retain the customers in the given class or to do nothing with certain classes.

