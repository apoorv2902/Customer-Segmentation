# Customer Segmentation
In this project, I performed unsupervised clustering of data on the customer's records from a supermarket database. Customer segmentation is the practice of separating customers into groups that reflect similarities among customers in each cluster. I divided customers into segments to optimize the significance of each customer to the business. To modify products according to distinct needs and behaviours of the customers. It also helps the business to cater to the concerns of different types of customers.

![alt text](https://blog-assets.freshworks.com/freshdesk/wp-content/uploads/2020/06/18152022/Blog_Banner_v1-01-1024x410.jpg)
## About the data

### People
* ID: Customer's unique identifier
* Year_Birth: Customer's birth year
* Education: Customer's education level
* Marital_Status: Customer's marital status
* Income: Customer's yearly household income
* Kidhome: Number of children in customer's household
* Teenhome: Number of teenagers in customer's household
* Dt_Customer: Date of customer's enrollment with the company
* Recency: Number of days since customer's last purchase
* Complain: 1 if customer complained in the last 2 years, 0 otherwise

### Products
* MntWines: Amount spent on wine in last 2 years
* MntFruits: Amount spent on fruits in last 2 years
* MntMeatProducts: Amount spent on meat in last 2 years
* MntFishProducts: Amount spent on fish in last 2 years
* MntSweetProducts: Amount spent on sweets in last 2 years
* MntGoldProds: Amount spent on gold in last 2 years

### Promotion
* NumDealsPurchases: Number of purchases made with a discount
* AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
* AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
* AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
* AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
* AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
* Response: 1 if customer accepted the offer in the last campaign, 0 otherwise

### Place
* NumWebPurchases: Number of purchases made through the company???s web site
* NumCatalogPurchases: Number of purchases made using a catalogue
* NumStorePurchases: Number of purchases made directly in stores
* NumWebVisitsMonth: Number of visits to company???s web site in the last month

## Clustering
![alt text](graph1.png) 

## Conclusion
### 1. Cluster 0:-
* They have done post-graduation.
* Most of them didn't accepted the campaign offer.
* Thier mean income is low and also spent low on purchasing.
* Mean age is 50.
### 2. Cluster 1:-
* They have done post-graduation.
* Most of them accepted the campaign offer.
* Thier mean income is highest and also spent the most on purchasing.
* Mean age is 55.
### 3. Cluster 2:-
* They have done under-graduation.
* Most of them didn't accepted the campaign offer.
* Thier mean income is lowest and also spent least on purchasing.
* Mean age is 43.
 
![alt text](graph2.png)
