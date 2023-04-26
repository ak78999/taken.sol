MyToken
MyToken is an ERC20 token smart contract built on the Ethereum blockchain. It is based on the OpenZeppelin ERC20 implementation and includes the Ownable contract for access control.

Deployment
The contract is deployed on the Ethereum mainnet with the following specifications:

Contract Address: [insert contract address here]
Name: MyToken
Symbol: MTK
Decimals: 18
Functions
mint
vbnet
Copy code
function mint(address to, uint256 amount) public onlyOwner
The mint function allows the contract owner to mint new tokens and send them to a specified address. Only the contract owner can call this function. The to parameter specifies the address that will receive the newly minted tokens, and the amount parameter specifies the amount of tokens to mint and send to the to address.

Dependencies
The MyToken contract relies on the following dependencies:

OpenZeppelin Contracts: This is a library of secure and tested smart contracts for the Ethereum blockchain. In this case, we are using the ERC20 and Ownable contracts.
License
This code is released under the MIT License.






