# Tip Jar - Blockchain-Based Tipping System

## Introduction
Tip Jar is a decentralized tipping platform built on Ethereum, allowing users to send and receive tips securely via smart contracts. The project leverages MetaMask for seamless wallet integration, enabling quick transactions without intermediaries. 

## Features
- **Decentralized Tipping** - Users can tip others directly on the blockchain.
- **MetaMask Integration** - Connect wallet and make transactions effortlessly.
- **Smart Contract Security** - Ensures transparency and immutability of all transactions.
- **Live Transaction Updates** - Real-time tracking of received tips.
- **User-Friendly Interface** - Simple and intuitive design for easy usage.

## Prerequisites
To run this project, you need:
- MetaMask installed in your browser.
- Node.js and npm installed.
- Truffle or Hardhat for contract deployment.
- Ganache (for local blockchain testing) or a live Ethereum testnet.

## Smart Contract Deployment
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/tip-jar.git
   cd tip-jar
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Compile and deploy the contract (using Truffle or Hardhat):
   ```sh
   truffle migrate --network ropsten
   ```
   or
   ```sh
   npx hardhat run scripts/deploy.js --network ropsten
   ```
4. Copy the deployed contract address for front-end integration.

## Frontend Integration
1. Open `index.html` and update the contract address in the JavaScript file.
2. Run a local server:
   ```sh
   npm start
   ```
3. Open the application in your browser and connect MetaMask.


# Deploy Address 0xD7ACd2a9FD159E69Bb102A1ca21C9a3e3A5F771B


## Usage
1. **Connect Wallet** - Click on "Connect Wallet" to link MetaMask.
2. **Enter Tip Amount** - Specify the ETH amount you want to tip.
3. **Send Tip** - Confirm the transaction via MetaMask.
4. **View Received Tips** - Check your wallet for received transactions.

## Technologies Used
- Solidity (Smart Contracts)
- Web3.js (Blockchain Interaction)
- MetaMask (Wallet Integration)
- HTML, CSS, JavaScript (Frontend)
- Truffle/Hardhat (Smart Contract Deployment)

## License
This project is licensed under the MIT License.

## Contributors
- Your Name ([GitHub Profile](https://github.com/your-profile))

Feel free to fork and improve the project! 🚀
