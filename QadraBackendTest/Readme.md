# Quotes importer
We need to import an instrument (stock, etf) quotes, to do this we typically connect to different data sources depending on the instrument. The datasources return data in different formats and sometimes this data needs to be processed before we can use it. 

We need to create a flexible engine that:
- given an instrument, it fetches the data from the appropriate data source
- depending on the data source it applies some processing logic to clean the data. For example, when importing from MS we need to remove all the values equal to 0 or null.

## Other info
- We are interested in seeing how you apply software best practices and design patterns. We value quality over quantity.
- Feel free to change any part of the code, add classes and tests
- We have created two dummy data source clients that you can use

We have already created the data source clients for two data sources. Use them.