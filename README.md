# MyToken Contract

 Overview
This Solidity contract implements a basic token (MyToken) with functionalities to mint new tokens and burn existing tokens. It adheres to the ERC-20 standard with simplified features for demonstration purposes.

 Requirements
1. The contract includes public variables to store details about the coin (Token Name, Token Abbreviation, Total Supply).
2. It utilizes a mapping to track balances of addresses.
3. Includes a mint function to increase the total supply and the balance of a specified address.
4. Implements a burn function to decrease the total supply and the balance of a specified address, with appropriate checks to ensure sufficient balance.
5. The burn function includes conditionals to ensure the balance of the sender is greater than or equal to the amount being burned.

 Contract Details
- **Token Name**: MyToken
- **Token Abbreviation**: MTK

 Functions
- **mint(address _to, uint _value): Increases the total supply and adds tokens to the balance of `_to`.
- **burn(address _from, uint _value): Decreases the total supply and deducts tokens from the balance of `_from`, ensuring sufficient balance.

 License
This contract is licensed under the MIT License. See `LICENSE` for more information.

