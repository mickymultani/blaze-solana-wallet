# Blaze - Solana Wallet POC
Blaze is a proof-of-concept (POC) Solana wallet application designed to demonstrate the core functionality of a Solana wallet. It provides a simple and user-friendly interface for creating and managing Solana wallets, checking balances, and sending SOL tokens.

## Features

- **Create Wallets**: Blaze allows users to easily create new Solana wallets. It generates a secure mnemonic (seed phrase) that can be used to recover the wallet.

- **Manage Wallets**: Users can view a list of all their wallets, including their network (e.g., mainnet-beta) and balance.

- **Check Balances**: Blaze displays the balance of each wallet in SOL tokens. This information is retrieved from the Solana blockchain + QR code.

- **Send SOL Tokens**: Users can initiate transactions to send SOL tokens to other wallet addresses. The application validates the recipient's address and available balance before sending.

## Getting Started

To run Blaze locally, follow these steps:


# Clone this repository to your local machine:
```bash
git clone https://github.com/mickymult/blaze-wallet.git
```

# Navigate to the project directory:
```bash
cd blaze-wallet
```
# Install project dependencies:
```bash
npm install
```

# Start the development server:
```bash
npm start
```
Open your web browser and access the application at http://localhost:3000.

## Future Improvements

- Database for State Persistence: Implement a database (e.g., SQLite, MongoDB) to persist wallet data and transactions. This ensures that wallet information is not lost when the application is closed.

- Secure Key Management: Enhance wallet security by implementing a secure key management system, including hardware wallet support.

- Transaction History: Create a transaction history page that displays the details of past transactions, including transaction IDs and timestamps.

- Token Support: Add support for custom Solana tokens (SPL tokens) to allow users to manage various tokens within their wallets.

- User Authentication: Implement user authentication to protect wallet access and sensitive operations.

- QR Code Scanning: Allow users to scan QR codes for wallet addresses and transaction requests, making it easier to send and receive SOL tokens.

- Cross-Platform Compatibility: Develop mobile applications (iOS and Android) to expand the accessibility of Blaze.

- Testnet Integration: Provide support for Solana testnet to allow users to experiment with wallets and tokens without using real SOL.

## Contributing
Contributions to Blaze are welcome! If you have ideas for new features, improvements, or bug fixes, please open an issue or create a pull request. Follow our Contributing Guidelines for more details.

## License
This project is licensed under the MIT License.
