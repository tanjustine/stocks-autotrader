# Stocks Autotrader Readme

This is an autotrader created using Microsoft Excel Visual Basic for Applications (VBA) to backtest IBM's stock from 1975-2017.

Five different strategies were tested using the autotrader to discover which strategy will produce the highest profit at the least amount of risk. The dataset was derived from Yahoo Finance.


## Strategies
- **Strategy 1: Buy all sell all** - The autotrader will automatically buy when the signal indicates "Buy" and will sell once signal indicates "Sell."

- **Strategy 2: Buy all sell all with stop loss** - The autotrader will automatically buy when the signal indicates "Buy." Once the signal issues a "Sell," the autotrader will not sell unless the trade is profitable or if the percent loss of the trade reaches the stop loss percentage inputted by the user.

- **Strategy 3: Buy all sell all with take profit** - The autotrader will automatically buy when the signal indicates "Buy." Once the signal issues a "Sell," the autotrader will sell if the trade is a loss or if the percent profit reaches the take profit percentage inputted by the user.

- **Strategy 4: Buy all sell all with stop loss and take profit** - The autotrader will automatically buy when the signal indicates "Buy." Once the signal issues a "Sell," the autotrader will sell if the percent loss of the trade reaches the stop loss percentage inputted by the user or if the percent profit reaches the take profit percentage inputted by the user.

- **Strategy 5: Accumulate buy and sell** - The autotrader will buy when the signal indicates a "Buy." If the next signal is another "Buy," the autotrader will only buy if the price is less than the price of the previously bought stock. The goal of this is to accumulate stock and lower down its cost per unit stock. The autotrader will immediately sell when the signal indicates a "Sell." This strategy does not have any stop loss or take profit.

_Note_: The five strategies consist of long trades only and can only handle one trade at a time.


## Configurations and preferences:

- **Starting balance**: amount of money that will be used for trading
- **Volume**: amount of stock that will be consistently bought or sold per trade
- **Stop Loss**: the percentage at which the autotrader will declare a loss
- **Take Profit**: the percentage at which the autotrader will declare a profit


## Acknowledgement
I would like to thank Dr. Kardi Teknomo for his guidance in this project.