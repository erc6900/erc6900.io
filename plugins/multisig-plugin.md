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

## Resources

* [Getting started with the Multisig Plugin](https://accountkit.alchemy.com/smart-accounts/modular-account/multisig-plugin/getting-started)
* [Multisig technical details](https://accountkit.alchemy.com/smart-accounts/modular-account/multisig-plugin/technical-details.html)

## Authors

[<picture><source srcset="../.gitbook/assets/alchemy-logo-white.png" media="(prefers-color-scheme: dark)"><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FImI9L0KXrv1O4bMTE21k%2Fuploads%2FzQq2looZUut1yU9kV9fD%2Falchemy-logo-blue-gradient.png?alt=media&#x26;token=5cbd91f0-eae0-4bc9-92ba-790016af4e75" alt="Alchemy Logo" data-size="line"></picture>](https://www.alchemy.com)     [<picture><source srcset="../.gitbook/assets/maple-logo-white.png" media="(prefers-color-scheme: dark)"><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FImI9L0KXrv1O4bMTE21k%2Fuploads%2FOECWP7YISgXk247n1Q4p%2Fmaple-finance-logo.webp?alt=media&#x26;token=d01a3eba-6638-49ec-9ea5-4151ca74b316" alt="Maple Finance Logo" data-size="line"></picture>](https://maple.finance)
