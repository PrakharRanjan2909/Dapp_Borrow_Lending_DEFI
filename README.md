## Table of Contents

- [Introduction](#introduction)
- [Technology Stack](#technology-stack)
- [Project Layout](#project-layout)
  - [Top Level folders](#top-level-folders)
  - [Important Files](#important-files)
- [Using & Testing DApp on Sepolia](#using--testing-DApp-on-sepolia)
- [Cloning and Deploying the Dapp on Sepolia Testnet](#cloning-and-deploying-the-dapp-on-sepolia-testnet)


## Introduction
This DeFi Lending & Borrowing decentralized application (DApp) operates on **Ethereum's Sepolia Testnet**. 


## Technology Stack

- Built on Ethereum Blockchain
- Solidity
- Javascript
- Typescript
- Chainlink Price Oracles
- Openzeppelin (ERC20 Tokens, Ownable, Reentrancy Guards)
- Hardhat
- Etherjs
- Metamask
- Infura Web3API
- Next JS
- Tailwind CSS
- HTML

## Project Layout

### Top Level folders

1. /components - contains the front-end application
2. /context - contains the front-end application wrapper javascript
3. /contracts - contains the solidity contract
4. /pages - Next Js Main rendering pages and components


### Important Files

1. package.json - node modules to be installed, etc.
2. .env - To store Infura/Alchemy API keys and your private key

## Using & Testing DApp on Sepolia

1. Metamask : Install Metamask wallet extension

2. Add Sepolia Testnet to MetaMask

3. Using the App : 

## Cloning and Deploying the Dapp on Sepolia Testnet

1. Clone this repo :

```
git clone https://github.com/PrakharRanjan2909/Dapp_Borrow_Lending_DEFI.git
```

2. Go to the root directory and install all node packages

```
cd Dapp_Borrow_Lending_DEFI
npm install
```

3. Please Create a new Infura API key
   [Follow this article to get Infura API key](https://medium.com/jelly-market/how-to-get-infura-api-key-e7d552dd396f)

   **_Select Sepolia testnet and copy the url_**


4. Now copy Metamask wallet private key : https://support.metamask.io/hc/en-us/articles/360015289632

5. Create a new .env file in the root directory

   **_Paste the Infura Sepolia API key and your metmask accounts private key into .env file_**
    INFURA_SEPOLIA_API_URL=""

    MAIN_ACCOUNT = ""
   

6. Start NextJs Node Server

```
npm run dev
```


