# HR-Data-Analysis
Employee analysis

## Table of contents
- [Introduction/Project Overview](#introductionproject-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Recommendations](#recommendations)
***

### Introduction/Project Overview
---

This is a python and SQL project on an imaginary supermarket called Nasa Supermarket. the analysis project objectives is to analyze and glean insight into the sales performance of Nasa Supermarket for the year 2023. By analyzing various aspect of the sales data, we want to identify trends, make data-driven recommendations, and gain a deeper understanding of the supermarket’s (company) performance to answer critical questions and help the supermarket make data-driven decisions.

### Data Source

HR data: The primary dataset used for this analysis is the “HR_data.csv” file, containing detail information about each company employee for the period under review spanning from first to the forth quarter of the year 2023.

### Tools

- Python - data analysis
-	SQL Server Data Analysis
-	Excel

### Data Cleaning/Preparation

In the initial data preparation phase, I performed the following tasks:

1.	Data loading and Inspection
2.	Handling missing values
3.	Data cleaning and formatting

### Exploratory Data Analysis

EDA provides the means to exploring the sales data to answer critical questions such as:

-	What is the overall sales trend?
-	Which products are top sellers? 
-	What are the peak sales period?

### Data Analysis

Some interested code / features worked with

```python
sales_df = pd.read_csv("C:/Users/Nasa/Databank Analysis/Dataframe/sale.csv")
```

```python
sales_df.columns = [i.lower() for i in sales_df.columns]
```

```sql
sals_df = select * from sales
```

### Results / Finding

The following are the the summary of the analysis:

1.	The supermarket sales has been steadily increasing over the past year, with a noticeable peak during the holiday seasons
2.	Product category cloths, sockets, and Phones are the best performing category in terms of sales and revenue generation
3.	Customer segment with high live time value (LTV) should be targeted for marketing efforts

### Recommendations

- Invest in marketing and promotions during during peak sales seasons to maximize revenue
-	Focus on expanding and promoting products categories cloths, sockets, and phones
-	Implement a customer segmentation strategy to target high LTV customers effectively

### Limitations

I have to remove all missing values and zeros from Tuesday to Friday columns because they would have impacted the accuracy of my result or conclusion from the analysis. There are still a few outliers even after the verifications but even then, we can still see that there is a positive correlation between daily sales and products.

### References

-	SQL GUIDE for beginners by werty
-	Stack overflow
-	Konga website

