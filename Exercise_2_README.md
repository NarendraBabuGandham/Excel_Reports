## Sales Report Analysis

This project involves generating sales reports using Excel formulas. The dataset consists of sales amounts for three salespersons (Rohit, Priya, and Amit) over the months of November and December. The following formulas have been used to generate insights about minimum, maximum, total, and average sales, along with transaction counts.

### Description

The goal is to create monthly and individual sales reports for each salesperson using Excel's built-in functions like MINIFS, MAXIFS, SUMIFS, AVERAGEIFS, and COUNTIFS. The results of these reports include the following:

**1.Minimum Sales Amount: Calculated for each salesperson for both November and December.**

**2.Maximum Sales Amount: Calculated for each salesperson for both November and December.**

**3.Total Sales Amount: Sum of all sales for each salesperson per month.**

**4.Average Sales Amount: Average of sales transactions for each salesperson per month.**

**5.Count of Sales Transactions: Number of sales transactions made by each salesperson for both months.**

**6.For each of the sales person, check if the above formulas are correctly applied or not.**

### Data Set:



![image](https://github.com/user-attachments/assets/d70185c1-8660-41bc-a861-b36c4a031edf)

### Reports

**1.Minimum Sales Amount: Calculated for each salesperson for both November and December.**

`=MINIFS(Sales_Amount_Range, Sales_Person_Range, "Rohit", Month_Range, "Nov")`


![image](https://github.com/user-attachments/assets/6a937350-ec75-4ef7-867a-ada59182efea)


**2.Maximum Sales Amount: Calculated for each salesperson for both November and December.**

`=MAXIFS(Sales_Amount_Range, Sales_Person_Range, "Priya", Month_Range, "Dec")`


![image](https://github.com/user-attachments/assets/278e07b4-100f-4c2a-a222-957c7f2a1cf6)


**3.Total Sales Amount: Sum of all sales for each salesperson per month.**

`=SUMIFS(Sales_Amount_Range, Sales_Person_Range, "Amit", Month_Range, "Nov")`


![image](https://github.com/user-attachments/assets/43e9e2dc-a458-4fae-9057-57ba2fa1f2dc)


**4.Average Sales Amount: Average of sales transactions for each salesperson per month.**

`=AVERAGEIFS(Sales_Amount_Range, Sales_Person_Range, "Rohit", Month_Range, "Dec")`


![image](https://github.com/user-attachments/assets/569e6547-fc3a-4d6f-b999-452c7ff3e91b)


**5.Count of Sales Transactions: Number of sales transactions made by each salesperson for both months.**

=COUNTIFS(Sales_Person_Range, "Priya", Month_Range, "Nov")


![image](https://github.com/user-attachments/assets/7e3d7d99-a052-43ee-84dd-cf1939b6956b)


**6.For each of the sales person, check if the above formulas are correctly applied or not.**

`=Totalsales-(average*count)`


![image](https://github.com/user-attachments/assets/7818c132-7771-4175-b5f3-d52aa65b9344)


## Screenshots

The Excel file includes calculations for each salesperson, organized by:

Minimum Sales Amount

Maximum Sales Amount

Total Sales Amount

Average Sales Amount

Count of Sales Transactions


### Usage Instructions

1.Open the Excel file.

2.The formulas have been applied in their respective columns.

3.Adjust the data ranges and criteria as per the requirements of your dataset.

## Conclusion

This Excel report provides a clear view of the sales performance of each salesperson.









