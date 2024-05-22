---
description: Upgrade functionality for ERC-6900 smart contract accounts.
---

# Plugins

## What are ERC-6900 plugins?

Plugins are smart contract interfaces that allow for composable logic within smart contract accounts.

Many new features of accounts can be built by customizing the logic that goes into the validation and execution steps. Examples of such features include session keys, subscriptions, spending limits, and role-based access control.

6900 proposes a standard that coordinates the implementation work between plugin developers and wallet developers. This standard defines a modular smart contract account capable of supporting all standard-conformant plugins. This allows users to have greater portability of their data, and for plugin developers to not have to choose specific account implementations to support.

## Compatible Accounts

There are various implementations for ERC-6900 including:

* [Modular Account](./#modular-account)
* [Upgradable Modular Smart Contract Account](./#upgradable-modular-smart-contract-account-factory)
* [SingleOwner Modular Smart Contract Account](./#singleowner-semi-modular-smart-contract-account-factory)

***

### Modular Account

A maximally modular, upgradeable smart contract account that is compatible with [ERC-4337](https://eips.ethereum.org/EIPS/eip-4337) and [ERC-6900](https://eips.ethereum.org/EIPS/eip-6900).

_Built by_ [_Alchemy_](https://www.alchemy.com)_._

{% embed url="https://github.com/alchemyplatform/modular-account" %}

#### Contract address:

Add address

***

### Upgradable Modular Smart Contract Account Factory

_Built by_ [_Circle_](https://www.circle.com)_._

#### Contract address:

{% embed url="https://etherscan.io/address/0x3cbb0a4A8918A49C87b948C8C4517C6247E59dca" %}

***

### SingleOwner Semi-Modular Smart Contract Account Factory

_Built by_ [_Circle_](https://www.circle.com)_._

#### Contract address:

{% embed url="https://etherscan.io/address/0x1a1f5310eD7fF0B84Cef7E6d7D0f94Cc16D23013" %}

