# Customer-Segmentation
## Customer Segementaion using RFM modeling and K-means Clustering

Customer segmentation is a method of dividing customers into groups or clusters on the basis of common characteristics.

It is useful to get this information so that the store can get help in personalize marketing and provide customers with relevant deals.

With the help of this project, companies can run user-specific campaigns and provide user-specific offers rather than broadcasting same offer to all the users.

In this case 
RFM (Recency, Frequency, Monetary) analysis is a behavior-based approach grouping customers into segments. It groups the customers on the basis of their previous purchase transactions. How recently, how often, and how much did a customer buy. 
* Recency (R): Who have purchased recently? Number of days since last purchase (least recency)
* Frequency (F): Who has purchased frequently? It means the total number of purchases. ( high frequency)
* Monetary Value(M): Who have high purchase amount? It means the total money customer spent (high monetary value)

RFM modeling groups each customer on basis of their RFM score.

Also K-means algorithm starts with a first group of randomly selected centroids, which are used as the beginning points for every cluster, and then performs iterative (repetitive) calculations to optimize the positions of the centroids.

I used K-means clustering to group each customer according to their RFM score and predicted the Membership of each customer.


## DATASET 
Datasert for this Segementation is taken from UCI Machine Learning repository,More information can be found from [here](http://archive.ics.uci.edu/ml/datasets/online+retail)

Features 
1. InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
2. StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
3. Description: Product (item) name. Nominal.
4. Quantity: The quantities of each product (item) per transaction. Numeric.
5. InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
6. UnitPrice: Unit price. Numeric, Product price per unit in sterling.
7. CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
8. Country: Country name. Nominal, the name of the country where each customer resides.

