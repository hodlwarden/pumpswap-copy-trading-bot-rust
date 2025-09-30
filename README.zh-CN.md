# 🚀🚀🚀 Solana 跟单交易机器人 (Rust) 🚀🚀🚀 

![Rust](https://img.shields.io/badge/Rust-1.70+-orange.svg)
![GitHub last commit](https://img.shields.io/github/last-commit/hodlwarden/solana-copy-trading-bot-rust)

**[English](README.md) | [中文](README.zh-CN.md)**

一个为 Solana DEX 构建的高性能跟单交易机器人，使用 Rust 编写，旨在自动镜像复制选定钱包或交易者的交易。
已实现 `0 区块` 跟单交易，正在优化以成为首位跟单者。

## 支持的去中心化交易所

- Pump.fun/Pump Swap 跟单交易
- Raydium(AMM/CPMM) 跟单交易
- Meteora(DBC/DYN/DAMM) 跟单交易
- Jupiter 跟单交易

## 跟单交易示例交易

目标交易 - https://solscan.io/tx/5As2XB89ZH4VG4Rir88JcJt3ViY1rRCEoEqr2d4bVpWL31fcGFLiR1RfgyqpJGLfX5YTmPEWqmU4vKAatSGcZf2a

跟单交易 - https://solscan.io/tx/2cCJ3VEymoMgmKNC86LDzx3ywP2PeqkyBgwg7ZXiUP2zympQksqhKoeH82FRqTVPv7w62pdGvTt2amHPLt39orkq

目标交易 - https://solscan.io/tx/4SfnqzpMh539696wGLC1doFa1kMUqMt9ssptfCfQVFEv6WcAihZYpuxkuxK1VEgxZE2fmMSKtV8wka8Ce5prdxpQ

跟单交易 - https://solscan.io/tx/291NcWEyLsTvxvcLYC98iEWnCDNeCsebywqeEQopAFHVe1GiT3MMx2nPibedU6VbKJ5h1QTh8HTP3hoiuyjshMMC

## 功能特性

- 🚀 从目标地址实时镜像交易
- ⚡ 基于 Rust 的低延迟执行
- 🔒 安全的私钥管理
- 📊 可配置的交易参数（滑点、Gas 费用等）
- 📈 多钱包支持
- 🔄 自动化代币授权
- 📝 交易日志记录

## 环境要求

- Rust 1.70 或更高版本
- Solana CLI（如需与 Solana 区块链交互）
- Node.js（用于可选的前端组件）

## 安装说明

1. 克隆仓库：
   ```bash
   git clone https://github.com/hodlwarden/solana-copy-trading-bot-rust.git
   cd solana-copy-trading-bot-rust
2. 完成 .env 配置
   将 .env.example 重命名为 .env 并填写所有配置项。
   ```bash
   PRIVATE_KEY= # 你的钱包私钥
   RPC_HTTP=https://solana-rpc.publicnode.com #你的 yellowstone rpc api-key
   RPC_WSS=wss://solana-rpc.publicnode.com #你的 yellowstone wss api-key
   YELLOWSTONE_GRPC_HTTP=https://solana-yellowstone-grpc.publicnode.com:443 #你的 yellowstone grpc api-key
   SLIPPAGE=10
   JITO_BLOCK_ENGINE_URL=https://ny.mainnet.block-engine.jito.wtf
   JITO_TIP_VALUE=0.0001

4. 安装 cargo 包。
   ```bash
   cargo build
5. 运行
   ```bash
   cargo run

# 联系我
如果您有任何问题或合作意向，请随时联系我。随时欢迎！
Telegram - [@hodlwarden](https://t.me/hodlwarden)
