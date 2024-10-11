# Project-Create-a-Token

## Description
This Solidity project implements a simple token system. The token contract includes basic functionality for minting and burning tokens, while keeping track of token balances and total supply. 

### Key Features:
- **Token Information**: The contract publicly stores details about the token, abbreviation, and the total supply of tokens.
- **Minting Functionality**: New tokens can be created and assigned to a specific address. The total supply of tokens is increased by the number of tokens minted, and the recipient's balance is updated accordingly.
- **Burning Functionality**: Allows token holders to eliminate tokens, reducing the total supply and the balance of the address holding the tokens. It also includes checks to ensure that the address has sufficient tokens before proceeding.

### Resources Used:
- Remix IDE: [Remix Ethereum](https://remix.ethereum.org/)

### Requirements
    1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
    2. Your contract will have a mapping of addresses to balances (address => uint)
    3. You will have a mint function that takes two parameters: an address and a value. 
       The function then increases the total supply by that number and increases the balance 
       of the “sender” address by that amount
    4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
       It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
       and from the balance of the “sender”.
    5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal 
       to the amount that is supposed to be burned.
       
## Authors
Aciel07
