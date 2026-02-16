# Simple Payment Contract 💰

A secure Solidity smart contract implementing payment functionality with deposit and withdrawal features.

![Solidity](https://img.shields.io/badge/Solidity-0.8.20-blue)
![Foundry](https://img.shields.io/badge/Foundry-tested-green)
![License](https://img.shields.io/badge/license-MIT-blue)

## 🎯 Features

✅ **Secure Deposits** - Users can deposit ETH into the contract  
✅ **Protected Withdrawals** - Balance checks prevent overdrafts  
✅ **Gas Optimized** - Efficient code to minimize transaction costs  
✅ **Event Logging** - All transactions emit events for tracking  
✅ **Comprehensive Testing** - Full test coverage with Foundry  

## 🛠️ Tech Stack

- **Solidity** ^0.8.20
- **Foundry** (Testing & Deployment)
- **OpenZeppelin** (Security standards)

## 📊 Test Results
```bash
Ran 2 test suites: 2 tests passed, 0 failed

| Function  | Min Gas | Avg Gas | Max Gas |
|-----------|---------|---------|---------|
| deposit   | 2,803   | 2,803   | 2,803   |
| withdraw  | 35,073  | 35,073  | 35,073  |
```

## 🚀 Getting Started

### Prerequisites
- [Foundry](https://book.getfoundry.sh/getting-started/installation)
- Git

### Installation
```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/simple-payment-contract.git

# Navigate to project
cd simple-payment-contract

# Install dependencies
forge install
```

### Running Tests
```bash
# Run all tests
forge test

# Run with gas report
forge test --gas-report

# Run specific test
forge test --match-path test/SimplePayment.t.sol
```

## 📝 Contract Overview

### Main Functions

**`deposit()`**
- Allows users to deposit ETH
- Emits `Deposit` event
- Updates user balance

**`withdraw(uint256 amount)`**
- Withdraws specified amount
- Checks sufficient balance
- Emits `Withdraw` event

**`balances(address user)`**
- Returns user's current balance

## 🔐 Security Considerations

✅ Reentrancy protection  
✅ Balance verification before withdrawal  
✅ Custom errors for gas efficiency  
✅ Event emission for transparency  

## 📍 Deployment

**Sepolia Testnet:**
- Contract Address: `Coming soon...`
- [View on Etherscan](https://sepolia.etherscan.io/)

## 🧪 Test Coverage

✅ Deposit functionality  
✅ Withdrawal with sufficient balance  
✅ Withdrawal failure with insufficient balance  
✅ Balance tracking accuracy  

## 🗺️ Roadmap

- [ ] Add multi-signature withdrawal
- [ ] Implement time-locked withdrawals
- [ ] Add ERC-20 token support
- [ ] Build frontend interface

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details

## 👤 Author

**Your Name**
- GitHub: [@jemimagaga8-hue](https://github.com/jemimagaga8-hue)
- Email: jemimagaga8@gmail.com
- Twitter: [@JemimaGaga92363](https://twitter.com/JemimaGaga92363)

---

⭐ **Star this repo if you found it helpful!**

💬 **Questions? Open an issue or reach out!**

🤝 **Contributions welcome!**
```
