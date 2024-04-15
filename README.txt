## NFT Marketplace README

Welcome to the decentralized NFT Marketplace project on the Ethereum blockchain! This repository contains the smart contract code required to create a marketplace where users can securely and transparently buy and sell non-fungible tokens (NFTs).

### About the Project

The main goal of this project is to provide a decentralized platform where creators and collectors of NFTs can interact without intermediaries, thus facilitating the buying and selling of unique digital assets. With this Marketplace, users can:

- **Create NFT Listings**: Users can create listings for their NFTs, specifying the NFT contract, token ID, and asking price.
- **Purchase NFTs**: Other users can purchase listed NFTs using Ether (ETH), the native cryptocurrency of Ethereum.
- **Commission Fee**: The contract includes a commission mechanism where a percentage of the transaction is collected as a fee for the service provided.

### Contracts

#### Marketplace.sol

`Marketplace.sol` is the smart contract responsible for managing the Marketplace functionality. This contract allows users to create and purchase NFT listings. Key features include:

- **Listing Creation**: Users can create listings by specifying the NFT contract, token ID, and price.
- **Listing Purchase**: Other users can purchase listings using Ether.
- **Commission Mechanism**: The contract collects a fee on each transaction, with a percentage of it being sent to the designated account.

#### NFT.sol

`NFT.sol` is the smart contract for creating ERC721-compliant non-fungible tokens (NFTs). This contract allows users to create their own NFTs with associated metadata. Key features include:

- **NFT Creation**: Users can create new NFTs with associated metadata URI.
- **ERC721 Compliance**: Fully compliant with the ERC721 standard for NFTs.

### Setup

To deploy and interact with these contracts, you'll need an Ethereum development environment such as Truffle or Hardhat. You'll also need to install dependencies specified in the `package.json` file.

### Deployment

Deploy the contracts to an Ethereum network of your choice, such as the Ethereum mainnet, Rinkeby testnet, or a local development network.

### Usage

1. Deploy the `NFT` contract to create NFTs.
2. Deploy the `Marketplace` contract to create a decentralized marketplace.
3. Mint NFTs using the `NFT` contract.
4. Create listings for these NFTs using the `Marketplace` contract.
5. Purchase listings using Ether by calling the `purchaseItem` function on the `Marketplace` contract.

