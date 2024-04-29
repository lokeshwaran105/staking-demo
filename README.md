# Staking-Demo
A decentralized staking token application built with React.js, Solidity, and deployed to the Polygon Mumbai testnet. Users stake tokens to earn rewards, powered by tested smart contracts and integrated with MetaMask.

## Staking Token Application
This repository houses the codebase for a comprehensive staking token application built on React.js, Solidity, and the Polygon Mumbai testnet.

## Key Features
Secure Token Staking: Users can seamlessly stake their tokens using a MetaMask wallet, with the logic handled by tested Solidity smart contracts.

Reward Generation: The application generates token rewards for staked tokens, providing incentivization for users.

Intuitive Frontend: React.js powers a user-friendly interface for staking and monitoring rewards.

Thorough Testing: Smart contracts are rigorously tested to ensure reliability and minimize vulnerabilities.

Polygon Mumbai Deployment: The application successfully functions on the Polygon Mumbai testnet.

## Getting Started

## 1. Prerequisites

Node.js and npm (or yarn)

MetaMask wallet

Basic familiarity with React.js, Solidity, and blockchain concepts

## 2. Clone the Repository

git clone https://github.com/romanlokesh/staking-demo

## 3. Install Dependencies

cd staking-demo

npm install 

## 4. Configure Environment
Create a .env file in the root of the project and add the following variables, replacing placeholders with your project-specific values:

REACT_APP_CONTRACT_ADDRESS=<deployed_contract_address>

REACT_APP_INFURA_KEY=<your_infura_key> 

REACT_APP_PRIVATE_KEY=<metamask_private_key>

## 5. Start the Development Server

npx hardhat run scripts/deploy.js --network <depolyment_network_name>

cd client

npm run dev

## Using the Application

1. Connect MetaMask: Ensure your MetaMask is set to the Mumbai network and has test tokens.
2. Stake Tokens: Use the application's interface to select the amount of tokens you wish to stake and initiate the staking process.
3. Earn Rewards: Rewards will accrue in your wallet over time, according to the smart contract's reward distribution logic.

## Testing

The test directory contains comprehensive test cases for the Solidity smart contracts. A test automation framework like Truffle or Hardhat is essential to execute tests. Refer to relevant documentation for your chosen testing framework.

## Deployment

Instructions for deploying the application to a production environment will depend on your specific hosting setup and your chosen blockchain.

