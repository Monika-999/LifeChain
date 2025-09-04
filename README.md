# LifeChain – Organ Donation Platform Using Blockchain

LifeChain is a blockchain-based platform designed to bring **security, transparency, and trust** into the organ donation process. By leveraging **Ethereum blockchain, Solidity, and smart contracts**, LifeChain ensures tamper-proof donor and recipient records, prevents fraud, and automates donor–recipient matching.

---

## 🚀 Features
- **Secure Registration**: Donors and recipients are recorded on an immutable blockchain ledger.
- **Smart Contract Matching**: Automated donor–recipient matching based on medical criteria such as blood group and organ type.
- **Fraud Prevention**: Tamper-proof data eliminates duplicate entries and illegal manipulations.
- **Transparency & Trust**: Auditable transactions ensure fairness in allocation.
- **Simple Interface**: Easy-to-use frontend for registration and status tracking.

---

## 🛠️ Tech Stack
- **Blockchain & Smart Contracts**: Ethereum, Solidity, Ganache, Truffle/Hardhat
- **Frontend**: HTML, CSS, JavaScript (with Web3.js)
- **Backend (optional)**: Node.js, Express.js
- **Database (optional/off-chain storage)**: MongoDB
- **Tools**: MetaMask, VS Code, Git/GitHub

---

## 📌 Prototype Functionality
1. Donors and recipients register securely via the web interface.
2. Data is stored immutably on the Ethereum blockchain.
3. Smart contracts automatically verify compatibility and match donors to recipients.
4. Hospitals and regulators can audit all transactions in real time.
5. The system ensures **fair, secure, and bias-free organ allocation**.

---

## 👥 Intended Users
- **Donors**: Individuals willing to donate organs.
- **Recipients**: Patients in need of transplants.
- **Hospitals & Medical Authorities**: For verification and allocation.
- **Regulatory Bodies**: To ensure compliance and ethical practices.

---

## 🌍 Impact
LifeChain addresses critical issues in organ donation such as fraud, illegal trading, and lack of transparency. By ensuring fairness, security, and trust, the platform has the potential to **save more lives, build public confidence, and encourage more people to become donors.**

---

## 📂 Project Setup
### Prerequisites
- [Node.js](https://nodejs.org/)
- [Truffle](https://trufflesuite.com/)
- [Ganache](https://trufflesuite.com/ganache/)
- [MetaMask](https://metamask.io/)

### Steps
```bash
# Clone the repository
git clone https://github.com/your-username/LifeChain.git

# Navigate to project folder
cd LifeChain

# Install dependencies
npm install

# Compile smart contracts
truffle compile

# Deploy contracts
truffle migrate --network development
