# Wonderman time locker token contract for binance smart chain and Ethereum if needed,

This utility smart contact will be used to build dApps to lock WONDR BEP20 Tokens (Depends on deployment chain) to a smart contract for specific period of time. It can be leveraged to lock ERC20 variant tokens if required.

### Quick Documentation
Fees in BNB/ETH or in percent in Smart Contract file. The smart contract owner can manage these values after deploying smart conract.

#### Files and usage
##### .secret
File which contains 12 secret mnemonic phrases of your hd wallet.

##### Deploy smart contact
 - ```npm install```
 - Copiling smart contract ```truffle compile```
 - Deploying smart contract - ```truffle migrate --network=testnet``` Choose network from ```truffle-config.js``` file.
 - Verify smart contract on bscscan/etherscan (API Keys are needed)- ```truffle run verify Airdrop@{ContractAddress} --network testnet```
 - Once smart contract is deployed and verified, you can interect it from bscscan/etherscan

## Authors

* Hiren Kavad
* Bill Petridis

## License

This bundle is dual-licensed under MIT and GPL licenses.

* [http://www.opensource.org/licenses/mit-license.php](http://www.opensource.org/licenses/mit-license.php)
* [http://www.gnu.org/licenses/gpl.html](http://www.gnu.org/licenses/gpl.html)

Feel free to use this contract but please leave the author attribution.

## Project information
* https://www.wondermannation.com/


