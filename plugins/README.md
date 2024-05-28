---
description: Upgrade functionality for ERC-6900 smart contract accounts.
---

# Plugins

## What are ERC-6900 plugins?

Plugins are smart contract interfaces that allow for composable logic within smart contract accounts.

Many new features of accounts can be built by customizing the logic that goes into the validation and execution steps. Examples of such features include session keys, subscriptions, spending limits, and role-based access control.

6900 proposes a standard that coordinates the implementation work between plugin developers and wallet developers. This standard defines a modular smart contract account capable of supporting all standard-conformant plugins. This allows users to have greater portability of their data, and for plugin developers to not have to choose specific [account implementations](../compatible-accounts.md) to support.

