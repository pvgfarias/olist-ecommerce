# Brazillian E-Commerce Company (Olist): Deliveries, Reviews and Repeat Customers

An analysis of Olist, a company that connects small and medium Brazillian stores to the large online marketplace. We try to understand the growth of the business and where deliveries fell short using Python, Pandas and Google Colab.

# Key Findings
1. The data shows a steady revenue growth between 2016 and 2017 with a peak in November 2017 when Black Friday happens. We noted a drop in 2018's last month since the orders were probably still being delivered.
2. About 6.8% of all the orders were late, with AL (21%) and MA (17%) being the top 2 states with the highest percentage of late orders. We also noticed most of the late orders were in the northeast region. However, a big market like RJ with 12,553 orders had a 12% late percentage which affects more users than AL and MA where there were fewer orders.
3. The late deliveries had a review score of around 2.3, which was 2 points below the 4.3 review score for orders on time. We proved that the result is both statistically relevant and practically relevant.
4. Out of all the unique users, only 3% came back to make a second order. Out of those 2801 second orders, 853 were actually made on the same day. It showed that the actual percentage of customers who came back was even lower, at around 2%. Showing that the business relies mostly on new customers, which can be worrisome for revenue if finding new customers becomes expensive.

# Google Colab
The project was created using a Google Colab notebook where we also found some key.

# Questions Answered
1. How did orders and revenue change month by month?
2. Where are deliveries late, and by how much?
3. Do late deliveries hurt review scores?
4. Do customers come back?

# Data
- Source: Brazilian E-Commerce Public Dataset by Olist [(Kaggle)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- Scope: We only considered orders that were delivered, while also ignoring the first and last months of the dataset since they have incomplete data. 
- Validation: 97% of orders (96,478) were delivered. The rest were shipped, canceled, unavailable or still processing, which is why 2,965 orders have no delivery date. Delivery analysis uses delivered orders only within the date range set in the scope.

# How To Run
1. Create a folder in your Google Drive called 'olist' containing the csv files downloaded from Kaggle.
2. Copy the olist_analysis.ipynb into a Google Colab notebook and run all.

# Next Steps
We would like to further investigate if the reason for the bad user retention is due to late deliveries, bad review scores or if this is just a common customer behavior of only making one purchase.
