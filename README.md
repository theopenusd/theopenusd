# OpUSD Smart Contract

This repository contains the FunC source code for the OpUSD smart contract, a decentralized stablecoin protocol supporting Elite Group (10,000 OpUSD + 2,000 OpShare) and DAO governance, as outlined in Whitepaper v2.16.

## Overview
- **Date**: April 23, 2025
- **Platform**: TON (The Open Network)
- **Language**: FunC
- **Features**:
  - Minting and burning OpUSD tokens
  - DAO governance with 5 wallets (3/5 multisig)
  - Elite Group management
  - Emergency pause, reserve distribution, oracle updates, and more

## Directory Structure
- `contracts/`: Core smart contract files
  - `OpUSD.fc`: Main contract logic
  - `initialization.fc`: Contract initialization
  - `signature.fc`: Signature verification
  - `token.fc`: Token minting and burning
  - `placeholders.fc`: Placeholder functions
- `docs/`: Documentation (e.g., Whitepaper v2.16)
- `scripts/`: Deployment scripts (optional)
- `tests/`: Test cases (optional)

## Setup
1. Install the FunC compiler and TON development tools.
2. Compile the contract using the FunC compiler.
3. Deploy to the TON blockchain using the provided deployment scripts.

## Notes
- The `check_single_signature` function is a placeholder and must be replaced with proper signature verification logic.
- Ensure compliance with Whitepaper v2.16 for full compatibility.
