# SunilToken (SUNIL) ERC-20 Token Contract

## Overview

This is the official smart contract for the SunilToken (SUNIL) ERC-20 token. SunilToken is designed to follow the Ethereum ERC-20 standard and includes basic functions for transferring tokens, approving spending, and transferring tokens on behalf of others.

## Contract Details

- **Name**: SunilToken
- **Symbol**: SUNIL
- **Decimals**: 18
- **Total Supply**: 1,000,000 SUNIL tokens

## Token Functions

The contract includes the following functions:

1. `transfer(address _to, uint256 _value)`: Transfers tokens from the sender's address to the specified recipient. It checks for available balances and emits a `Transfer` event upon successful transfer.

2. `approve(address _spender, uint256 _value)`: Approves another address to spend tokens on your behalf. This function allows for the delegation of spending rights.

3. `transferFrom(address _from, address _to, uint256 _value)`: Allows an approved spender to transfer tokens from one address to another. It checks for available balances and allowance.

## Usage

You can interact with this contract using Ethereum-compatible wallets or by deploying and interacting with it directly on the Ethereum blockchain. Here's how you can use it:

- **Transferring Tokens**: Use the `transfer` function to send SUNIL tokens from your address to another Ethereum address. Make sure you have a sufficient balance.

- **Approving Spending**: Use the `approve` function to grant another address permission to spend a certain number of SUNIL tokens on your behalf.

- **Transferring on Behalf of**: If you have been approved to spend tokens on someone else's behalf, use the `transferFrom` function to make the transfer.

## Deployment

You can deploy this contract on the Ethereum blockchain, and the initial total supply of SUNIL tokens will be assigned to the deployer's address.

## License

This contract is released under the MIT License. You can find the license details in the `SPDX-License-Identifier` section of the contract.

## Important Notes

- This contract is provided as-is and without any warranties. It is your responsibility to ensure its proper deployment and usage.
- Be mindful of gas costs when interacting with the contract on the Ethereum network.
