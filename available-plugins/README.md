---
description: Upgrade functionality for ERC-6900 smart contract accounts.
---

# Available Plugins

* [Session Keys](session-keys-plugin.md)
* [Multi-owner](multi-owner-plugin.md)
* [Cold Storage](cold-storage-plugin.md)
* [Multisig](multisig-plugin.md)

## What are ERC-6900 plugins?

Plugins are smart contract interfaces that allow for composable logic within smart contract accounts.

Many new features of accounts can be built by customizing the logic that goes into the validation and execution steps. Examples of such features include session keys, subscriptions, spending limits, and role-based access control.

6900 proposes a standard that coordinates the implementation work between plugin developers and wallet developers. This standard defines a modular smart contract account capable of supporting all standard-conformant plugins. This allows users to have greater portability of their data, and for plugin developers to not have to choose specific account implementations to support.

## Build new plugins

If you're interested in building new plugins, fill out [this short application](https://alchemyu.typeform.com/to/Sh3Errb3)[ ](https://docs.google.com/forms/d/e/1FAIpQLSdAMs8\_yizHlUrrpbbiOPEjHwQnIYmBoG9EG2piigUILPadxg/viewform)to enable 6900 ecosystem coordinators support you (with tools, guidance) and to make sure we avoid teams unintentionally working on duplicative plugins.

Feel free to hop in [telegram](https://t.me/modular\_account\_standards) with any questions.
