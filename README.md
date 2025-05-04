# DApp Token Sale ICO

A decentralized application (DApp) for conducting an Initial Coin Offering (ICO) token sale on the Ethereum blockchain. This project implements a custom ERC-20 token called DappToken and a smart contract to manage its sale.

## Features

- Custom ERC-20 token implementation (DappToken)
- Token sale smart contract with admin controls
- Web interface for token purchase
- Configurable token price
- Admin dashboard for sale management

## Technology Stack

- Solidity (Smart Contracts)
- Truffle Framework
- Web3.js
- Node.js
- Lite Server (Development)

## Prerequisites

- Node.js (v10.x or later)
- Truffle Framework
- Ganache (for local blockchain)
- MetaMask browser extension

## Installation

1. Clone the repository:
```bash
git clone <your-repository-url>
cd dapp-token-sale
```

2. Install dependencies:
```bash
npm install
```

3. Start Ganache and ensure it's running on port 7545

4. Compile and migrate the smart contracts:
```bash
truffle compile
truffle migrate --reset
```

5. Start the development server:
```bash
npm run dev
```

## Smart Contracts

The project contains three main smart contracts:

1. `DappToken.sol` - The ERC-20 token implementation
2. `DappTokenSale.sol` - Manages the token sale process
3. `Migrations.sol` - Handles contract migrations

## Usage

1. Connect MetaMask to your local Ganache network
2. Visit the DApp in your browser (usually at http://localhost:3000)
3. Use MetaMask to interact with the token sale
4. Admin can:
   - Set token price
   - End the token sale
   - Manage token distribution

## Testing

Run the test suite:
```bash
truffle test
```

## Deployment

To deploy to a live network:

1. Update `truffle-config.js` with your network settings
2. Run migrations:
```bash
truffle migrate --network <network-name>
```
3. Deploy frontend:
```bash
./deployfrontend.sh
```

## License

ISC

## Author

Gregory 