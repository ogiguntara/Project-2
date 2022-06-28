# Project-2
Extract Data From SQL File, Transform, and Create Excel File
![batch-processing](https://user-images.githubusercontent.com/96209699/173058169-d0670a31-b29b-4c4b-bcc8-94dc2612c437.png)


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
