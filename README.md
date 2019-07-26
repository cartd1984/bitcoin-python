# python/sql project - Price changes in bitcoin vs. volume traded

My project attempt to answer the question whether there is a correlation between a price fluctuation and the volume of transactions in a given day. More specifically, if the difference between the high price and the low price increases, does the volume of transactions increase?

To answer this question, I created a SQL database and imported a table of data that contains information on the prices. The table contained the Date, High (highest price on a given date), Low (lowest price on a given date), Open (opening price on a given day), Volume, and Market Cap. 

Once the data was imported, I conducted a SQL Query that subtracted the Low price from the High price and renamed the column as "Difference". I also included the Volume in the search. I sorted the data in Ascending and Descending order to give a depiction of what the data looks like in SQL. I eliminated any data that did not contain a value.

After returning the data, I graphed it as a scatterplot to measure the relationship. I have had trouble getting the graph to accurate order the volume of transactions. 

The packages I used to answer this question are as follows: sqlite3, pandas, numpy, and matplotlib.
