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
- Reuse address

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
- [BOLT12: An Awesome Upgrade Coming For The Lightning Network (2024)](https://athenaalpha.substack.com/p/bolt12-an-awesome-upgrade-coming)
- [Stephan Livera - The Bolt12 age of Lightning](https://x.com/stephanlivera/status/1808573143012827227)
- [Why The Denial-Of-Service Argument Against BOLT 12 Doesn’t Hold Up](https://bitcoinmagazine.com/technical/dos-argument-against-bitcoin-bolt-12)
- [BOLT12 on the phoenix phoenixd ecosystem](https://massmux.org/p/bolt12-on-the-phoenix-phoenixd-ecosystem)
- [Lightning Network In A Class Of Its Own At Bitcoin 2024 Conference](https://www.nasdaq.com/articles/lightning-network-class-its-own-bitcoin-2024-conference)

## Videos

- [ LIGHTNING NETWORK CON GLI STEROIDI: BOLT12 E GLI INDIRIZZI RIUTILIZZABILI](https://www.youtube.com/watch?v=Et5m6HwaRC8)

## Ecosystem

Ecosystem around BOLT12 implementation

### Lightning Implementations 

- [LNDK](https://github.com/lndk-org/lndk) - LNDK is a standalone daemon that connects to LND (via its grpc API) that aims to implement bolt 12 functionality externally to LND. LNDK leverages the lightning development kit to provide functionality, acting as a thin "shim" between LND's APIs and LDK's lightning library
- [Core Lightning](https://github.com/ElementsProject/lightning) - Lightning Network implementation focusing on spec compliance and performance
- [bolt12.dart](https://github.com/dart-lightning/lndart.bolt12) - A dart implementation of lightning network BOLT12
- [Rust-Lightning](https://github.com/lightningdevkit/rust-lightning) - LDK/rust-lightning is a highly performant and flexible implementation of the Lightning Network protocol
- [Eclair](https://github.com/ACINQ/eclair) - A scala implementation of the Lightning Network
- [BOLT12 Address Support](https://github.com/rustyrussell/bolt12address) - BOLT12 Lightning Address Format
- [LDK Bindings for Garbage-Collected Languages](https://github.com/lightningdevkit/ldk-garbagecollected) - This repo contains an autogeneration system to generate LDK bindings for garbage-collected languages, currently including Java and TypeScript
- [Breez SDK](https://github.com/breez/breez-sdk) - The Breez SDK enables mobile developers to integrate Lightning and bitcoin payments into their apps with a very shallow learning curve. The use cases are endless – from social apps that want to integrate tipping between users to content-creation apps interested in adding bitcoin monetization (Planned)
- [Lightning Network Daemon (LND)](https://github.com/lightningnetwork/lnd) - The Lightning Network Daemon (lnd) - is a complete implementation of a Lightning Network node. lnd has several pluggable back-end chain services including btcd (a full-node), bitcoind, and neutrino (a new experimental light client) (Planned)
- [BOLT12 PLayground by Strike](https://github.com/LN-Zap/bolt12-playground) - This Bolt 12 Playground provides a docker stack that comprises of bitcoind, LND, CLN, Eclair and LNDK. It connects everything together, initializes wallets, and creates channels between the nodes.
- [LDK Offer Parser Reproducer](https://github.com/LN-Zap/ldk-offer-parser-reproducer) -  Sample repository to reproduce ldk offer parser issues
- [LDK Node](https://github.com/lightningdevkit/ldk-node) - A ready-to-go node implementation built using LDK.
- [Phoenixd](https://github.com/ACINQ/phoenixd/) - Phoenixd is the server equivalent of the popular phoenix wallet for mobile
- [Payto](https://github.com/urza/payto) - Core Lightning (CLN) companion app that can pay to lightning address, LNURL, BIP353 (DNS Payment Instructions) and bolt12 offers
- [Javascript DLC](https://github.com/AreaLayer/javascript-dlc) - Javascript library for working with Discreet Log Contracts and Lightning Network 

### Wallet

- [Spark wallet](https://github.com/shesek/spark-wallet) - A minimalistic wallet GUI for c-lightning (Core Lightning), accessible over the web or through mobile and desktop apps
- [Phoenix](https://github.com/ACINQ/phoenix) - Phoenix is a self-custodial Bitcoin wallet using Lightning to send/receive payments
- [Lexe Wallet](https://lexe.app/) - 24/7 Lightning wallet for payments
- [Firebolt](https://github.com/AreaLayer/firebolt-react-native) -  Bitcoin and Lightning wallet with Nostr, Lightning Network, Bitcoin, Coinjoin and Payjoin (Planned)
- [Mutiny Wallet](https://www.mutinywallet.com/) - Non custodial Lightning wallet for browser (Planned)
- [Zeus](https://zeusln.com/) - ZEUS is an open-source, self-custodial Bitcoin wallet that gives you full control over how you make payments
- [Breez Mobile Wallet](https://breez.technology/mobile/) - The Breez mobile app is a favorite of Lightning wizards and rookies alike. With a non-custodial Lightning node running on your mobile device (Planned)
- [Plasma](https://github.com/Fonta1n3/Plasma) -  Core Lightning Wallet powered by LNSocket
- [Alby](https://getalby.com/) - Your Bitcoin & Nostr companion for the web (Planned)
- [Zaprite](https://zaprite.com/) - Bitcoin payments made easy (Plannned)

### Exchanges

- [Boltz Exchange](https://boltz.exchange/) - Non-Custodial Bitcoin Bridge (Planned)


### Projects

- [VLS (Validating Lightning Signer)](https://vls.tech/) - An open-source Rust library and reference implementation of software that separates a user's private keys from their Lightning node
- [CivKit](https://github.com/civkit/civkit-node) - An open-source P2P makertplace use Nostr and Lightning Network (Planned)
- [Ocean Mining](https://ocean.xyz/) - Mining Pool
- [BOLT12 design](https://bolt12.org/) - Design and guides to BOLT12
- [BIP-353](https://github.com/bitcoin/bips/pull/1551/files) - BIP for support BOLT12
- [ROYGBIV.GUIDE](https://www.roygbiv.guide/) - roygbiv.guide is a blog for those interested in Lightning Prisms based on BOLT12.
- [Clams](https://clams.tech/) - Visualize your Sats Flow
- [Twelve Cash](https://twelve.cash/) - A simple way to receive bitcoin
- [Ride The Lightning](https://www.ridethelightning.info/) - Ride The Lightning a powerful tool to help manage your lightning node
- [Lampo](https://lampo.devcrew.cc/) - A fast and modular lightning network implementation for all usages, written in Rust. lampo (lightning in Italian) is a experimental implementation of a tiny lightning node
- [Bolt12 API](https://github.com/ATLBitLab/twelvecash) - API for BOLT12
- [Twelve Cash](https://twelve.cash/) - A simple way to share your bitcoin payment info with the world.
- [El Tor](https://bitbucket.org/eltordev/workspace/projects/ELTOR) - El Tor aims to enhance the Tor network with high-bandwidth capabilities, powered by the Bitcoin Lightning Network
- [Entropy](https://dplus.plus/offer) -  BIP-353 Offer Address
- [Sats To Me](https://satsto.me/) -  BIP 353 defines the way to use simple human-readable names for Bitcoin payments. 
- [Zaprite](https://zaprite.com/) - Bitcoin payments made easy (Planned)
  
### Social Media

- [NIP-XXX](https://github.com/nostr-protocol/nips/blob/361c439b4860648dda06ff6e6c41dd11e58bb995/XXX.md) - This NIP defines a new event type to communicate trade orders between Nostr relays and clients.


## Contributors

<a align="center" href="https://github.com/Rsync25/awesome-bolt12/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Rsync25/awesome-bolt12" />
</a>

