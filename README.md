# Calculate-Stock-Beta
<h3> What is Beta and How to Calculate It? </h3>  

Beta is a measure of a stock's volatility relative to the overall market. It indicates how much a stock's price is expected to move in response to changes in the market index. The market (e.g., S&P 500) has a Beta of 1, and individual stocks have Beta values that indicate their risk level compared to the market:

Beta = 1 → The stock moves in line with the market.
Beta > 1 → The stock is more volatile than the market. If the market rises by 1%, the stock might rise by more than 1% (and fall more in downturns).
Beta < 1 → The stock is less volatile than the market, meaning it fluctuates less than the overall market.
Beta < 0 → The stock moves inversely to the market (rare but possible).

<h3> How to Calculate Beta? </h3>
Beta is calculated using the formula:

<h3>  Python Implementation </h3>
The Beta of a stock (e.g., Tesla) relative to the S&P 500 can be calculated using Python, as shown in the script provided in this repository. 
<br>
<br>
The code:
<br>
<br>

1. Fetches historical adjusted closing prices for Tesla (TSLA) and the S&P 500 (^GSPC) using yfinance.<br>
2. Computes daily returns.<br>
3. Calculates the covariance between Tesla and the S&P 500.<br>
4. Computes the variance of the S&P 500.<br>
5. Divides the covariance by the variance to obtain the Beta value.<br>
6. Plots a scatter plot with a regression line to visualize the Beta.<br>
