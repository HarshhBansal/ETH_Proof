**First_Token**
This is the initial token I created using Solidity. It's a straightforward example demonstrating how contracts operate, along with the processes of minting and burning tokens.

**Description**
Solidity is a widely-used programming language for creating smart contracts on the Ethereum blockchain. This example includes two functions that manage the minting and burning of tokens on the network.

Public Variables

string public tokenName - The name of the token.
string public tokenAbbrv - The abbreviation of the token.
uint public totalSupply - The total supply of tokens.

Mappings

mapping(address => uint) public balances - A mapping to store the balance of each address.

Functions

mint(address _address, uint _value)

This function increases the total supply of tokens and adds the specified amount of tokens to the balance of the given address.

Parameters:

_address: The address to which the tokens will be minted.
_value: The amount of tokens to be minted.
burn(address _address, uint _value)
This function decreases the total supply of tokens and subtracts the specified amount of tokens from the balance of the given address. The burn operation only occurs if the address has a sufficient balance.

Parameters:

_address: The address from which the tokens will be burned.
_value: The amount of tokens to be burned.
Usage
Deploy the Contract: Deploy the MyToken contract on the Ethereum blockchain using Remix, Truffle, or any other Solidity development environment.

Mint Tokens: Call the mint function to create new tokens and assign them to an address.

**Execution**
To execute this program, you need an IDE that supports Solidity. I used Remix IDE, an online platform, to implement the code. Anyone can use a similar setup to deploy it.
