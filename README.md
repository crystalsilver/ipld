<p align="center">
  <a href="https://ipld.io"><img src="./logo/ipld-logo.png"  width="150px"/></a>
</p>

# IPLD

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](http://ipn.io)
[![](https://img.shields.io/badge/project-ipld-blue.svg?style=flat-square)](http://github.com/ipld/ipld)
[![](https://img.shields.io/badge/freenode-%23ipfs-blue.svg?style=flat-square)](http://webchat.freenode.net/?channels=%23ipfs)

> InterPlanetary Linked Data

Read more about IPLD at https://ipld.io

_Note that, as in many IPFS repositories, most of the work is happening in [the issues](https://github.com/ipld/ipld/issues/) or in [active pull requests](https://github.com/ipld/ipld/pulls/). Go take a look!_

### IPLD Definitions

There are a variety of systems that use merkle-tree and hash-chain inspired datastructures (e.g. git, bittorrent, IPFS, tahoe-lafs, sfsro). IPLD defines:

- merkle-links: the core unit of a merkle-graph
- merkle-dag: any graphs whose edges are merkle-links.
- merkle-paths: unix-style paths for traversing merkle-dags with named merkle-links
- IPLD Data Model: a flexible, JSON-based data model for representing merkle-dags.
- IPLD Serialized Formats: a set of formats in which IPLD objects can be represented, for example JSON, CBOR, CSON, YAML, Protobuf, XML, RDF, etc.
- IPLD Canonical Format: a deterministic description on a serialized format that ensures the same logical object is always serialized to the exact same sequence of bits. This is critical for merkle-linking, and all cryptographic applications.

In short: JSON documents with named merkle-links that can be traversed.

## Table of Contents

- [Repositories](#repositories)
  - [Specifications](#specifications)
  - [Implementations](#implementations)
    - [New implementations](#new-implementations)
  - [Other Tools](#other-tools)
  - [Meta repos](#meta-repos)
- [Lead](#lead)
- [Contribute](#contribute)
- [License](#license)

## Repositories

IPLD is a multifaceted, distributed effort.

### Specifications

- [specs](https://github.com/ipld/specs) - The specifications for IPLD
- [cid](https://github.com/ipld/cid) - Self-describing content-addressed identifiers for distributed systems

### Implementations

IPLD has multiple types of implementations, some of which have been written in multiple languages.

#### Data format descriptions

- [js-ipld-dag-cbor](https://github.com/ipld/js-ipld-dag-cbor) - JavaScript implementation of the IPLD spec.
- [js-ipld-dag-pb](https://github.com/ipld/js-ipld-dag-pb) - JavaScript Implementation of the MerkleDAG Nodes with Protobuf.
- [js-ipld-eth-block](https://github.com/ipld/js-ipld-eth-block) - JavaScript Implementation of the IPLD format - Ethereum Block
- [go-ipld-btc](https://github.com/ipfs/go-ipld-btc)
- [go-ipld-zcash](https://github.com/ipfs/go-ipld-zcash)
- [go-ipld-cbor](https://github.com/ipfs/go-ipld-cbor)
- [go-ipld-git](https://github.com/ipfs/go-ipld-git)
- [go-ipld-node](https://github.com/ipfs/go-ipld-node)

#### Interface definitions

- [interface-ipld-format](https://github.com/ipld/interface-ipld-format) - A interface you can follow to implement a valid IPLD format, resolvable through the IPLD Resolver (available in IPFS)

#### Path Resolution

- [js-ipld-resolver](https://github.com/ipld/js-ipld-resolver) - JavaScript implementation of the IPLDService

#### Other repositories

- [**Go:** ipfs/go-ipld](https://github.com/ipfs/go-ipld) - The Go implementation of IPLD (deprecated).

<!-- - [**C:** kenCode-de/c-ipld](https://github.com/kenCode-de/c-ipld) - Implementation of the IPLD spec in C. (Warning: not from core team) -->

#### New implementations

Are you working on your own implementation in another language? [Open an issue](https://github.com/ipld/ipld/issues) in this repository to discuss it with others, find help, and coordinate efforts. Eventually, we can move it to the organization if you like, add it above, and mention it on the website.

### Other Tools

- [js-ipld-cli](https://github.com/ipld/js-ipld-cli) - Interact with IPLD on the command line

### Meta repos

- [ipld](https://github.com/ipld/ipld) - This repo, which is now self-describing.
- [website](https://github.com/ipld/website) - The official website for IPLD, at ipld.io

## Lead

- [Nicola Greco](https://github.com/nicola)

## Contribute

Please contribute! [Look at the issues](https://github.com/ipld/ipld/issues)!

Check out our [contributing document](contributing.md) for more information on how we work, and about contributing in general. Please be aware that all interactions related to IPLD are subject to the IPFS [Code of Conduct](https://github.com/ipfs/community/blob/master/code-of-conduct.md).

Small note: If editing the README, please conform to the [standard-readme](https://github.com/RichardLitt/standard-readme) specification.

## License

This repository is mainly documents. All of these are licensed under a [CC-BY-SA 3.0](https://ipfs.io/ipfs/QmVreNvKsQmQZ83T86cWSjPu2vR3yZHGPm5jnxFuunEB9u) license, © 2016 Protocol Labs Inc.
