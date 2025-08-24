# BSC Testnet Faucet

A simple BSC testnet faucet that allows developers to claim free BNB tokens for testing purposes on the Binance Smart Chain testnet.

## ⚙️ Project Overview

* Built using **Next.js** and **ethers.js**
* Connect wallets via **Web3Modal** with support for **WalletConnect**
* Provides 0.01 BNB per claim, limited to one claim per hour
* Displays user wallet address, balance, faucet contract balance, and number of times users have been funded
* Provides transaction feedback with loader and confirmation count

## 📁 Structure

* **Web3ModalBscFaucet** → Main React component handling wallet connection, faucet interactions, and UI.
* Integrated in the website `page.jsx` for direct access.
* Uses `style/faucetCss.css` for styling.

## 🛠 Features

* Connect wallet using MetaMask or WalletConnect
* Claim testnet BNB (0.01 BNB per hour)
* View current contract balance
* View the number of times people have been funded
* Transaction status updates with loader and confirmation display

## 💻 Setup

1. Clone the repository:

```bash
git clone https://github.com/granat207/BscTestnetFaucet-Frontend.git
cd BscTestnetFaucet-Frontend
```

2. Install dependencies:

```bash
yarn install
```

3. Add your **RPC URL** for BSC testnet in `providerOptions`.
4. Start the development server:

```bash
yarn dev
```

## 🧪 Usage

1. Open the web app in your browser.
2. Connect your wallet using MetaMask or WalletConnect.
3. Request 0.01 BNB from the faucet (once per hour).
4. Observe transaction confirmation and updated balances.

## 🔗 Notes

* Only works on **BSC Testnet**.
* Make sure to use the testnet network in your wallet.
* Backed by Daniel.eth (Twitter: [@0xDaniel\_eth](https://twitter.com/0xDaniel_eth))

## 📄 License

MIT License
