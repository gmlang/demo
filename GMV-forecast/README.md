PayPay is a Japanese payment processing company. The business team is interested 
in forecasting GMV (Gross Merchandise Value), which is defined as the sum of 
transaction amounts over a period of time. GMV can be defined per store (the seller), 
per user (the purchaser), or for PayPay as a whole (across all users and stores). 
The business team has provided you with the following datasets (in CSV format): 

  - *transactions.csv*: contains all transactions for 2020 and 2021. Its 
    columns are user ID (user_id), store ID (store_id), datetime of each
    transaction (event_occurance), and transaction amount in yen (amount).
  - *stores.csv*: contains store characteristics such as prefecture (nam), 
    local administrative area (laa), category, and location in latitude (lat) 
    and longitude (lon).
  - *users.csv*: contains user characteristics such as gender and age.

The business team wants to 

1. understand patterns in the data,
2. forecast GMV for each user for the month of January 2022, and
3. forecast GMV for PayPay as a whole for each date in the month of January 2022.
