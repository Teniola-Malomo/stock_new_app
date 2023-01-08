# Stock News App

## Description
Looks for a companies stock and sends a news report if there is difference of 5% by an sms message.

## Implmentation

###### Imports:
    from twilio.rest import Client

###### API Endpoints and use: 
- [Alphavantage](https://www.alphavantage.co/query) 
  - Get requests to get companies stock data
- [Newsapi](https://newsapi.org/v2/everything)
  - Get requests to get airport codes and flight data
- [Twilio](https://www.twilio.com)
  - to send sms messages


###### Flies responsible for what:
- Made a get request for the companies stock data
- Took yesterdays closing stock and the day before
- Calculated the percentage difference
- Made a get request for the news reports
- Sent a sms message if the difference is greater than 5
