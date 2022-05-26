# KaseiCoin Crowdsale
![KaseiCoin Image](./Execution_Results/kaseicoin.jpeg)

This project creates a fungible token that is ERC-20 compliant and that will be minted by using a crowdsale contract from the OpenZeppelin Solidity library. The idea is to develop a monetary system for the first human colony on Mars. The new monetary system is based on blockchain technology and defines a new cryptocurrency named KaseiCoin. The crowdsale contract manages the entire crowdsale process, allowing users to send ether to the contract and in return receive KAI, or KaseiCoin tokens. The contract mints the tokens automatically and distributes them to buyers in one transaction. 

---
## Technologies
This project leverages the following tools:
* [Solidity](https://docs.soliditylang.org/en/v0.8.13/) - programming language for implementing smart contracts
* [Remix IDE](https://remix.ethereum.org/#optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.7+commit.e28d00a7.js) - open source tool that helps you write Solidity contracts straight from the browser; has modules for testing, debugging, and deploying of smart contracts
* [Ganache](https://trufflesuite.com/ganache/) - A program that allows you to quickly set up a local blockchain, which you can use to test and develop smart contracts
* [MetaMask](https://metamask.io/) - allows users to store and manage account keys, broadcast transactions, send and receive Ethereum-based cryptocurrencies and tokens, and securely connect to decentralized applications through a compatible web browser or the mobile app's built-in browser

The Solidity version used for this project was the following:
`pragma solidity ^0.5.5`

OpenZeppelin Libraries to Import:

```
ERC20 Token:
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20.sol";
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20Detailed.sol";
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20Mintable.sol";


Crowdsale:
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/Crowdsale.sol";
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/emission/MintedCrowdsale.sol";

```

---

## Installation Guide
If you do not already have these tools installed, install them now: 
1. Download and install the MetaMask browser extension. Follow the [instructions here](https://metamask.io/download/) to install it.
2. Download and install the lastest version of Ganache. Follow the [instructions here](https://trufflesuite.com/ganache/) to install it. To create a workspace, click on "Quickstart Ethereum".

---

## Usage

---

## Methods
1. Create the KaseiCoin Token Contract
2. Create the KaseiCoin Crowdsale Contract
3. Create the KaseiCoin Deployer Contract
4. Deploy the Crowdsale to a local blockchain by using Remix, MetaMask, and Ganache


---

## Evaluation Evidence
Here are examples of the KaseiCoin crowdsale in action:

### Deployed Contract


---

## Contributors
Catherine Croft

Email: catherinecroft1014@gmail.com

LinkedIn: [catherine-croft](https://www.linkedin.com/in/catherine-croft-4715481aa/)

---

## License 
MIT