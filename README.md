# Online-retail-customer-segmentation
Customer segmentation is the practice of grouping the consumers of a firm into categories that represent the similarities among the customers in each category. In order to optimize each customer's value to the company, it is important to segment customers in order to determine how to interact with them. Customer segmentation may enable marketers to reach out to each customer in the most efficient manner. A customer segmentation analysis enables marketers to accurately identify distinct groups of customers based on demographic, behavioral, and other factors by utilizing the vast amount of customer (and potential customer) data accessible.
# Objective
The objective of this project is to segment the customers based on the features in to groups.
# Data Summary
InvoiceNo: Invoice number. Nominal, a six-digit integral number assigned to each transaction specifically. This code denotes a cancellation if it begins with the letter "c.".

StockCode: Product (item) code. A 5-digit integral number known as the nominal is assigned to each unique product.

Description: Name of the Product (Item). Nominal.

Quantity: The number of each item (product) in each transaction. Numeric.

InvoiceDate: Invoice Time and date. The day and time that each transaction was created, represented by a number.

UnitPrice: Unit pricing. Numeric, Sterling unit price for the product.

CustomerID: Customer number. Nominal, a five-digit integral number assigned to every customer uniquely.

Country: Country name. Nominal, the name of the country in which each customer resides.
# Approach 
* step 1 - Data loading
* step 2 - Data preprocessing and data wrangling
* step 3 - Exploratory data analysis
    * Univariate analysis
    * Bivariate analysis
    * correlation matrix
* step 4 - feature engineering
    *  In this step, Based on the data we created features like Recency, Frequency and Monetory.
* step 5 - Training models on different combinations of RFM features.
# Conclusion
Initiating the task, we found that our raw data contains about 25% missing values and we also found some duplicate values. We performed data cleaning to get rid of these values and also cancelled orders.

We derived important business insights based on products, time and location.

We also performed feature engineering. This included deriving new date and time features and getting a new feature giving the total amount of transaction using price and quantity of order.

We then performed RFM analysis of the transaction data. This helped us gain importance metrics to build models for customer segmentation.

Model building included Segmentation Using RFM Scores(Heuristic Model) which gave us 4 major segments.

*As K-means has the high score , it can be as used for the segmentation.

*The model can help to segment the customers on the basis on which their activities.

*The model helps to segment customer as it helps to target them with their interests with similar customers.
  
