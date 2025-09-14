---
layout: col-sidebar
title: OWASP Blockchain AppSec Standard
tags: blockchain cryptocurrency blockchain web3
level: 2
type: documentation
pitch: We focus on security of in blockchain and web3 and share our knowledge on attack vectors and defense mechanisms. We strongly encourage your contribution to these topics and content.
---

**Audience** \- security or tech professionals with basic to intermediate networking and cryptography knowledge

**Out of scope for this exercise:** Smart contracts which are sufficiently covered by the [Smart Contract Security Verification Standard](https://owasp.org/www-project-smart-contract-security-verification-standard) project. We explain a little bit about it for completeness.

## What are Web3, Blockchain and Smart Contracts?

**Blockchain** \- is a cryptography based technology stack recording transactions in a trusted and transparent way. A block of transactions are chained together to form a ledger. The chain is distributed to multiple nodes (decentralized) and the majority consensus is sought to verify the block to become a part of the chain. If a transaction is agreed to be retroactively changed, all transactions after that will have to be changed as well, therefore it is not often that a transaction can get altered even with consensus, hence it is considered to be immutable.  
Chains can have one or more use cases, such as cryptocurrency, voting systems, supply chain tracking.

Using an elliptic curve algorithm, private and public key pairs are created (up to 256 pairs). As a user, private key is your secret key and each public key is a wallet. Each key pair can be used in a different chains, like ethereum, bitcoin or non-currency project/products named chains. Each chain has an immutable ledger that is viewable publicly but can only be changed with majority of user’s consensus.

**Mining** \- the chain creates a challenge of the next required block (a specific hash outcome) and miners use their compute power to try different salts in their hashing to reach this outcome. First miner to reach and gets proved by the chain gets rewarded.

**Web3** is a communication layer built on top of Internet Protocol. It utilises blockchain technology to run the next generation of the internet and envisioned to be decentralised (no single company or person owns it) and user-owned (users own their data and digital assets, often through tokens (e.g., NFTs).

### In short:  
* **Web3** is the vision of a decentralised internet.  
* **Blockchain** is the underlying technology that enables decentralisation.  
* **Smart Contracts** are the tools used to automate and enforce agreements on the blockchain.  
Further resources and more advanced topics for blockchain and web3 are at the [appendice](#advanced-topics-and-further-resources:).
