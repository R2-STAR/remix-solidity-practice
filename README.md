# Solidity Smart Contract

Here we build our own Solidity contract to accept payments from a user. The project contains
 - A simple contract that accepts payments. It emits events anytime a user makes a payment
 - The user can connect their wallet and make a payment. Once the payment is made, the user is given access to the course
 - A centralized backend that watches the contract, and anytime a payment is made, it gives the user access to the course
   
Future enhancements
 - There is a problem with our backend, it can go down, and when it does it might miss events from the contract. Fix this.
 - A frontend so that user can interact and connect their wallet.

## Network
- Sepolia Testnet

## Tools
- Remix IDE
- MetaMask

## License
MIT
