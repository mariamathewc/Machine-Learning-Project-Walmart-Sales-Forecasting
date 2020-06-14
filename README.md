<h3> ABOUT </h3>
Walmart is an American multinational retail corporation that operates a chain of hypermarkets,
discount department stores, and grocery stores,with a revenue, over US$ 500 billion.
Our goal is to predict Walmarts Weekly Sales for a specific store and department combination.
Weekly sales are predicted on Fridays.

Dataset is taken from Kaggle competition Walmart Recruiting - Store Sales
Forecasting( https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting ).
Weekly sales are predicted based on inputs from 3 csv files.

Dataset1 : train.csv
This dataset has 421570 rows and 5 features
This file contains historical training data, which covers to 2010-02-05 to 2012-11-01.
Within this file you will find the following features:
● Store - the store number
● Dept - the department number
● Date - the week
● Weekly_Sales - sales for the given department in the given store
● IsHoliday - whether the week is a special holiday week

Dataset2: stores.csv
This dataset has 45 rows and 3 features
This file contains anonymized information about the 45 stores, indicating the type and size of store.
Within this file you will find the following features:
● Store - the store number
● Type - the store type
● Size - the store size

Dataset3 : features.csv
This dataset has 8190 rows and 12 features
This file contains additional data related to the store, department, and regional activity for the given
dates.
Within this file you will find the following features:
● Store - the store number
● Date - the week
● Temperature - average temperature in the region
● Fuel_Price - cost of fuel in the region
● MarkDown1-5 - anonymized data related to promotional markdowns that Walmart is running.
MarkDown data is only available after Nov 2011, and is not available for all stores all the
time. Any missing value is marked with a NA.
● CPI - the consumer price index
● Unemployment - the unemployment rate
● IsHoliday - whether the week is a special holiday week


Please see the below link for more details.
https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting
