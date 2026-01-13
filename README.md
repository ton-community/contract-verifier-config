# Contract Verifier Config

Central configuration file for TON contract verification infrastructure.

## Usage

This configuration is consumed by various TON ecosystem tools:

### Compiler Versions

The following projects use this config to dynamically load available FunC, Tact, and Tolk compiler versions without requiring code updates:

- [ton-blockchain/verifier](https://github.com/ton-blockchain/verifier) — Web UI for contract verification
- [ton-community/contract-verifier-backend](https://github.com/ton-community/contract-verifier-backend) — Backend verification service

### Verification Endpoints

The following projects fetch backend endpoints for source code submission and verification:

- [ton-org/blueprint](https://github.com/ton-org/blueprint) — Development framework CLI (`npx blueprint verify`)
- [tact-lang/tact-deployer](https://github.com/tact-lang/tact-deployer) — Tact contract deployment tool
