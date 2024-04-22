
# CustomToken Contract

This Solidity contract, named `Token`, is an ERC20 token contract deployed on the Ethereum blockchain. It enables users to interact with a custom token named "CTK" and includes functionality for minting, burning, transferring tokens, and redeeming ice cream flavors using tokens.

## Features

### ERC20 Standard Compliance

The contract follows the ERC20 standard, providing basic functionalities such as transferring tokens between addresses and querying token balances.

### Ice Cream Redemption

Users can redeem various flavors of ice cream using their tokens. Each flavor has a specific price and a limited stock. When a user redeems ice cream, the corresponding amount of tokens is deducted from their balance, and the ice cream stock is reduced accordingly.

## Usage

### Minting Tokens

Only the contract owner can mint new tokens. This function (`mintTokens`) allows the owner to create additional tokens and assign them to a specific address.

### Burning Tokens

Users can burn their tokens using the `burnTokens` function. This action permanently removes tokens from the user's balance.

### Transferring Tokens

Users can transfer tokens to other addresses using the `transferTokens` function.

### Redeeming Ice Cream

Users can redeem ice cream flavors using their tokens. The `redeemIceCream` function deducts the appropriate amount of tokens from the user's balance and decreases the available stock of the selected ice cream flavor.

## Ice Cream Flavors

The contract currently supports the following ice cream flavors, each with its own price and initial stock:

- Vanilla
- Chocolate
- Strawberry
- Mint
