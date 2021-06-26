# API-Homework
This code will be analyzing a personal potfolio containing BTC, ETH, AAG, and SPY.</br></br>
The first part of the code pulls price data using Alpaca for stock data and Alternative.me for crypto data.</br></br>
It then creates a dataframe displaying the personal portfolio and using if statements to determine with the portfolio is worth than an emergency fund.</br></br>
The second part of the code uses Monte Carlo to predict the outcomes of AAG and SPY (40%/60% composition) within the next 30, 10, and 5 years. </br></br>
It also uses 95% lower and upper confidence intervals to predict the price range these stocks could target based on various initial investments. </br></br>

## This code requires a .env containing API keys (Alpaca API)</br>
When creating your .env file, try to have the file type as "No File Extension" and make sure that the .env file has no title. Have the file in this format:</br></br>
ALPACA_API_KEY = 'Insert key here'</br></br>

ALPACA_SECRET_KEY = 'Insert secret key here'</br></br>

