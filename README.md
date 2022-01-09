# Plot of normalized time series for stocks
<i><b>Investia</b>, student-lead investment fund, 2021, Antoine Ruzette</i>

When investigating a sector to invest in, it is particularly useful to have a global view of the performance of the stocks of the companies within that industry over the past years. The present notebook enables the generation of such comparison plots. 

Content: 

* ETL: 
   - Data are retrieved using the YahooFinance API (using `pandas_datareader` package) 
   - Scaling based on the initial value of the stock
   - User specifies the tickers, start and end date
* Generates a plot combining the time series of the user-specified stocks over the user-specified time scope

NB: Such plot illusrates nicely the impact of March 2020... :) 
