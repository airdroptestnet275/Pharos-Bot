# Pharos Auto Bot

**Pharos Auto Bot** is a robust, modular automation framework built in **Node.js** for interacting with the [Pharos Testnet](https://pharos.network). It handles day-to-day tasks like check-ins, faucet claims, social verifications, and on-chain operations with ease and precision.

Perfect for testers, point farmers, and developers who want to automate repetitive tasks securely and efficiently.

---

## Features

- **Multi-Account Support**  
  Process unlimited accounts in parallel using `wallet.json`

- **Proxy Integration**  
  Optional proxy support via `proxy.txt` for IP rotation and privacy.

- **Modular Architecture**  
  Clearly separated services and utilities for clean, scalable code.

- ## Task Automation  
  
1. **Account Management**:
   - Logs into accounts.
   - Performs account check-ins.
   - Checks account status.

2. **Faucet Claims**:
   - Claims PHRS tokens from the faucet.
   - Claims USDC tokens from the faucet.

3. **Token Swaps**:
   - Swaps PHRS to USDC.
   - Swaps PHRS to USDT.

4. **Liquidity Provision**:
   - Adds liquidity to PHRS-USDC pool.
   - Adds liquidity to PHRS-USDT pool.

5. **Random Transfers**:
   - Executes random token transfers.

6. **Social Tasks**:
   - Performs social-related tasks (details not specified).

7. **NFT Minting**:
   - Mints Gotchipus NFTs.

8. **OpenFi Operations**:
   - Executes OpenFi-related tasks (details not specified).

9. **Pharos Deployment**:
   - Deploys Pharos (details not specified).

10. **Auto All**:
    - Runs all tasks automatically in a batch.

11. **Transaction Count Configuration**:
    - Allows setting the number of transactions to perform (default: 5).

12. **Exit**:
    - Terminates the bot.
    - 

- **Multi-Threaded Execution**  
  Efficient task handling using asynchronous JavaScript threading.

- **Configurable Settings**  
  Modify task preferences, delays, threads, and API keys via `config.js`.

- **Cross-Platform Compatibility**  
  Supports Windows, macOS, and Linux (Termux-friendly too).

---

## File Structure

```bash
Pharos-Auto-Bot/
pharos_bot/
├── index5.js          # Main script with console-based UI and menu
├── service.js         # Core logic for tasks, including Unlimited Faucet
├── chains             # Configuration for Pharos testnet and utilities
├── wallet.json        # Wallet storage for other tasks
├── wallet.txt         # Main wallet address for transfers
├── address.txt        # Generated wallet private keys
├── package.json       # Node.js project configuration
├── node_modules/      # Installed dependencies
└── README.md          # Project documentation
```
## ⚙️ Requirements

Before using the bot, make sure you have:

- [Node.js](https://nodejs.org/) v16+
- Git installed
- A valid Pharos Testnet account → [pharos.network](https://pharos.network/)
- Optional: Proxy list for stealth mode
- Terminal confidence (a little hacker energy helps)

---

## 🧠 Installation & Setup

```bash
# 1. Clone the repo
git clone https://github.com/airdroptestnet275/Pharos-Bot.git
cd Pharos-Bot
```
# 2. Install dependencies
```
npm install
```
# 3. Configure your settings
```
nano wallet.jsom 
```
# or use any code editor

# Put Your `wallet` Adddress in `wallet.txt`
```
nano wallet.txt
```

# 4. Run the bot
```
node main.js
```
---


---

## 🧾 License

This project is licensed under the **MIT License**.
