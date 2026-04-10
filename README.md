#💊 Anti-Counterfeit Pharmachain

A blockchain-based system to prevent counterfeit drugs in the pharmaceutical supply chain using Ethereum smart contracts and decentralized verification.


## 📌 Project Overview

Counterfeit medicines are a serious global issue that leads to health risks and financial loss. This project introduces a secure and transparent system using blockchain technology to track and verify pharmaceutical products at every stage of the supply chain.
The system ensures that only genuine medicines reach consumers by providing tamper-proof tracking and real-time verification.

## 🚀 Features

* 🔗 Blockchain-based drug tracking
* 🧾 Smart contract for supply chain management
* 🔍 Drug authenticity verification
* 📦 Role-based workflow (Manufacturer, Distributor, Pharmacy)
* 🛡️ Tamper-proof data storage
* ⚡ Transparent and secure transactions



## 🏗️ System Architecture

The system consists of the following layers:

* **User Layer** – Interaction via web interface
* **Wallet Layer** – MetaMask for transaction signing
* **Network Layer** – Ethereum Blockchain
* **Smart Contract Layer** – Handles drug lifecycle
* **Storage Layer** – Blockchain ledger

---

## 🛠️ Tech Stack

* **Blockchain**: Ethereum
* **Smart Contracts**: Solidity
* **Local Blockchain**: Ganache
* **Frontend**: HTML, CSS, JavaScript
* **Wallet**: MetaMask

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/udhayaanandhi/Anti-counterfeit-Pharmachain.git
cd Anti-counterfeit-Pharmachain
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Start Ganache

* Open Ganache and run a local blockchain network

### 4️⃣ Compile Smart Contracts

```bash
truffle compile
```

### 5️⃣ Deploy Contracts

```bash
truffle migrate
```

### 6️⃣ Run the Application

```bash
npm run dev
```

---

## 🔑 Smart Contract Functions

* **manufactureDrug()** – Register a new drug
* **shipDrug()** – Transfer drug to distributor
* **receiveDrug()** – Confirm delivery
* **verifyDrug()** – Check authenticity
* **recallDrug()** – Mark drug as unsafe

---

## 🖥️ Usage

1. Connect MetaMask wallet
2. Register drug by manufacturer
3. Transfer drug through supply chain
4. Verify drug authenticity before purchase


## 🎯 Objectives

* Eliminate counterfeit drugs
* Improve supply chain transparency
* Ensure drug authenticity
* Build trust among stakeholders


## 📊 Future Enhancements

* QR code-based verification
* Integration with real-time pharmacy systems
* Mobile application support
* AI-based fraud detection

## 📜 License

This project is developed for academic purposes.
