# Prediction Market DApp

A decentralized prediction market platform built on Ethereum where users can create, trade, and resolve prediction markets using META tokens. The platform implements automated market making for fair price discovery and provides an intuitive interface for market participation.

## Features

- **Decentralized Prediction Markets:** Create and participate in prediction markets for any future event
- **META Token Integration:** Native platform token with faucet functionality for easy onboarding
- **Automated Market Making:** Implements LMSR (Logarithmic Market Scoring Rule) for efficient price discovery
- **Real-Time Market Data:** Track market prices, trading volumes, and positions
- **Secure Smart Contracts:** Built with OpenZeppelin standards and comprehensive security measures
- **User-Friendly Interface:** Modern UI with real-time updates and interactive charts
- **Wallet Integration:** Seamless connection with MetaMask and other Web3 wallets

## Technologies Used

- **Frontend:** 
  - React.js 18
  - Vite
  - Tailwind CSS
  - Chart.js
  - Framer Motion
  - React Router DOM

- **Blockchain:** 
  - Ethers.js v6
  - Solidity ^0.8.19
  - OpenZeppelin Contracts
  - MetaMask Integration

## Smart Contracts

1. **META Token (0x49A2340a1ba96E38EFF65C8050c71A803063F0dd)**
   - ERC20 token for platform transactions
   - Built-in faucet (1000 META/24h)
   - Ownership controls and reentrancy protection

2. **Prediction Market (0xFd41283820D1B5E5795CF1C1f61aA41bF81d624E)**
   - Market creation and management
   - Trading functionality
   - Automated market making
   - Resolution mechanism

## Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/prediction-market.git
   ```

2. Navigate to project directory:
   ```bash
   cd prediction-market
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Set up environment variables:
   Create a `.env` file:
   ```env
   VITE_CONTRACT_ADDRESS=0xFd41283820D1B5E5795CF1C1f61aA41bF81d624E
   VITE_META_TOKEN_ADDRESS=0x49A2340a1ba96E38EFF65C8050c71A803063F0dd
   VITE_NETWORK_ID=11155111  # Sepolia testnet
   ```

5. Start development server:
   ```bash
   npm run dev
   ```

## How to Use

1. **Connect Wallet:**
   - Install MetaMask
   - Connect to the Sepolia testnet
   - Click "Connect Wallet" in the app

2. **Get META Tokens:**
   - Visit the faucet section
   - Request 1000 META tokens (available every 24 hours)

3. **Participate in Markets:**
   - Browse available prediction markets
   - Buy YES/NO shares using META tokens
   - Monitor your positions in real-time

4. **Create Markets:**
   - Click "Create Market"
   - Set market parameters and description
   - Submit transaction to create market

5. **Trading:**
   - Use the order interface to buy/sell shares
   - View price charts and market statistics
   - Monitor your trading history

## Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Security

- Smart contracts audited and built with OpenZeppelin standards
- Implements reentrancy protection
- Access control mechanisms
- Secure wallet integration

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions, feature requests, or bug reports, please open an issue in the GitHub repository.