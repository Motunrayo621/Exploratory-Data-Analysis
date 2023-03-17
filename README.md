### Exploratory-Data-Analysis
## K SUPERMARKET SALES REPORT
### INTRODUCTION
As a data analyst at K Supermarket, I've been asked to deliver a sales report to the Senior Managers that details the company's sales, costs, profits, quantity sold, and historical performance across the nation.
I gave a summary of the sales statistics, emphasizing the trends and patterns, the main areas that needed improvement, and also making suggestions for the future sales tactics.
##### Tool Used : Microsoft Excel, Microsoft PowerPoint and Power BI
### ABOUT THE DATASET
The dataset used in this project is an Excel file obtained from Microsoft @Financial Sample Dataset. It has 16 columns including Segment, Country, Product, Discount Band, Unit Sold, Manufacturing Price, Sale Price, Gross Sale, Discount, Sales, CGOS, Profit, date, Month Number, Month Name and Year.

![Raw data fin](https://user-images.githubusercontent.com/127993425/225927827-ec8162f9-5028-461c-9816-323f87eba995.PNG)
**Raw Data**
### CLEANING OF THE DATA OBTAINED
After scrutinizing all the columns, I:
* Removed blanks and duplicates in Excel
* Inserted 3 new columns to show the Continent, Store Name and Product Category using the IF FUNCTION

![Continent](https://user-images.githubusercontent.com/127993425/225929158-0468674a-e9f7-469e-a03e-d071c570361d.PNG)
* Imported to Power BI and transformed the data in the Power Query Editor
* Grouped the columns into Dimension Tables (Product and Continent) and Fact Table.

![transform](https://user-images.githubusercontent.com/127993425/225929369-b06ec46b-760d-4f3c-8dd5-22c6f1f49a02.PNG)
**Data Transformation**
* Established relationship between tables using the unique keys.

![modelling](https://user-images.githubusercontent.com/127993425/225929525-c8937671-baab-4c15-b18e-b542ce3331f0.PNG)

**Data Modelling**
### DATA VISUALIZATION & INSIGHTS
The insights obtained from the dataset are as follows:

The grocery store earned a profit of 3.88 million in 2013 and 13.02 million the following year. The business sold more than 264K products in 2013 and more than 861K in 2014. This is due to the growing number of customers and their rising spending power.

![2013 begin](https://user-images.githubusercontent.com/127993425/225933925-79a95ee2-abc7-4d9c-b631-8906032030ee.PNG)
    **_2013_**
    
![2014 beginning](https://user-images.githubusercontent.com/127993425/225934023-5e49c8d1-43fa-4381-a573-99d3a4e33766.PNG)
    **_2014_**
#### TOTAL COST BY PRODUCT
A quarter of the overall expenditure for 2013 was spent on the production of Velo, which cost 5.6 million dollars. The cost of manufacturing Paseo increased in 2014 and was roughly 23 million. This can be because of a rise in the number of products being produced and the rising cost of the raw materials used to make them.

![2013 TC by Poduct](https://user-images.githubusercontent.com/127993425/225940242-d59e68fd-c001-4982-94a3-7ae7e3497fa3.PNG)
**_2013_**

![2014 TC](https://user-images.githubusercontent.com/127993425/225940407-acb3d29a-5c7d-45b4-8f79-241a92f7fa29.PNG)
**_2014_**
#### PROFIT BY PRODUCT
In 2013 and 2014, the sale of the Paseo and VTT product collectively contributed about 51% of the profit and 45% of the profit, respectively. Nevertheless, the Paseo product outperformed the VTT product in terms of profit, generating 20% more in 2013 and 41% more in 2014.

![2013- profit by pr](https://user-images.githubusercontent.com/127993425/225940620-e5515fda-350e-47c0-9e63-7635dc9439b8.PNG)
**_2013_**

![2014 - profit by pr](https://user-images.githubusercontent.com/127993425/225940730-4c8ae321-8126-41c0-ae9c-5f65ac6516a3.PNG)
**_2014_**
#### UNIT SOLD BY PRODUCT CATEGORY
In both 2013 and 2014, customers gradually made more purchases from the general products category. Sales of 163.3k units, or 61.7% of the entire quantity, occurred in 2013; sales of 506.15k units, or 58.78% of the total quantity, occurred in 2014.

![2103- Qty](https://user-images.githubusercontent.com/127993425/225941007-0f333d6e-e6b3-43d1-ad03-e3ba81d726a8.PNG)
**_2013_**

![2014- qty](https://user-images.githubusercontent.com/127993425/225941131-374c3026-4f85-4630-b9d1-d38f49d1ffa4.PNG)
**_2014_**
#### PROFIT BY COUNTRY
Germany generated the most profit of 1.1 million and 2.6 million in 2013 and 2014, respectively, according to a map visual of the income by countries. There was an 62% increase, which may have been brought on by the large number of shoppers in the supermarket. More specifically, it can be due to higher productivity and lower production costs for the goods in Germany.

![2013 (original)- Profit by Country](https://user-images.githubusercontent.com/127993425/225941397-4fba82ba-883b-4fd9-b389-ca4d67d7f023.PNG)
**_2013_**

![2013-Profit by Country](https://user-images.githubusercontent.com/127993425/225941551-3314f054-c934-4c01-a8df-c083cae67433.PNG)
**_2014_**
#### SALES BY COUNTRY
Germany had the greatest sales in 2013 with 6.2 million, and they grew to 17 million in 2014. Nonetheless, the United States and Canada outperformed Germany in sales in 2014 with 20M, or 44% of all sales for that year. This may be due to the effective marketing techniques employed to draw in clients.

![Sales by Con 2013](https://user-images.githubusercontent.com/127993425/225942512-d14ed8ee-6123-4150-9c34-4fa872a93f51.PNG)
**_2013_**

![2014- sales by con](https://user-images.githubusercontent.com/127993425/225941993-9e62663f-dd19-4a02-8498-6a5661041320.PNG)
**_2014_**
#### SALES BY MONTH
The store recorded its greatest sales in October for both 2013 and 2014, with 9.3M and 12.4M, respectively. This can be due to the promotions offered that month and the rise in customers.

![2013 sales by mon](https://user-images.githubusercontent.com/127993425/225943208-d2ca8249-5b3a-40c0-b2be-deae9ef6258f.PNG)
**_2013_**

![2014-sales by mon](https://user-images.githubusercontent.com/127993425/225943305-c9377b36-f7e1-4446-a7fa-b90848785071.PNG)
**_2014_**

### REPORT VIEW

The report is a three-page document

* The Home Page
* 2013 Sales Report Page
* 2014 Sales Report Page

![K Sup1](https://user-images.githubusercontent.com/127993425/225944244-0a615c95-4fbd-41e1-84f7-ce97000930ef.PNG)

**_Home Page_**

![K Sup2](https://user-images.githubusercontent.com/127993425/225944344-5cdcb5f9-6520-4380-a9bf-0c0fd7fba90a.PNG)

**_2013 Report View_**

![K Sup 3](https://user-images.githubusercontent.com/127993425/225944498-22e02c34-0aa5-449b-a086-337264f9375a.PNG)

**_2014 Report View_**

### RECOMMENDATIONS
* Countries with low profit margins should make every effort to reduce their expenses and reassess their strategies because a company's goal is to have enough profit at the end of the year.
* In addition to increasing sales, K Supermarket have to think about providing discounts at different seasons of the year.
