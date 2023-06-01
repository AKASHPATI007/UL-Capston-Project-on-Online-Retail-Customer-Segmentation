# UL-Capston-Project-on-Online-Retail-Customer-Segmentation

# Problem Description

In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

# Data Description

# Attribute Information:

InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.

StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

Description: Product (item) name. Nominal.

Quantity: The quantities of each product (item) per transaction. Numeric.

InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.

UnitPrice: Unit price. Numeric, Product price per unit in sterling.

CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.

Country: Country name. Nominal, the name of the country where each customer resides.

# Summary And Conclusion of project

Firstly we did clustering based on RFM analysis. We had 4 clusters/Segmentation of customers based on RFM score.

![image](https://github.com/AKASHPATI007/UL-Capston-Project-on-Online-Retail-Customer-Segmentation/assets/113876908/85b0be36-6973-47fd-82dd-9f6c4a5fb9a8)

Platinum customers=1263 ( less recency but high frequency and heavy spendings)

Gold customers=1324 (good recency,frequncy and moentary)

Silver customers=981(high recency, low frequency and low spendings)

Bronz customers=770 (very high recency but very less frequency and spendings)

Later we implemented the machine learning algorithms to cluster the customers.

![image](https://github.com/AKASHPATI007/UL-Capston-Project-on-Online-Retail-Customer-Segmentation/assets/113876908/76b43ea4-af9f-49ae-9344-92e1eb23ead6)

![image](https://github.com/AKASHPATI007/UL-Capston-Project-on-Online-Retail-Customer-Segmentation/assets/113876908/cfd732c3-8208-47b7-8a8d-124fa34fb080)

Above clustering is done with recency,frequency and monetary data(Kmeans Clustering) as all 3 together will provide more information.

Cluster 0 has high recency rate but very low frequency and monetary. Cluster 0 conatins 2414 customers.

Cluster 1 has low recency rate but they are frequent buyers and spends very high money than other customers as mean monetary value is very high.Thus generates more revnue to the retail business

With this, we are done.Also, we can use more robust analysis for the clustering, using not only RFM but other metrics such as demographics or product features.

