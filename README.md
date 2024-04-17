### Welcome to BitcoinKit

The BitcoinKit library is a Swift implementation of the Bitcoin protocol which support both BCH and BTC.

BitcoinKit allows maintaining a wallet, sending or receiving transactions without a full blockchain node.

Features
--------

- Encoding/decoding addresses: base58, Cashaddr, P2PKH, P2SH, WIF format.
- Transaction building blocks: inputs, outputs, scripts.
- EC keys and signatures.
- BIP32, BIP44 hierarchical deterministic wallets.
- BIP39 implementation.

Requirements
------------
- iOS 12.0+ / Mac OS X 10.11+ / tvOS 9.0+ / watchOS 2.0+
- Xcode 10.0+
- Swift 5.0+

Installation
------------

Simply add the following lines to dependencies of your Package.swift:

```swift
.package(url: "https://github.com/yenom/BitcoinKit.git", .upToNextMinor(from: "1.1.0"))
```

Note that following data types and features are currently not supported on Linux platform.  

* `Peer` and `PeerGroup`
* SQLite based BlockStore

License
-------

BitcoinKit is available under the MIT license. See the LICENSE file for more info.
<a href="https://opencollective.com/BitcoinKit/sponsor/8/website" target="_blank"><img src="https://opencollective.com/BitcoinKit/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/BitcoinKit/sponsor/9/website" target="_blank"><img src="https://opencollective.com/BitcoinKit/sponsor/9/avatar.svg"></a>


