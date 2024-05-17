---
description: Provides validation functions for a k-of-n ownership scheme
---

# Multisig Plugin

**Multisig validation only works in the user operation context.**

{% embed url="https://github.com/alchemyplatform/multisig-plugin" %}

## Core features

1. Multisig user operation validation on native account functions (`installPlugin`, `uninstallPlugin`, `execute`, `executeBatch`, `upgradeToAndCall`).
2. An execution function that modifies account ownership by adding or removing owners, and/or modifies the threshold. This is guarded by the above validation function.
3. Support for ERC-1271 smart contract signatures based on the same multisig scheme.
4. Variable gas feature that allows for more flexibility and control over gas spent.

## Authors

{% embed url="https://github.com/howydev" %}

{% embed url="https://github.com/adamegyed" %}

{% embed url="https://github.com/jaypaik" %}

{% embed url="https://github.com/Dan-Nolan" %}
