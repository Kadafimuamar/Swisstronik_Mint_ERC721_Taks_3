# Swisstronik-erc-721

This repository contains a setup for deploying and interacting with an ERC-721 token on the Swisstronik testnet using Hardhat. The setup includes scripts for deploying the contract, minting tokens, and transferring tokens, utilizing encrypted transactions with Swisstronik.

## Prerequisites

Ensure you have the following installed:

- Node.js (version 14.x or later)
- npm (version 6.x or later)

## Faucet

https://faucet.testnet.swisstronik.com/

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Kadafimuamar/Swisstronik_Mint_ERC721_Task_3.git
    cd Swisstronik_Mint_ERC721_Task_3
    ```

2. Run

    ```bash
    npm install --save-dev @nomicfoundation/hardhat-toolbox
    npm install dotenv
    npm install @swisstronik/utils
    npm install @openzeppelin/contracts
    ```

## Create File .env for Private Key (Keep Safe for this)

1. 

```bash
    PRIVATE_KEY=YOUR-PRIVATE-KEY
```



## Running

1. Compile

 ```bash
    npx hardhat compile
```

2. Deploy Erc-20

 ```bash
    npx hardhat run scripts/deploy.js --network swisstronik
```

2. Minting Erc-71

 ```bash
    npx hardhat run scripts/mint.js --network swisstronik
```

Success TX will appear like this :
![Jepretan Layar 2024-07-29 pukul 01 23 27](https://github.com/user-attachments/assets/1f543f25-84b1-422a-89b5-6ccb1a67146d)


