# stock-market-analysis

https://www.alphavantage.co/ is an API used to fetch stock market data.

Your task here is to fetch historical daily data from the API from Jan 1, 2020 to May 31, 2024 for the Top 10 companies in India (by Market Cap) and get the following columns:

```
Date
Company
Open
Close
High
Low
Volume
```

From this, the final tasks would be:

1. One script for historical dump
2. One script for a daily dump of D-1 (yesterday) which would run on a cron job (the cron job is out of the scope of this task)
3. SQL DB/DW credentials such that querying can be done
4. Indexing of the DB if the following queries have to run on a regular interval:
    1. Company Wise Daily Variation of Prices
    2. Company Wise Daily Volume Change
    3. Median Daily Variation

You can get the Free API Key by signing up on the platform

Bonus would be if you are able to write executable queries with minimum load time for the above 5 queries.
