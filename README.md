<!--
parent:
  order: false
-->

<div align="center">
  <h1> Ernest-Chain (Based on EVMOS & COSMOS SDK) </h1>
</div>

<div align="center">
  <a href="https://github.com/evmos/evmos/releases/latest">
    <img alt="Version" src="https://img.shields.io/github/tag/tharsis/evmos.svg" />
  </a>
  <a href="https://github.com/evmos/evmos/blob/main/LICENSE">
    <img alt="License: Apache-2.0" src="https://img.shields.io/github/license/tharsis/evmos.svg" />
  </a>
  <a href="https://pkg.go.dev/github.com/evmos/evmos">
    <img alt="GoDoc" src="https://godoc.org/github.com/evmos/evmos?status.svg" />
  </a>
  <a href="https://goreportcard.com/report/github.com/evmos/evmos">
    <img alt="Go report card" src="https://goreportcard.com/badge/github.com/evmos/evmos"/>
  </a>
  <a href="https://bestpractices.coreinfrastructure.org/projects/5018">
    <img alt="Lines of code" src="https://img.shields.io/tokei/lines/github/tharsis/evmos">
  </a>
</div>
<div align="center">
  <a href="https://discord.gg/evmos">
    <img alt="Discord" src="https://img.shields.io/discord/809048090249134080.svg" />
  </a>
  <a href="https://github.com/evmos/evmos/actions?query=branch%3Amain+workflow%3ALint">
    <img alt="Lint Status" src="https://github.com/evmos/evmos/actions/workflows/lint.yml/badge.svg?branch=main" />
  </a>
  <a href="https://codecov.io/gh/tharsis/evmos">
    <img alt="Code Coverage" src="https://codecov.io/gh/tharsis/evmos/branch/main/graph/badge.svg" />
  </a>
  <a href="https://twitter.com/EvmosOrg">
    <img alt="Twitter Follow Evmos" src="https://img.shields.io/twitter/follow/EvmosOrg"/>
  </a>
</div>

## What is Ernest Chain

Ernest Chain is a scalable, high-throughput Proof-of-Stake blockchain that is fully compatible and interoperable with Ethereum. It's built using the [Cosmos SDK](https://github.com/cosmos/cosmos-sdk/) which runs on top of [Tendermint Core](https://github.com/tendermint/tendermint) consensus engine.

Ernest Chain is mainly used to support Ernest Network the first ever full web3 implementation.

Ernect Chain allows for running vanilla Ethereum as a Cosmos application-specific blockchain. This allows developers to have all the desired features of Ethereum, while at the same time, benefit from Tendermint’s PoS implementation. Also, because it is built on top of the Cosmos SDK, it will be able to exchange value with the rest of the Cosmos Ecosystem through the Inter Blockchain Communication Protocol (IBC).


**Note**: Requires [Go 1.19+](https://golang.org/dl/)

## Features

Here’s a glance at some of the key features of Ernest Chain:

   - Web3 and EVM compatibility
   - High throughput via [Tendermint Core](https://github.com/tendermint/tendermint)
   - Horizontal scalability via [IBC](https://cosmos.network/ibc)
   - Fast transaction finality
   
Point Chain enables these key features by:

   - Being the blockchain layer for [Ernest Network](https://ernestnetwork.io/)

   - Implementing Tendermint Core's Application Blockchain Interface (ABCI) to manage the blockchain

   - Leveraging [modules](https://docs.cosmos.network/main/building-modules/intro.html) and other mechanisms implemented by the [Cosmos SDK](https://docs.cosmos.network/).

   - Utilizing [geth](https://github.com/ethereum/go-ethereum) as a library to promote code reuse and improve maintainability.

   - Exposing a fully compatible Web3 JSON-RPC layer for interacting with existing Ethereum clients and tooling (Metamask)[https://docs.pointnetwork.io/docs/point_chain/users/wallets/metamask].
   
The sum of these features allows developers to leverage existing Ethereum ecosystem tooling and software to seamlessly deploy smart contracts which interact with the rest of the Cosmos ecosystem!

## Quick Facts
- Ernest Chain Testnet	73287
- Ernest Chain Mainnet	73288
- Block Time	~2s

## Installation

For prerequisites and detailed build instructions please read the [Installation](https://evmos.dev/validators/quickstart/installation.html) instructions. Once the dependencies are installed, run:

```bash
make install
```

Or check out the latest [release](https://github.com/evmos/evmos/releases).

## Quick Start

To learn how the Erneest Chain works from a high-level perspective, go to the [Introduction](https://evmos.dev/about/intro/overview.html) section from the documentation. You can also check the instructions to [Run a Node](https://evmos.dev/validators/quickstart/run_node.html).

## Community

The following chat channels and forums are a great spot to ask questions about Evmos:

- [Ernest-Chain Twitter](https://twitter.com/ernestchain)
- [Ernest-Chain Discord](https://discord.gg/ernestchain)

