# DegenToken

DegenToken is an ERC20 token contract deployed on the Ethereum blockchain. It also provides functionality for managing NFT (Non-Fungible Token) items.

## Features

- ERC20 Compliance: DegenToken follows the ERC20 standard, allowing for seamless integration with other ERC20-compatible platforms and wallets.
- NFT Item Management: The contract allows the owner to define and manage NFT items, each with a unique identifier, name, and price.
- Minting: The owner can mint new Degen tokens and distribute them to specific addresses.
- Burning: Token holders can burn their Degen tokens, effectively reducing the total supply.
- Transfers: Users can transfer Degen tokens to other addresses.
- Redeeming NFTs: Users can redeem NFT items by burning the required amount of Degen tokens.

## Getting Started

To interact with the DegenToken contract, you can use any Ethereum wallet or development environment that supports ERC20 tokens. You'll need the contract address to interact with it.

## Prerequisites

- An Ethereum wallet or development environment
- Knowledge of interacting with Ethereum smart contracts using tools like Remix, Truffle, or web3.js

## Deployment

The contract can be deployed to the Ethereum blockchain using tools like Remix, Truffle, or Hardhat. Make sure to specify the appropriate compiler version (Solidity ^0.8.0) and include necessary dependencies from OpenZeppelin.

## Usage

- Minting: Call the `mint` function to mint new Degen tokens and distribute them to specific addresses.
- Burning: Call the `burn` function to burn Degen tokens, reducing the total supply.
- Transfers: Use standard ERC20 transfer functions to transfer Degen tokens between addresses.
- Redeeming NFTs: Call the `redeem` function with the ID of the NFT item you want to redeem. Ensure you have sufficient Degen tokens to cover the redemption cost.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

