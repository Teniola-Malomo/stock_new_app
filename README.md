# Stock News App

## Description
Looks for a companies stock and sends a news report by sms message, if there is difference of 5%.

## Implmentation

###### Imports:
    from twilio.rest import Client

###### API Endpoints and use: 
- [Alphavantage](https://www.alphavantage.co/query) 
  - Get requests to get companies stock data
- [Newsapi](https://newsapi.org/v2/everything)
  - Get requests to new reports
- [Twilio](https://www.twilio.com)
  - to send sms messages


###### Flies responsible for what:
- Made a get request for the companies stock data.
- Took yesterdays closing stock and the day before.
- Calculated the percentage difference for the stock.
- Made a get request for the news reports.
- Sent a sms message if the difference is greater than 5.
