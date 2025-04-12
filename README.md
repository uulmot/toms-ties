# toms-ties

# Was it Pivoting away from Face Masks or Marketing Strategies that Could’ve Improved Sales for Tom’s Ties (Hint: It’s Both)?

Etsy Sales & Marketing Performance Analysis

## Introduction/Project Overview

Tom’s Ties (Voovanah) had its highs around end of the 2020 and spring of 2021 in terms of sales revenue. Most store sales were through face masks and may have been driven from an increased number of store reviews and an increase in number of COVID cases around that time (Mathieu et al., 2020). But at times of sales decline around May 2021, could there have been a pivot in the kinds of product offerings my store could have provided or was a demand for face masks still inevitable, but it was more of a seasonal item?

To better understand how my business could have continued a positive trajectory, I want to explore more into the question above alongside the following other research questions:

•	What factors influenced sales fluctuations over time?
•	How effective were different traffic sources in converting visitors into buyers?
•	Could different marketing strategies have improved sales performance?


## Data Overview

Using individual transactions dataset and shopper behavior dataset that I have compiled from the Etsy seller’s dashboard, I will analyze sales trends, customer purchasing behavior, and marketing metrics. Analyzing these results can better understand how my store could have done better in what products to offer and what marketing strategies could have been deployed. 

### Individual Transactions Dataset: this dataset provides a list of information to describe all the transaction activities that occurred when I ran the Etsy store from July 2020-June 2021. It has 2,464 records with key fields being d_date and title. There are some of blank cells in the amount field and can be ignored.
### Etsy Shopper Data: this dataset provides information on the amount of customers who interacted/visited to the my Etsy store. There’s also metrics on the different kinds of media platforms that customers have came from and visited to my Etsy store. Key fields include visits, orders, conversion rate, revenue, repeat buyers, and traffic sources. 


## Data Methodology

### 1.	Individual Transactions Dataset
Data Cleaning: Converted the date column into proper SQL date format. Some of the blank cells in the net revenue, amount, and fees columns left to have no value and still be counted in the dataset.
Data Transformation: Using the data_type column, title column, and amount column, I will filter the unique products (face masks, neckties, and bow ties) to better understand sales numbers and the amount of units sold of the products.

### 2.	Etsy Consumer Behavior Data
Data Cleaning: Converted date column into proper SQL date format. 
Data Transformation: Using all the traffic sources columns alongside the visits, orders, conversion_rate, and revenue columns, I will be able to gauge during each of the months when the business was still in operations of the performance in regards to the marketing metrics and the customer conversion and sales amount made per month.


## Deliverables

### 1.	Documentation on project
### 2.	Data Dictionary on dataset
### 3.	SQL Queries File
### 4.	Tableau Visualizations

### Best-Selling Products: 
a bar graph showing which product category performed the best in terms of unit sales and categorized by month to show popularity in certain months.

### Channel with Most Traffic Brought In: 
a two-way table to show the different categories in traffic channels that show which ones by month is most popular and in total which is most popular. A line graph can accompany with the two-table to show the average conversion rate by month along with the number of repeat buyers that are contributing to the amount of sales.


## Results & Insights

### 1. 
In terms the total number of visits across all media traffic platforms, months before the Christmas season (October 2020 and November 2020) and March of 2021 holds the most traffic–likely for these months to have more traffic is due in part of the advent holiday season and the longer the store was in business, the more positive reviews and sales that are create more visits/purchases.

### 2. 
Much of the online traffic and purchase conversions are derived from Etsy and related pages that are owned by Etsy. This may entail continuing to drill down keywords and put more footprint in getting my products on the first-second search result pages and through Etsy promoted listings to get more eyes on the Etsy platform.

### 3. 
The most sold number of face masks correlate to the number in the media traffic volume as mentioned in the first bulletin.

### 4.
Half of the months had at least 4-5 percent conversion rates on products sold, which correlated in the number of face masks sold and the number of media traffic that occurred.


## Recommendations

** From the SQL query results and knowledge gained after that year of store operating, some improvements and changes to increase sales and marketing performance of my Etsy shop would include the following:

### 1. Pivoting Away from Masks
As the spring/summer seasons of 2021 progressed, the number of face masks that were sold only showed when it was trending during times of the bigger sales periods for most online retail transactions along during the periods when the COVID pandemic cases were on the rise. Though more data in the future months could have given a better picture if my face mask designs could still have some demand, the need to pivot to other products in the accessories category could have been tested in order to give a better conclusion to whether there could have been strong numbers in the business.

### 2. The Etsy Platforms
Since most of the sales transactions were as a result of the number of traffic directly coming from the Etsy app and desktop, focusing on understanding the keywords that were trending at the time in the search bar and Etsy’s keyword metrics in the seller’s dashboard. Potentially, investing in between $1-$3 could have increased more exposure to get my product listings in the top and first search results to some key landing pages that results in more page visits to my listings.

### 3. Sales Figures for Tom's Ties
Since the median sales revenue is $534.50, figuring introducing more products that had higher price points could have helped in the sales figures since almost all of the face masks each had an average price of about $11. Figuring out how to get more sales in neckties and having other accessories introduced with an average product price of more than $11 could increase the sales number.

Through this analysis, I hope to highlight factors contributing to the decline in Vietnamese language proficiency among U.S.-born Vietnamese Americans. There needs to be continued efforts to support newer generations of Vietnamese Americans and other ethnic groups through dedicated language schools and programs, especially in communities with a growing Vietnamese population. 

Understanding these dynamics is crucial for developing strategies to preserve linguistic heritage and promote bilingualism and multilingualism within the Vietnamese community.

> **Correlation does NOT equal causation.**

---

## References

Mathieu, E., Ritchie, H., Rodés-Guirao, L., Appel, C., Gavrilov, D., Giattino, C., Hasell, J., Macdonald, B., Dattani, S., Beltekian, D., Ortiz-Ospina, E., & Roser, M. (2020, May 2). Coronavirus (COVID-19) cases. Our World in Data. https://ourworldindata.org/covid-cases 
