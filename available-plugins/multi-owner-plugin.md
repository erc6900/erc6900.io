---
description: >-
  One or more EOA accounts or ERC-1271 compliant contracts can be owners of the
  Modular Smart Contract Account.
---

# Multi-owner Plugin

{% embed url="https://github.com/alchemyplatform/modular-account/tree/develop/src/plugins/owner" %}

## Core features

* Enable ECDSA verification of signatures, standard EOA signatures verification.
* Enable ERC-1271 signature verification, standard contract owner signatures verification.
* Multiple equal owners who have the same root access to account.
* Implements EIP-712.
* By default, owner validation is added for most of MSCA’s native functions including:
  * `installPlugin`/ `uninstallPlugin`
  * `upgradeToAndCall`
  * `execute` / `executeBatch`

## Authors

{% embed url="https://github.com/adamegyed" %}

{% embed url="https://github.com/jaypaik" %}

{% embed url="https://github.com/howydev" %}
