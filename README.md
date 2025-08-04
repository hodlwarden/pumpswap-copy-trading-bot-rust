# Bonkfun Copy Trading Bot (Rust)

![Rust](https://img.shields.io/badge/Rust-1.70+-orange.svg)
![GitHub last commit](https://img.shields.io/github/last-commit/hodlwarden/pumpswap-copy-trading-bot-rust)

A high-performance copy trading bot for PumpSwap built in Rust, designed to automatically mirror trades from selected wallets or traders.

## Features

- 🚀 Real-time trade mirroring from target addresses
- ⚡ Low-latency execution powered by Rust
- 🔒 Secure private key management
- 📊 Configurable trade parameters (slippage, gas fees, etc.)
- 📈 Multi-wallet support
- 🔄 Automated token approval
- 📝 Transaction logging

## Prerequisites

- Rust 1.70 or higher
- Solana CLI (if interacting with Solana blockchain)
- Node.js (for optional frontend components)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hodlwarden/bonkfun-copy-trading-bot-rust.git
   cd bonkfun-copy-trading-bot-rust
2. Complete config of .env
   Simply rename the .env.example to .env and fill all configs.
   ```bash
   PRIVATE_KEY= # your wallet priv_key
   RPC_HTTP=https://solana-rpc.publicnode.com #your yellowstone rpc api-key
   RPC_WSS=wss://solana-rpc.publicnode.com #your yellowstone wss api-key
   YELLOWSTONE_GRPC_HTTP=https://solana-yellowstone-grpc.publicnode.com:443 #your yellowstone grpc api-key
   SLIPPAGE=10
   JITO_BLOCK_ENGINE_URL=https://ny.mainnet.block-engine.jito.wtf
   JITO_TIP_VALUE=0.0001

4. Install cargo package.
   ```bash
   cargo build
5. Run
   ```bash
   cargo run

# Contact Me
If you have any question or collaboration offer, feel free to text me. You're always welcome
Telegram - [@hodlwarden](https://t.me/hodlwarden)
