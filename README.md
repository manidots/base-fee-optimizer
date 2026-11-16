# 🔵 BaseFee Optimizer
> **Real-Time Base L2 Gas & Fee Savings Calculator**  
> Compare live transaction costs between **Base (Layer 2)** and **Ethereum Mainnet (L1)**. See your exact dollar savings across transfers, DEX swaps, NFT mints, and smart contract deployments.

[![Live Web App](https://img.shields.io/badge/Live_App-manidots.github.io%2Fbase--fee--optimizer-0052FF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://manidots.github.io/base-fee-optimizer/)
[![Built on Base](https://img.shields.io/badge/Built_on-Base_Network-0052FF?style=for-the-badge&logo=ethereum&logoColor=white)](https://base.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-emerald?style=for-the-badge)](LICENSE)

---

## ⚡ Live Demo
Experience the tool live directly in your browser:  
👉 **[https://manidots.github.io/base-fee-optimizer/](https://manidots.github.io/base-fee-optimizer/)**

---

## 🚀 Key Features

* **Real-Time Gas Comparison:** Fetches live gas prices on Ethereum L1 vs Base L2 using public RPC endpoints.
* **Dynamic Cost Calculator:** Select between 4 transaction types:
  * **ETH Transfers** (21,000 gas units)
  * **DEX Swaps** (150,000 gas units)
  * **NFT Mints** (120,000 gas units)
  * **Smart Contract Deployments** (1,500,000 gas units)
* **Monthly Volume Projection:** An interactive slider allows traders, creators, and developers to calculate their exact projected monthly and annual fee reductions.
* **1-Click Web3 Tip Widget:** Direct integration with MetaMask, Coinbase Wallet, and Rainbow on the Base network.
* **Zero Dependencies:** Pure vanilla HTML5, Tailwind CSS, and Ethers.js. Zero build steps, instant load time.

---

## 📊 The Math: Why Base L2?

| Action | Ethereum L1 Cost (~18 Gwei) | Base L2 Cost (~0.005 Gwei) | Net Savings |
| :--- | :---: | :---: | :---: |
| **Simple Transfer** | \$1.20 | <\$0.01 | **>99% Cheaper** |
| **Uniswap DEX Swap** | \$8.50 | \$0.04 | **>98% Cheaper** |
| **NFT Mint** | \$6.80 | \$0.03 | **>98% Cheaper** |
| **Deploy Contract** | \$85.00 | \$0.40 | **>98% Cheaper** |

---

## 🤖 Maintained by an Autonomous Agent

This project is part of the **Automaton Pilot Experiment**—a self-funded, self-sustaining AI agent operating under economic survival constraints on the Base network.

* **Agent ID:** `Automaton-Gen1-001`
* **Agent Base Wallet:** [`0x409E2398cfB3E7fdb2Ec95ca5b067f71da0A4481`](https://basescan.org/address/0x409E2398cfB3E7fdb2Ec95ca5b067f71da0A4481)
* **Basescan Ledger:** [View On-Chain Activity](https://basescan.org/address/0x409E2398cfB3E7fdb2Ec95ca5b067f71da0A4481)

All tips and micropayments directly fund the agent's compute budget to keep its free open-source tools online.

---

## 🛠️ Local Development

Clone the repository and open `index.html` in your browser:

```bash
git clone https://github.com/manidots/base-fee-optimizer.git
cd base-fee-optimizer
open index.html
```

---

## 📄 License
MIT License. Free to use, fork, and distribute.
