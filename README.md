# hardhat-web3

### Web3.js Hardhat JS Template
Contains template using: Web3.js, Hardhat and JavaScript

### Web3.js Hardhat TS Template
Contains template using: Web3.js, Hardhat and TypeScript

## Introduction

This project demonstrates a basic Hardhat use case, focusing on deploying and testing smart contract on Hardhat. It includes a sample contract, a test for that contract, and a script that deploys the contract.

The project utilizes:
- Hardhat as the development environment
- Chai for assertions
- web3.js for interacting with Ethereum

## Prerequisites

- [Node.js and npm](https://nodejs.org/en/download/) (latest version)
- Basic understanding of JavaScript and Ethereum smart contracts

## Getting Started

Follow these steps to set up and run the project locally.

### Installation

1. Clone the repository:
   
   `git clone git@github.com:web3/hardhat-web3.git`

2. Install NPM packages:
   
   `npm install`

### Compiling the Contract

Compile the smart contract with:

`npx hardhat compile`

This compiles contracts in the `contracts/` directory and generates artifacts.

### Running Tests

Execute tests with:

`npx hardhat test`

This runs all test files in the `test/` directory.

## Project Structure

- `contracts/`: Solidity smart contracts
- `test/`: Test files for smart contracts
- `hardhat.config.js`: Hardhat configuration
