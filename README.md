# Sample Solidity Contract & Deployment

### Installation
`npm install`

### Usage

#### Testing
`npm run test`

#### Compilation
`node compile.js`

#### Deployment
Note: Update the deploy.js file with your Mnemonic (metamask creds) and Infura web url

`node deploy.js`

#### Use the contract

1. Once the deployment is completed, make a note of the Contract address in Rinkeby network
2. Connect Metamask with the Rinkeby network. This can be done from the Remix UI when selected the option of `Injected web3`
3. Use the address of the deployed contract and interact with it. To do setMessage, it will ask permission from Metamask to detect the ether.
4. You can view the transactions happened on the contract by visiting [Ether Scan](https://rinkeby.etherscan.io)
