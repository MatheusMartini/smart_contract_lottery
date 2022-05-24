# smart_contract_lottery

### `Steps for you to follow`

First, you should be have acount in bscScan, before, you need a create a [Api](https://bscscan.com/myapikey). 
### `create a truffle-config.js`

After creating your api in BscScan, you must change the truffle-config.txt file to .js and put your api there

### `create a .secret`

In the project directory you need a .secret and put your secret backup phrase of MetaMask

In the project directory, you can run:
### `npm Install`

To dowload dependencies in package.json
## Steps for build
### `truffle migrate --network bsctest`

After the command, it will generate the contract, you should take it and put it in the command below and run
### `truffle run verify Lottery@YuorContract --network bsctest`
