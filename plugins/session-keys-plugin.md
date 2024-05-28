---
description: >-
  Session keys can be added to conduct various actions on behalf of the modular
  account under preset rules.
---

# Session Keys Plugin

**Session keys are used in user operation context only.**

{% embed url="https://github.com/alchemyplatform/modular-account/tree/develop/src/plugins/session" %}

## Core features

* Supports an expiry and time range rules that restrict session keys’ access to a specified time range.
* Supports external contract address limitations that limit what external contract addresses a session key is allowed to call. This restriction may be an allowlist, denylist, or neither.
* Supports external contract method limitations, which limit what external contract functions a session key is allowed to call.
* Support key rotation to update the key while keeping the permissions in place.
* Default permissions restrict everything, all access must be explicitly granted.
* Supports ERC-20 spend limits. These may be a total for the key, or refreshing on an interval (e.g. once per week).
* Supports ETH / native token spend limitations. These may be a total for the key, or refreshing on an interval.
* Supports gas spend limitations (total for a key, or refreshing on an interval).
* Supports ERC-721 permission through selector access limitations.
* Supports a required paymaster rule, where a session key may only be used to validate a user operation if a specific paymaster address is used. This is an alternative way to prevent session keys from spending your native token on gas than the gas limit.

## Author

[<picture><source srcset="../.gitbook/assets/alchemy-logo-white.png" media="(prefers-color-scheme: dark)"><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FImI9L0KXrv1O4bMTE21k%2Fuploads%2FzQq2looZUut1yU9kV9fD%2Falchemy-logo-blue-gradient.png?alt=media&#x26;token=5cbd91f0-eae0-4bc9-92ba-790016af4e75" alt="Alchemy Logo" data-size="line"></picture>](https://www.alchemy.com)
