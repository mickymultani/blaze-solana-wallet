# Blaze - Solana Wallet Proof of Concept

Blaze is a proof-of-concept (POC) Solana wallet application designed to demonstrate the core functionality of a Solana wallet. It provides a simple and user-friendly interface for creating and managing Solana wallets, checking balances, and sending SOL tokens.

## Features

- **Create Wallets**: Blaze allows users to easily create new Solana wallets. It generates a secure mnemonic (seed phrase) that can be used to recover the wallet.

- **Manage Wallets**: Users can view a list of all their wallets, including their network (e.g., mainnet-beta) and balance.

- **Check Balances**: Blaze displays the balance of each wallet in SOL tokens. This information is retrieved from the Solana blockchain.

- **Send SOL Tokens**: Users can initiate transactions to send SOL tokens to other wallet addresses. The application validates the recipient's address and available balance before sending.

## Getting Started

To run Blaze locally, follow these steps:

```bash
# Clone this repository to your local machine:
git clone https://github.com/your-username/blaze-wallet.git
```

# Navigate to the project directory:
cd blaze-wallet

# Install project dependencies:
npm install

# Start the development server:
npm start
