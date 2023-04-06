# Boilerplate to get contracts deployed on the blockchain

## Basic Setup
- dotenv
    - <code> npm install dotenv --save-dev </code>
    - configure .env to include api key and private key.
- hardhat
    - run <code> npm install hardhat --save-dev </code>
    - spin up a hardhat project and configure the <code> hardhat.config.js </code>
    - use <code> API_KEY </code> & <code> PRIVATE_KEY </code> from dot env to deploy to the blockchain
- alchemy toolkit
    - <code> npm install alchemy-sdk --save-dev </code>
    - configure scripts for js file
- <code>--save-dev</code> saves the package to package.json file

## Assets Needed To Deploy
Alchemy dashboard for API_KEY: https://dashboard.alchemy.com/
Metamask: PRIVATE_KEY


## Helpful Docs
- https://hardhat.org/docs
- https://docs.alchemy.com/reference/api-overview
- https://docs.soliditylang.org/en/v0.8.19/
- https://docs.npmjs.com/
