---
description: >-
  One or more EOA accounts, ERC-1271 compliant contracts, or P256 passkeys can
  be owners of an account.
---

# Webauthn Owner Plugin

{% embed url="https://github.com/exactly/webauthn-owner-plugin" %}

## Core Features

* Enable ECDSA verification of signatures, standard EOA signature verification.
* Enable ERC-1271 signature verification, standard contract owner signature verification.
* Enable Webauthn verification, secp256r1 (P256) passkey signatures verification.
* Multiple equal owners who have the same root access to account.
* Implements EIP-712.
* By default, owner validation is added for most of the account's native functions, including:
  * `installPlugin`/ `uninstallPlugin`
  * `upgradeToAndCall`
  * `execute` / `executeBatch`

## Author

[<img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FImI9L0KXrv1O4bMTE21k%2Fuploads%2FnSTewa6S36xgaoZKWxEr%2FExactly-logo-2.png?alt=media&#x26;token=339826d1-7f65-4a94-84fe-837dc5dc0cd8" alt="Exactly Logo" data-size="original">](https://exact.ly/)

{% embed url="https://github.com/cruzdanilo" %}
