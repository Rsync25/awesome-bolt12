
# Awesome BOLT12 ⚡🟣

A curated list of resources around BOLT12

## About BOLT12

An "offer" has enough information for you to reach out and fetch a real invoice from the issuer, through the Lightning Network itself, just like it would send a payment: no web server needed. Your wallet then pays the actual invoice (or, if you scan an "invoice_request", your wallet sends an invoice which the vendor pays, as an ATM or refund would use).

This means that offers can be much smaller than invoices, and contain more information (currency, vendor name, quantity limits, blinded paths to reach the vendor).

## Resources

- [Website](https://bolt12.org/)
- [Telegram group](https://t.me/bolt12org)
- [PR with "Offer" option](https://github.com/lightning/bolts/pull/798)
- [bootstrap.bolt12.org: API Guide bitcoin version ](https://bootstrap.bolt12.org/)
- [Offer](https://bitcoinops.org/en/topics/offers/)

## Articles

- [What Are Lightning Offers (BOLT 12) ?](https://thebitcoinmanual.com/articles/lightning-offers-bolt12/)
- [BOLT 12 AND LNURL: WHAT IS THE FUTURE FOR BITCOIN’S LIGHTNING NETWORK?](https://bitcoinmagazine.com/technical/bolt12-lnurl-and-bitcoin-lightning)
- [BOLT 12 – NATIVELY ENHANCING LIGHTNING’S USER EXPERIENCE](https://voltage.cloud/blog/lightning-network-faq/bolt-12-enhancing-lightning-networks-users-experience/)
- [How BOLT12 increases Lightning's privacy](https://www.litebit.eu/en/news/bolt12-lightning)
- [BOLT12 tread by LNCapital](https://twitter.com/TorqLN/status/1589321548133203968)


## Ecosystem

Ecosystem around BOLT12 implementation

### Lightning Implementations 

- [LNDK](https://github.com/lndk-org/lndk) - LNDK is a standalone daemon that connects to LND (via its grpc API) that aims to implement bolt 12 functionality externally to LND. LNDK leverages the lightning development kit to provide functionality, acting as a thin "shim" between LND's APIs and LDK's lightning library
- [Core Lightning](https://github.com/ElementsProject/lightning) - Lightning Network implementation focusing on spec compliance and performance
- [bolt12.dart](https://github.com/dart-lightning/lndart.bolt12) - A dart implementation of lightning network BOLT12
- [Rust-Lightning](https://github.com/lightningdevkit/rust-lightning) - LDK/rust-lightning is a highly performant and flexible implementation of the Lightning Network protocol
- [Eclair](https://github.com/ACINQ/eclair) - A scala implementation of the Lightning Network
- [Bolt 11](https://github.com/lnbits/bolt11) - Lightning BOLT11 implementation for Python
- [BOLT12 Address Support](https://github.com/rustyrussell/bolt12address) - BOLT12 Lightning Address Format
- [LDK Bindings for Garbage-Collected Languages](https://github.com/lightningdevkit/ldk-garbagecollected) - This repo contains an autogeneration system to generate LDK bindings for garbage-collected languages, currently including Java and TypeScript

### Wallet

- [Spark wallet](https://github.com/shesek/spark-wallet) - A minimalistic wallet GUI for c-lightning (Core Lightning), accessible over the web or through mobile and desktop apps
- [Phoenix](https://github.com/ACINQ/phoenix) - Phoenix is a self-custodial Bitcoin wallet using Lightning to send/receive payments
- [Lexe Wallet](https://lexe.app/) - 24/7 Lightning wallet for payments
- [Firebolt](https://github.com/AreaLayer/FireBolt) -  Bitcoin and Lightning wallet with Nostr, TBD, Hypercore, LN, Bitcoin, Coinjoin and Payjoin


### Projects

- [VLS (Validating Lightning Signer)](https://vls.tech/) - An open-source Rust library and reference implementation of software that separates a user's private keys from their Lightning node

### Social Media

- [NIP-XXX](https://github.com/nostr-protocol/nips/blob/361c439b4860648dda06ff6e6c41dd11e58bb995/XXX.md) - This NIP defines a new event type to communicate trade orders between Nostr relays and clients.




