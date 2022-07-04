# Project-2
Produce Monthly Report from Sales Data through Batch Data Processing using Python
![project 2 1](https://user-images.githubusercontent.com/96209699/176355602-ade22839-f2d3-4778-9fa8-cdbe964baf8b.jpg)


im using a given order E-commerce data set from Digital Skola data set comes with 2 files .sql. the data folowing information=

1. customer data set
2. order_items data set
3. order_payments data set
4. order_reviews data set
5. product data set
6. seller data set

the field of interest include the folowing:
1. order
2. customer
3. city
4. date

Goals:
Make a daily report

Transformation :
-used pandas function to load all table 
- transformed into data frames
- groub by city and date
- aggregation order with count value

Load :
Last step is program create a report in excel format
