# Polygon-Bridge

This project involves the creation, deployment, and management of an NFT (Non-Fungible Token) collection using various tools and technologies.

## Overview

This repository contains scripts and contracts to facilitate the creation, deployment, and management of an NFT collection. The collection is generated using DALLE 2 or Midjourney AI, stored on IPFS via pinata.cloud, deployed on the sepolia Ethereum Testnet using ERC721 or ERC1155 contracts. Additionally, it includes scripts to mint and transfer NFTs between Ethereum and Polygon amoy using the FxPortal Bridge.

## Features

- **NFT Generation**: Utilizes DALLE 2 or Midjourney AI to generate a 5-item NFT collection.
- **IPFS Storage**: Stores NFT images on IPFS using pinata.cloud for decentralized storage.
- **Blockchain Deployment**: Deploys ERC721 or ERC1155 contracts on the sepolia Ethereum Testnet.
- **Metadata**: Implements a `promptDescription` function on the contract to retrieve the prompt used for image generation.
- **Polygon Integration**: Maps the NFT collection using the Polygon network token mapper for visualization.
- **Hardhat Scripts**:
  - `batch-mint.js`: Script to batch mint all NFTs, optimized for ERC721A.
  - `batch-transfer.js`: Script to batch transfer all NFTs from Ethereum to Polygon amoy using the FxPortal Bridge.
- **Testing**: Includes tests for functionalities such as checking balances (`balanceOf`) on Polygon amoy.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Configuration**:
   - Update `.env` file with necessary API keys and addresses.

4. **Deployment**:
   - Deploy contracts to sepolia Ethereum Testnet using Hardhat.
   - Use Polygon network token mapper for mapping.

5. **Scripts Execution**:
   - Execute Hardhat scripts (`batch-mint.js` and `batch-transfer.js`) to mint and transfer NFTs.

6. **Testing**:
   - Run tests to verify functionality on Polygon amoy.

## Contributing

Contributions are welcome! Fork this repository, make your changes, and submit a pull request. For major changes, please open an issue first to discuss potential updates.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Feel free to adjust and expand this template based on your specific project details and requirements!
- - -
