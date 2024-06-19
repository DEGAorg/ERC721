# DEGA ERC721 Smart Contract

This repository contains the ERC721 smart contract used by DEGA. The contract is based on ThirdWeb's smart contract `TokenERC721.sol` and includes the main logic extracted from [`contracts/prebuilts/token/TokenERC721.sol`](contracts/prebuilts/token/TokenERC721.sol).

## Overview

The purpose of this repository is to present the codebase of the DEGA ERC721 smart contract to the public. The contract has been streamlined to include only the essential logic and a few utility functions developed by ThirdWeb. All other files, interfaces, and known OpenZeppelin contracts have been removed for simplicity.

## Contract Details

The DEGA ERC721 smart contract follows the ERC721 standard for non-fungible tokens (NFTs). It includes the following features:
- Minting of new tokens
- Transfer of ownership
- Metadata management
- Compatibility with various ERC721-compliant platforms

### Smart Contract Location

The main smart contract can be found in the following file:
[`contracts/prebuilts/token/TokenERC721.sol`](contracts/prebuilts/token/TokenERC721.sol)

### Imports

The contract imports a couple of utility files developed by ThirdWeb, ensuring the core functionality remains intact and efficient.

## Verification

The smart contract can be fully checked and verified on block explorers. This ensures transparency and allows users to inspect the contract code and verify its authenticity.
