<p align="center">
  <a href="https://ipld.io"><img src="./logo/ipld-logo.png"  width="150px"/></a>
</p>

# IPLD

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](https://protocol.ai)
[![](https://img.shields.io/badge/project-ipld-blue.svg?style=flat-square)](https://github.com/ipld/ipld)
[![](https://img.shields.io/badge/freenode-%23ipfs-blue.svg?style=flat-square)](https://webchat.freenode.net/?channels=%23ipfs)

> InterPlanetary Linked Data

Captain: [@nicola](https://github.com/nicola)


- [Overview](#overview)
- [New implementations](#new-implementations)
- [Contribute](#contribute)
- [License](#license)


## Overview

- Specs: [ipld/specs](https://github.com/ipld/specs)
- CID specs: [ipld/cid](https://github.com/ipld/cid)
- Website: [ipld/website](https://github.com/ipld/website)
- Tools
  - IPLD graph builder: [ipld/js-ipld-graph-builder](https://github.com/ipld/js-ipld-graph-builder)
  - CLI for interacting with IPLD: [ipld/js-ipld-cli](https://github.com/ipld/js-ipld-cli)
- New implementations
  - Are you working on your own implementation in another language?
  - [Open an issue](https://github.com/ipld/ipld/issues) in this repository to discuss it with others, find help, and coordinate efforts.
  - Eventually, we can move it to the organization if you like, add it above, and mention it on the website.


| Package | JavaScript | Go |
| ------- | ---------- | -- |
| CID | [ipld/js-cid](https://github.com/ipld/js-cid) | [ipfs/go-cid](https://github.com/ipfs/go-cid) |
| IPLD Node interface | [ipld/interface-ipld-format](https://github.com/ipld/interface-ipld-format) | [ipfs/go-ipld-format](https://github.com/ipfs/go-ipld-format) |
| IPLD Resolver | [ipld/js-ipld-resolver](https://github.com/ipld/js-ipld-resolver) | [ipfs/go-ipld-format#8](https://github.com/ipfs/go-ipld-format#8) |
| CBOR (default) | [ipld/js-ipld-dag-cbor](https://github.com/ipld/js-ipld-dag-cbor) | [ipfs/go-ipld-cbor](https://github.com/ipfs/go-ipld-cbor) |
| Merkledag/Protobuf (legacy) | [ipld/js-ipld-dag-pb](https://github.com/ipld/js-ipld-dag-pb) | [ipfs/go-ipld-format#8](https://github.com/ipfs/go-ipld-format#8) |
| Raw | [ipld/js-ipld-raw](https://github.com/ipld/js-ipld-raw) | [ipfs/go-ipld-format#8](https://github.com/ipfs/go-ipld-format#8) |
| Git | | [ipfs/go-ipld-git](https://github.com/ipfs/go-ipld-git) |
| Bitcoin | | [ipfs/go-ipld-btc](https://github.com/ipfs/go-ipld-btc) |
| Zcash | | [ipfs/go-ipld-zcash](https://github.com/ipfs/go-ipld-zcash) |
| Ethereum | [ipld/js-ipld-ethereum](https://github.com/ipld/js-ipld-ethereum) | [ipfs/go-ipld-eth](https://github.com/ipfs/go-ipld-eth) |
| Bencode | [ipld/js-ipld-bencode](https://github.com/ipld/js-ipld-bencode) | |
| Torrent info | [ipld/js-ipld-torrent-info](https://github.com/ipld/js-ipld-torrent-info) | |
| Torrent file | [ipld/js-ipld-torrent-file](https://github.com/ipld/js-ipld-torrent-file) | |
| IPLD Selectors (experimental) | [ipld/js-ipld-selector](https://github.com/ipld/js-ipld-selector) | |


## Contribute

Please contribute! [Look at the issues](https://github.com/ipld/ipld/issues)!

Check out our [contributing document](contributing.md) for more information on how we work, and about contributing in general. Please be aware that all interactions related to IPLD are subject to the IPFS [Code of Conduct](https://github.com/ipfs/community/blob/master/code-of-conduct.md).

Small note: If editing the README, please conform to the [standard-readme](https://github.com/RichardLitt/standard-readme) specification.


## License

This repository is mainly documents. All of these are licensed under a [CC-BY-SA 3.0](https://ipfs.io/ipfs/QmVreNvKsQmQZ83T86cWSjPu2vR3yZHGPm5jnxFuunEB9u) license, © 2016 Protocol Labs Inc.
