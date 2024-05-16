# -ERC20-token
# MyToken ERC20 Contract

This is a simple implementation of an ERC20 token contract using the OpenZeppelin library. The contract allows minting, burning, and transferring tokens, with the ability to mint new tokens restricted to the contract owner.

## Features

- ERC20 compliant token with a fixed supply of 1,000,000 tokens
- Token name: "MyToken"
- Token symbol: "MTK"
- Decimals: 18 (same as Ether)
- Contract owner can mint new tokens and transfer them to any address
- Token holders can burn (destroy) their own tokens
- Transfer tokens between accounts
- Transfer tokens on behalf of another account (if approved)

## Prerequisites

- Solidity compiler version 0.8.0 or later
