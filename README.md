## Summary
This is a decentralized exchange (DEX) for ERC20 tokens. DAI Stablecoin used as quote currency. Before users can trade, they first need to transfer their Ether to the DEX smart contract by using the Wallet component of the DEX UI. Then, 
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

~~SafeMath library from OpenZeppelin was used and imported in Dex.sol~~ (functionality included in Solidity 0.8.0)

### Resources
https://blog.logrocket.com/the-definitive-guide-to-scss/

### deployment
https://dex-erc20-131e89.netlify.app/

trader4
0xfF1B6955c7A5ab86e99f237356b200DA518516a2
