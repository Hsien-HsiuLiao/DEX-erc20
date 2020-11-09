`npm install`

To view frontend in browser, first run development blockchain

`truffle develop`

`migrate --reset`

then,

`cd client`

`npm start`

![](./screenshots/screenshot1.png)

![](./screenshots/screenshot2.png)

## Testing

https://stackoverflow.com/questions/52690481/how-to-create-new-ethereum-solidity-contract-for-each-test-in-javascript-truffle

> The .new keyword will deploy an instance of your contract in a new context.

But, .deployed will actually use the contract that you have deployed earlier i.e. when you are using truffle migrate command.

In the context of unit test, it's better to use .new so that you will always start with fresh contract.

https://twitter.com/zulhhandyplast/status/1026181801239171072

> Use 'deployer.deploy(YourContract)' in your migration file if you want to store the contract address in the build directory.

If you use 'http://YourContract.new()', the address won't get saved in the build directory.

https://www.trufflesuite.com/docs/truffle/getting-started/interacting-with-your-contracts