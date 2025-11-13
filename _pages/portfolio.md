---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

Smart contract
======
#### CMTAT [Taurus SA / Solidity]

> Security token framework to tokenize financial instruments on Ethereum and EVM compatible blockchain.

- Project: CMTAT [Solidity]
- Role: Smart Contract Developer
- Duration: 2022 &mdash; Present
- [GitHub project](https://github.com/CMTA/CMTAT)

**Skills:** Solidity · EVM · Ethereum

#### Chainlink CCIP Sender [Taurus SA / Solidity]

> Study of the CCIP cross-chain bridge by Chainlink with the transfer of USDC between different blockchains as proof-of-concept

- Role: Smart Contract Developer
- Duration: 12/2023 &mdash; 05/2024
- [Github project](https://github.com/taurushq-io/tg-bridge-contracts-CCIP)
- Two articles were published on the Taurus blog, as well as a github project (Sender contract to interact with CCIP).

**Skills:** Solidity · CCIP · Chainlink · cross-chain bridge · Stablecoin

#### IncomeVault [Taurus SA / Solidity]

> IncomeVault to distribute dividend on-chain, build with CMTAT

- Role: Smart Contract Developer
- Duration: 12/2023 &mdash; 05/2024
- [Github project](https://github.com/CMTA/IncomeVault)
- Publish a blog post on Taurus blog describing the architecture: <a href="https://www.taurushq.com/blog/equity-tokenization-how-to-pay-dividend-on-chain-using-cmtat/">Equity Tokenization - How to Pay Dividend On-Chain Using CMTAT</a>

**Skills:** Solidity · Smart Contracts · defi · Foundry · Stablecoin

## Rust

### Password manager [HEIG-VD]

[GitHub](https://github.com/rya-sge/password-manager)

A password manager to store password securely.

When a user creates an account on the application, an `RSA` key pair is generated. 

- The private key is encrypted using a key derived from the user's master password, and a hash of the master password is stored in `accounts.db`. 
- Passwords added by the user are encrypted with their RSA public key and stored in `passwords.db`. 
- To share a password with another user, the sender uses the recipient’s public key for encryption.

**Skills:** cryptography security
