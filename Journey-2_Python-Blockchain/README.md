# 🪙 Python Blockchain Project

## 📌 About This Project
This is a minimal blockchain implementation in **Python** demonstrating:
- Block structure & hashing
- Proof of Work (PoW) mining
- Transaction batching
- Blockchain validation

It’s part of my personal **Blockchain Learning Journey**, where I progressively build more complex blockchain-related tools while learning the theory behind them.

---

## 📖 Learning Journey — Stage 1
Before coding this, here’s what I learned so far:

### 1. 🌍 Blockchain Basics
- **Definition**: A decentralized, distributed ledger that records transactions across many computers securely.
- **Benefits**: Transparency, immutability, decentralization, and security.
- **Characteristics**:
  - Distributed ledger technology (DLT)
  - Consensus mechanisms
  - Cryptographic security
  - Tamper resistance

### 2. ⛓ Structure of a Blockchain
- Each block contains:
  - **Hash**: Unique cryptographic fingerprint of the block
  - **Previous block hash**: Linking blocks together
  - **Transactions / Data**
  - **Timestamp**
- **Genesis Block**: The first block in the chain.
- **UTXO Model**: Used in Bitcoin to track spendable transaction outputs.

### 3. 🛠 Bitcoin & Ethereum Differences
- **Bitcoin**: Focus on peer-to-peer digital cash system.
- **Ethereum**: Introduced **Smart Contracts** (programs stored & executed on the blockchain).
- **Solidity**: Language used to code Ethereum smart contracts.

---

## 🛠 Features in My Python Blockchain
- **Genesis block** creation at startup
- **Adjustable mining difficulty**
- **Pending transactions** stored until mined (batch size: 5)
- **Hashing** with `SHA-256`
- **Proof of Work** implemented in `proof_of_work.py`
- **Chain validation** to detect tampering

---

## 📂 File Structure
.
├── Block.py # Block structure & mining logic
├── Blockchain.py # Blockchain management
├── Transaction.py # Transaction model
├── proof_of_work.py # Proof of Work mining
├── main.py # Demo usage of the blockchain

yaml
Copier
Modifier

---

## 🚀 How to Run

### 1️⃣ Prerequisites
- Python 3.x installed

### 2️⃣ Run the demo
```bash
python main.py
Example Output
mathematica
Copier
Modifier
Mining block 1...
Block mined: 00000a3e...
Mining block 2...
Block mined: 000001bc...
Blockchain valid? True
Block(2, Mon Aug 11 15:32:10 2025, Block 2, [...], 000001bc...)
