# Boilerplate to get contracts deployed on the blockchain

## npm packages used
- dotenv
    - configure .env to include api key and private key.
- hardhat
    - run <code> npm install hardhat --save-dev </code>
    - spin up a hardhat project and configure the <code> hardhat.config.js </code>
    - use <code> API_KEY </code> & <code> PRIVATE_KEY </code> from dot env to deploy to the blockchain
- <code> npm install alchemy-sdk --save-dev </code>

## assets needed
since we use alchemy we'll need the api key from our developer dashboard
we'll also need the private key from our metamask wallet

## needed doc lists
- https://hardhat.org/docs
- https://docs.alchemy.com/reference/api-overview
- https://docs.soliditylang.org/en/v0.8.19/
- https://docs.npmjs.com/