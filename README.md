# TypeScript Blockchain

## Summary:

 - What is this
 - How does it work
 - How to run

## What is this

This project is a cyptocurrency blockchain template API, developed with *** TypeScript, NodeJs *** and Postman for requests to the API.

This blockchain has many standard features of popular blockchains like Bitcoin and Ethereum. Many of these features are taken from the original Bitcoin whitepaper:

 - peer to peer secure blockchain server that accepts multiple connections through a published REST API
 - autonomous blockchain network with clients that can engage and disengage from the blockchain
 - full blockchain replication among all the clients
 - timestamp on each block so they can be properly ordered
 - mining with a proof of work system for adding new blocks to the blockchain with a dynamic difficulty level and a financial incentive
 - transaction system for transferring funds between nodes
 - secure wallets for storing a public-private key pair
 - digital signatures (SHA-256) and payment verification
 - full suite of unit tests for every aspect of the system

## How does it work

This app have a few routes to access it's functions:

> /mine

adds new block to blockchain - generic mine endpoint for mining any data

> /transact

create a transaction with user's wallet and broadcast it to other nodes

> /balance

view balance

> /blocks

view all blocks on blockchain

> /mine-transactions

mines new block with transaction data

> /public-key

show wallet's public key

> /transactions

view all transactions


## How to run

```bash
    git clone https://github.com/Arthur-Matias/typescript-blockchain.git
    cd ts-blockchain
```

#### then just (both Yarn or NPM):

To run in development mode:

```bash
    yarn install
    yarn dev
```

or build and run:

```bash
    yarn install
    yarn build
    yarn start
```

> based on [this project](https://github.com/gomisha/blockchain)
