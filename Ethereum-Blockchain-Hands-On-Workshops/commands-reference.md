# Go Ethereum (Geth) – Commands Reference

## Introduction
This document provides a reference to selected Geth commands and command-line concepts discussed during the Ethereum hands-on workshop.

## 1. Check Geth Installation

```powershell
geth version
```

Purpose: Displays the installed Geth version and build information.

## 2. Development Mode

```powershell
geth --dev
```

Purpose: Starts Geth in development mode for local experimentation.

## 3. Check Git Installation

```powershell
git --version
```

Purpose: Checks whether Git is installed.

## 4. Understanding Node Data Directories

A data directory stores information associated with an Ethereum node.

Example directory structure:

```text
Ethereum/
    node1/
```

## 5. Ethereum Account Concepts

The workshop introduced the following account-related operations:

- Creating an account.
- Listing accounts.
- Understanding public addresses.
- Understanding private-key security.

## 6. Transaction Concepts

An Ethereum transaction generally involves:
- Sender
- Recipient
- Value
- Gas parameters
- Transaction data
- Signature

## 7. JavaScript Console Concepts

The presentation introduced JavaScript console expressions for understanding account information and transaction status.

Examples of concepts explored:
- Account listing.
- Balance queries.
- Transaction information.
- Transaction receipt inspection.

## Important Notes
- These examples are educational references based on the accompanying workshop material.
- Some commands and APIs in the original presentation may be outdated or unsupported in current Geth releases.
- Check the official Geth documentation before attempting any command.
- Use a local development environment or approved test network.
- Never expose private keys, passwords, or seed phrases.
- Do not expose a node's administrative APIs to public networks.

## Conclusion
This reference summarizes the command-line and transaction concepts introduced during the workshop and provides a starting point for further learning.