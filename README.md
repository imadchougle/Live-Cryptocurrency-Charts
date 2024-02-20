Live working Website link : https://imadchougle.github.io/Live-Cryptocurrency-Charts/


### Introduction


The Live Cryptocurrency Chart is a web application that allows users to visualize real-time cryptocurrency price data using charts. The chart provides a graphical representation of price movements over varying time intervals, aiding users in analyzing market trends, identifying patterns, and formulating trading strategies. By leveraging candlestick charts, which display the open, high, low, and close prices within a specified time frame, users can gain a comprehensive view of price dynamics and market sentiment.
With support for popular cryptocurrencies like Bitcoin (BTC), Ethereum (ETH), and Solana (SOL), users can track the performance of specific digital assets that interest them
Users can select different cryptocurrencies (BTC, ETH, SOL) and time intervals (1 Minute, 1 Hour, 1 Day) to view historical price movements with their live price. offers flexibility in analyzing short-term fluctuations or long-term trends.
User can also see the Live Cryptocurrency returns also for 7 days, 1 month and 1 year below 
The Live Cryptocurrency Chart provides an interactive way for users to monitor cryptocurrency price movements in real-time

### Features

•	Real-time candlestick chart visualization.
•	Selection of cryptocurrencies (BTC, ETH, SOL).
•	Selection of time intervals (1 Minute, 1 Hour, 1 Day).
•	User-friendly interface with responsive design.
•	Responsive chart with zoom in, zoom out
•	Extend Price Scale and Time Scale
•	Crosshair with close price
•	Legend Display: The legend displays the current time frame and selected cryptocurrency.
•	Return on investments for 7 days, 1 month and 1 year.

### Dependencies

Binance API: The Binance API is utilized for fetching historical price data of cryptocurrencies. It provides the necessary data to render the candlestick chart with up-to-date information.
Trading View Lightweight Charts Library: The Lightweight Charts library is used for rendering the candlestick chart. 
Font Awesome and SVG Icons: Font Awesome and SVG icons are utilized for displaying cryptocurrency symbols.


### Implementation Details

The application is built using HTML, CSS, and JavaScript.
Candlestick chart rendering is handled by the Lightweight Charts library.
Data fetching is done from the Binance API, which provides historical price data for the selected cryptocurrency and time interval.
The data type is in Json format
Event listeners are used to handle user interactions (click events on cryptocurrency and time interval buttons)
Used Live Server on Vscode for Implementation

### Process Flow

Step 1: Launch Application
User opens the Live Cryptocurrency Chart web application.

Step 2: Default Settings (BTC 1 Minute)
By default, the chart displays the price movements of Bitcoin (BTC) with a 1-minute time interval.

Step 3: Select Cryptocurrency
User selects a cryptocurrency from the available options (BTC, ETH, SOL).

Step 4: Choose Time Interval
User selects a time interval for data visualization (1 Minute, 1 Hour, 1 Day).

Step 5: Fetch Data
Application fetches historical price data for the selected cryptocurrency and time interval from the Binance API.

Step 6: Render Chart
The Lightweight Charts library renders a candlestick chart based on the fetched data.

Step 7: Display Chart
The candlestick chart is displayed to the user, showing the price movements of the selected cryptocurrency over the chosen time interval.

Step 8: Interact with Chart
User can interact with the chart by zooming in/out, extending the timescale, and viewing crosshair details.

Step 9: Analyze Data
User analyzes the price data on the chart to make informed decisions regarding cryptocurrency trading or investment.

Step 10: Return over Investment
User can see the Live ROI in the dashboard itself

### Use cases

1.	Real-time Monitoring: Traders and investors can use the chart to monitor cryptocurrency prices in real-time. They can track price movements, identify trends, and make timely decisions based on the current market conditions.
2.	Trading Strategy Development: Traders can use the chart to develop and test trading strategies. By analyzing historical price data across different time intervals
3.	Comparison of Cryptocurrencies: Users can compare the price movements of different cryptocurrencies, such as Bitcoin, Ethereum, and Solana, on the same chart. This can help them identify strength.
4.	Long-term Investment Analysis: Investors can use the chart to analyze long-term trends and assess the potential for long-term investment opportunities. 
5.	Tracking Returns: Users can track the return on investment (ROI) of their cryptocurrency holdings over different time frames, such as 7 days, 1 month, and 1 year. 
