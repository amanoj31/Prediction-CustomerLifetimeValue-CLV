# Prediction-CustomerLifetimeValue-CLV

Customer Lifetime Value (CLV) is an important metric for businesses. CLV represents the total 
worth/profit from a particular customer to a business over a period of time. It provides a
measure of relative importance of existing customers to a business in terms of revenue, churn,
interaction, and loyalty. This metric informs business leaders on decisions regarding strategic
focus on existing customer retention or new customer acquisition; marketing strategies targeted
at specific segments of the populace; and recommended advertisement budget projections. In
short, CLV is a powerful measure of customer value to a business based on historic transaction
data; a metric which is hard to encapsulate in existing summary statistics such as total
transactions, average purchase amount per transaction, or percentage of total sales.
This project aims to predict the CLV of customers based on 1-year transaction data. First, we
will extract customer-level information on purchases and returns from the data set to generate
features per customer including Average Order Value (AOV), Days to Purchase (D2P), Gross
Margin, and Recency, Frequency, Monetary (RFM) Metrics. Based on these features, we will
build a regression model to estimate and predict CLV. After validating model assumptions and
conducting goodness of fit analysis, we will compare our model to existing CLV models from
other researchers who did not include returns as a part of their analysis. We will use both
models to predict CLV of the same data set and analyze how differing methodologies and model
assumptions influenced difference in CLV predictions.
