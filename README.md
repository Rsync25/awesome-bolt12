
# Awesome BOLT12 ⚡ 🟣

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)


![image](https://github.com/Rsync25/awesome-bolt12/assets/135646455/1792378e-30b8-43ad-9543-b8889c70604d)


>A curated list of resources around BOLT12

**Contributions are welcome**


## About BOLT12

An "offer" has enough information for you to reach out and fetch a real invoice from the issuer, through the Lightning Network itself, just like it would send a payment: no web server needed. Your wallet then pays the actual invoice (or, if you scan an "invoice_request", your wallet sends an invoice which the vendor pays, as an ATM or refund would use).

This means that offers can be much smaller than invoices, and contain more information (currency, vendor name, quantity limits, blinded paths to reach the vendor).

### Potential Use Case

- Crowdfunding
- Privacy with payments
- Static QR
- Simple QR Code

## Resources

- [Website](https://bolt12.org/)
- [BOLT12 Support](https://bolt12.support/)
- [Telegram group](https://t.me/bolt12org)
- [PR with "Offer" option](https://github.com/lightning/bolts/pull/798)
- [bootstrap.bolt12.org: API Guide bitcoin version ](https://bootstrap.bolt12.org/)
- [Offer](https://bitcoinops.org/en/topics/offers/)
- [[Lightning-dev] Lightning Address in a Bolt 12 world](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-November/004204.html)
- [Lightning Address](https://gist.github.com/t-bast/78fd797a7da570d293a8663908d3339b)

## Articles

- [What Are Lightning Offers (BOLT 12) ?](https://thebitcoinmanual.com/articles/lightning-offers-bolt12/)
- [BOLT 12 AND LNURL: WHAT IS THE FUTURE FOR BITCOIN’S LIGHTNING NETWORK?](https://bitcoinmagazine.com/technical/bolt12-lnurl-and-bitcoin-lightning)
- [BOLT 12 – NATIVELY ENHANCING LIGHTNING’S USER EXPERIENCE](https://voltage.cloud/blog/lightning-network-faq/bolt-12-enhancing-lightning-networks-users-experience/)
- [How BOLT12 increases Lightning's privacy](https://www.litebit.eu/en/news/bolt12-lightning)
- [BOLT12 tread by LNCapital](https://twitter.com/TorqLN/status/1589321548133203968)
- [A pleb’s journal to running BOLT12 with CLN, PART 1](https://stacker.news/items/538702)
- [BOLT12 has arrived](https://lightningdevkit.org/blog/bolt12-has-arrived/)
- [The BOLT 12 Playground](https://strike.me/blog/bolt12-playground/)

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
- [Breez SDK](https://github.com/breez/breez-sdk) - The Breez SDK enables mobile developers to integrate Lightning and bitcoin payments into their apps with a very shallow learning curve. The use cases are endless – from social apps that want to integrate tipping between users to content-creation apps interested in adding bitcoin monetization (Planned)
- [Lightning Network Daemon (LND)](https://github.com/lightningnetwork/lnd) - The Lightning Network Daemon (lnd) - is a complete implementation of a Lightning Network node. lnd has several pluggable back-end chain services including btcd (a full-node), bitcoind, and neutrino (a new experimental light client) (Planned)
- [BOLT12 PLayground by Strike](https://github.com/LN-Zap/bolt12-playground) - This Bolt 12 Playground provides a docker stack that comprises of bitcoind, LND, CLN, Eclair and LNDK. It connects everything together, initializes wallets, and creates channels between the nodes.
- [LDK Offer Parser Reproducer](https://github.com/LN-Zap/ldk-offer-parser-reproducer) -  Sample repository to reproduce ldk offer parser issues
- [LDK Node](https://github.com/lightningdevkit/ldk-node) - A ready-to-go node implementation built using LDK. 

### Wallet

- [Spark wallet](https://github.com/shesek/spark-wallet) - A minimalistic wallet GUI for c-lightning (Core Lightning), accessible over the web or through mobile and desktop apps
- [Phoenix](https://github.com/ACINQ/phoenix) - Phoenix is a self-custodial Bitcoin wallet using Lightning to send/receive payments
- [Lexe Wallet](https://lexe.app/) - 24/7 Lightning wallet for payments
- [Firebolt](https://github.com/AreaLayer/firebolt-react-native) -  Bitcoin and Lightning wallet with Nostr, Lightning Network, Bitcoin, Coinjoin and Payjoin (Planned)
- [Mutiny Wallet](https://www.mutinywallet.com/) - Non custodial Lightning wallet for browser (Planned)
- [Zeus](https://zeusln.com/) - ZEUS is an open-source, self-custodial Bitcoin wallet that gives you full control over how you make payments
- [Breez Mobile Wallet](https://breez.technology/mobile/) - The Breez mobile app is a favorite of Lightning wizards and rookies alike. With a non-custodial Lightning node running on your mobile device (Planned)
  
### Exchanges

- [Bitswap](https://github.com/Bitswap-BiFi) - AMM DEX over Lightning Network by RGB protocol (Planned)


### Projects

- [VLS (Validating Lightning Signer)](https://vls.tech/) - An open-source Rust library and reference implementation of software that separates a user's private keys from their Lightning node
- [CivKit](https://github.com/civkit/civkit-node) - An open-source P2P makertplace use Nostr and Lightning Network (Planned)
- [Ocean Mining](https://ocean.xyz/) - Mining Pool
- [BOLT12 design](https://bolt12.org/) - Design and guides to BOLT12
- [BIP-353](https://github.com/bitcoin/bips/pull/1551/files) - BIP for support BOLT12
- [ROYGBIV.GUIDE](https://www.roygbiv.guide/) - roygbiv.guide is a blog for those interested in Lightning Prisms based on BOLT12.
- [Clams](https://clams.tech/) - Visualize your Sats Flow
- [Twelve Cash](https://twelve.cash/) - A simple way to receive bitcoin


  
### Social Media

- [NIP-XXX](https://github.com/nostr-protocol/nips/blob/361c439b4860648dda06ff6e6c41dd11e58bb995/XXX.md) - This NIP defines a new event type to communicate trade orders between Nostr relays and clients.


## Contributors

<a align="center" href="https://github.com/Rsync25/awesome-bolt12/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Rsync25/awesome-bolt12" />
</a>

