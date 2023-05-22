## Flow's Beginners Course Project
This project implements a basic Non-Fungible Token (NFT) system on the Flow blockchain using the Flow scripting language Cadence. It consists of three main contracts: NonFungibleToken.cdc, crypto-poops.cdc, and the transaction script deposite code. Here is a brief description of each file:

## NonFungibleToken.cdc
This contract defines the main interface for the Flow NFT standard.
It includes interfaces for NFT, Provider, Receiver, and Collection.
The contract provides functions for depositing, withdrawing, and accessing NFTs within a collection.
It also allows for creating an empty collection.
## crypto-poops.cdc
This contract extends the NonFungibleToken contract and implements the NFT functionality.
It defines the NFT resource with additional properties like name, favorite food, and lucky number.
It implements the functions required by the NonFungibleToken interface, such as deposit, withdraw, and collection management.
## deposite code
This transaction script is used to deposit a new NFT into a recipient's collection.
It retrieves the recipient's collection reference and the NFT minter reference.
It creates a new NFT using the minter and deposits it into the recipient's collection.
## script code
This script retrieves the first NFT from the specified account's collection.
It borrows the NFT reference from the collection using the borrowAuthNFT function.

Please refer to the individual contract and script files for more detailed information on their functionalities and usage.
