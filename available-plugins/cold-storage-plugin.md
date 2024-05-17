---
description: >-
  Secure valuable NFTs within your Modular Smart Contract Account with custom
  virtual cold storage.
---

# Cold Storage Plugin

{% embed url="https://github.com/alchemyplatform/aa-virtual-cold-storage" %}

## Core features

1. Installing the Cold Storage Plugin
   * The owner specifies a highly secure storage key when installing the plugin
2. Locking an NFT
   * The owner can lock NFTs (all ERC721s, collections, or tokens) and place them in cold storage
3. Transferring NFT as the Owner
   * Transferring a locked NFT is blocked
   * Transferring a NFT that isn’t locked is fine
4. Transferring a Locked NFT with Storage Key
   * The storage key has permission to transfer locked NFTs
5. The storage key also has permissions to unlock NFTs and change the storage key
6. Uninstalling the Plugin
   * The plugin **blocks uninstalls** when there locked NFTs

## Authors

{% embed url="https://github.com/dphilipson" %}

{% embed url="https://github.com/alex-miao" %}

{% embed url="https://github.com/denniswon" %}
