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

## Author

[<picture><source srcset="../.gitbook/assets/alchemy-logo-white.png" media="(prefers-color-scheme: dark)"><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FImI9L0KXrv1O4bMTE21k%2Fuploads%2FzQq2looZUut1yU9kV9fD%2Falchemy-logo-blue-gradient.png?alt=media&#x26;token=5cbd91f0-eae0-4bc9-92ba-790016af4e75" alt="Alchemy Logo" data-size="line"></picture>](https://www.alchemy.com)
