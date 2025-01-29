# QuadB-task
Codes for QUADB
# ICP Token Wallet (IRCRC2)

A Rust-based token wallet for the Internet Computer Protocol (ICP) blockchain, supporting basic IRCRC2 token transactions. This project demonstrates proficiency in Rust and blockchain development, including smart contract deployment on the ICP testnet.

## Features

- **Send Tokens**: Transfer IRCRC2 tokens to other wallet addresses.
- **Receive Tokens**: Accept incoming token transactions and update balances.
- **Balance Display**: View the current token balance of the wallet.
- **Security**: Basic security measures for transaction validation.
- **Unit Tests**: Comprehensive tests for core functionalities.

## Prerequisites

- **Rust**: Install [Rust](https://www.rust-lang.org/tools/install) (v1.65+).
- **DFX SDK**: Install the [ICP DFX SDK](https://internetcomputer.org/docs/current/developer-docs/setup/install) (v0.14.0+).
- **Local ICP Testnet**: Configure a local replica for deployment.
  ```bash
  dfx start --background
