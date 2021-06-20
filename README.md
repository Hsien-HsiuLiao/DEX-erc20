## Summary
DAI Stablecoin used as quote currency. Before users can trade, they first need to transfer their Ether to the DEX by using the Wallet component of the DEX UI. Then, 
users can create limit or market buy/sell orders for BAT/REP/ZRX mock tokens. Orders will be displayed in All Orders component. If there is a match, trade will be executed and the All Trades component will update the chart and the table for amount/price/date. User will also see My Orders component with their BUY/SELL orders and update when orders are filled. 

## Testing on local machine

`npm install`

To view frontend in browser, first run development blockchain

`truffle develop`

`migrate --reset`

then in the project directory in another terminal,

`cd client`

`npm start`

![](./screenshots/screenshot1.png)

![](./screenshots/screenshot2.png)



### Libraries used:

~~SafeMath library from OpenZeppelin was used and imported in Dex.sol~~

### Resources
https://blog.logrocket.com/the-definitive-guide-to-scss/