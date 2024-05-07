# Foundry ChainTools - OurToken

## Introduction

This repository contains a Solidity smart contract, deployment script, and test suite for the OurToken ERC20 token.

## Contract

The `OurToken.sol` contract is an ERC20 token implementation that extends the OpenZeppelin ERC20 contract. It provides basic functionalities for managing tokens such as minting and transferring.

## Deploy Script

The `DeployOurToken.sol` script is used to deploy the OurToken contract. It initializes the token with an initial supply specified by the constant `INITIAL_SUPPLY`.

## Tests

The test suite in `OurTokenTest.sol` covers various functionalities of the OurToken contract using the Forge Standard Library (forge-std). It includes tests for transferring tokens, approving allowances, and verifying balances.

## Usage

To use this project:

1. Install dependencies:
   ```bash
   npm install
2. Compile the contracts:
   ```bash
   npx hardhat compile
3. Run tests:
    ```bash 
    npx hardhat test
4. Deploy the contract:
    ```bash 
    npx hardhat run scripts/deploy.js
