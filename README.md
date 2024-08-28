# BTEG-Contract.
Smart contract for the Bitcoin Edge (BTEG) token on the Base Network.
# Bitcoin Edge (BTEG) Token

Welcome to the official repository for the **Bitcoin Edge (BTEG) Token** on the Base Network. This repository contains the source code for the BTEG token smart contract, along with documentation on how to interact with and contribute to the project.

## Project Overview

**Bitcoin Edge (BTEG)** is a decentralized cryptocurrency inspired by Bitcoin's principles of scarcity and trust. Built on the Base Network, BTEG aims to combine the best aspects of Bitcoin with advanced capabilities, providing a secure and scalable financial ecosystem.

Our mission extends beyond just creating a cryptocurrency—we aim to **decentralize all aspects of the global economy**. By leveraging blockchain technology and smart contracts, BTEG strives to create a fully decentralized financial system where power is distributed among the community, and all transactions are transparent, secure, and efficient.

- **Token Name:** Bitcoin Edge
- **Symbol:** BTEG
- **Decimals:** 18
- **Total Supply:** 21,000,000 BTEG

## Features

- **Fully Decentralized:** The BTEG contract is designed to operate without central control, ensuring trust and transparency.
- **Fixed Supply:** The total supply of BTEG is capped at 21 million tokens, mirroring Bitcoin's scarcity model.
- **Renounced Ownership:** The contract ownership has been renounced, making the contract fully community-driven and immutable.

## Getting Started

### Prerequisites

To interact with the BTEG smart contract, you'll need:

- **Node.js**: Install [Node.js](https://nodejs.org/).
- **Truffle or Hardhat**: These are frameworks for Ethereum development. You can install Truffle using:
  ```bash
  npm install -g truffle
Or install Hardhat by following the official guide.

Deployment
To deploy the BTEG contract on the Base Network, follow these steps:

Clone the repository:
git clone https://github.com/YourUsername/BTEG-Contract.git
cd BTEG-Contract
Install dependencies:
npm install
Compile the contract:
truffle compile
Deploy to the Base Network:
truffle migrate --network base
Interacting with the Contract
You can interact with the BTEG contract using the following functions:

Transfer Tokens:
function transfer(address to, uint256 value) external returns (bool);
his function allows you to transfer BTEG tokens to another address.
Check Balance:
function balanceOf(address account) external view returns (uint256);
This function returns the token balance of a given address.
Contributing

We welcome contributions from the community. If you'd like to contribute:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a Pull Request.
Please ensure that your code adheres to the project's coding standards and is thoroughly tested before submission.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Contact

For any questions or support, please reach out via contact@bitcoinedge.io.
