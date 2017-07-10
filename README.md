# Crypto Exchange Compare

Express and Socket.io app powered by React+ Redux to implement real-time tracking of specified trading pairs such as (BTC-DASH, BTC-ETH, BTC-LTC) from Bittrex, Poloniex and Bitfinex

* install dependencies
```yarn install```
* install ``rimraf`` globally for use in production build
```yarn global add rimraf```
* run in dev
```yarn run open:src```
* build for prod
``` yarn run build```

## TODO
* fetch user from database(mongodb)
* store historical data to db and use d3 to display it
* make exchangeSocketApi consumable by third party
* spinner until data arrives from all 3 exchanges