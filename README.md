# Simple-RFMAnalysis
RFM stands for Recency, Frequency and Monetary Value by which we can divide our customers in separate groups.
In this example we have a table with customers purchases during one month with InvoiceNo, CustomerID, Date and Amount.

First, we are preparing our data grouping by customer and define the date of the last purchase(recency), amount of purchases(frequency) and the total sum of purchases(Monetary Value).

Then we define quantiles for each metric and write functions to apply group to each customer by each of the metrics.

Finally, our table is ready and we can further check who spent most, who buys our goods more often or who bought our products recently.
