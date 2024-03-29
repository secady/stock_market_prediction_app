This is a demo of an analytics app created by Selvie. The app is an AI bot that helps us collect the stock market data, analyze it, predict stocks prices (Close Price), generate a recommendation and check the forecast accuracy on a real-time basis. To watch the demo, please check out this Youtube link: https://www.youtube.com/watch?v=WiNauEPT55I.

App Functionality (Minimum Viable Product):
- For Demo purpose, this app only contains IBEX 35 weekly data
- By default, the week starts on Monday. If we are in the week of 2023.10.09, then the bot will do the forecast for the next 8 weeks starting from the week of 2023.10.16. Once the week of 2023.10.16 has come, the bot will check the accuracy of the last week forecast.
- If the forecast shows an uptrend in the next 8 weeks, the app will give a "buy" recommendation at the lowest forecasted price and a "sell" recommendation at the highest forecasted price. Otherwise, it will suggest to "hold".
- The accuracy is checked based on the range of "Low" and "High" prices within the corresponding week. If the forecasted Close Price falls within the low-high range, then we consider it accurate because any purchase/sales order placed at the forecasted Close Price will be most likely executed.

Possible future development:
- Add more time intervals (minutely/hourly/daily/monthly)
- Add fundamental analysis (based on Financial report indicators)
- Models optimization to increase the accuracy

Here are the tools used in building this web app:
- Python programming language to create backend and frontend (interactive dashboard) parts of the app
- AWS RDS (Amazon Relational Database Service) - MySQL database
- AWS EC2 (Amazon Elastic Compute Cloud) for cloud deployment

The app is currently deployed on AWS. Please kindly contact the creator if you would like to see the live demo.

<br>Disclaimer: ON!!! The creator doesn't have any intention to encourage people to invest in stock market or to follow the recommendation. This app was made for educational purpose.
