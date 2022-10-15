# Dapp_Lottery
# Note: Rinkby testnet is not working currently. So you need to change the testnet Rinkby to Gorli
## To run the project:
---
1. Must have to create Metamask wallet
2. Also need to create infura account
3. Then go for deploy.js file (you will find it in the lottery-updated folder) then change/place the Metamask secret 12 word and the infura rinkeby API
---

4. Open the cmd with lottery-updated folder then run the following command:
   ```python
   cd lottery-updated
   npm init
   npm install solc@0.8.9 web3 mocha ganache-cli @truffle/hdwallet-provider
   ```
5. After that open another cmd with the lottery_react folder then simply run the following command:
   ```python
   npm init
   npm install
   npm start
   ```
   
# Extra: TO see the ABI and deployed contract
  ```python
   node deploy.js
   ```   
