# Sales-Summary
Created a SQLite database (sales_data.db) containing a table with product sales data.
2. Connected Python to the database
Used the sqlite3 library to connect to the SQLite database.
3. Wrote an SQL query
Used SQL to calculate the total quantity sold and total revenue for each product using GROUP BY.
4. Loaded the SQL result into a pandas DataFrame
Used pd.read_sql_query() to read the SQL query result into Python for further processing.
5. Printed the output table
Displayed the summary table showing product-wise total quantity and revenue.
6. Plotted a bar chart using matplotlib
Used df.plot() to create a bar chart showing revenue by product.
7. Visualized the output
Displayed the chart, which clearly shows which product made the most revenue.
