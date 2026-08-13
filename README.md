<!--lint disable double-link-->

# Awesome Cosmos with stars

> A community curated list of awesome projects related to the Cosmos ecosystem

The Cosmos SDK is a modular framework for building blockchain applications in Go.
Gaia, the implementation of the Cosmos Hub, is built with the Cosmos SDK.

**Contributing:**
Please read the [Contributing guide](./CONTRIBUTING.md). Thank you to all our [contributors](https://github.com/cosmos/awesome/graphs/contributors) ⭐ 601 | 🐛 11 | 📅 2026-04-13.

**Disclaimer: This community-maintained repo does not reflect the views of any official entity.**

## Contents

* [Core Components](#core-components)
* [Documentation](#documentation)
* [Client Libraries](#client-libraries)
  * [Go](#go)
  * [JavaScript](#javascript)
  * [Python](#python)
  * [Rust](#rust)
* [Block Explorers](#block-explorers)
  * [Visual Block Explorers](#visual-block-explorers)
  * [Terminal Block Explorers](#terminal-block-explorers)
* [Chain Registry](#chain-registry)
* [Validators](#validators)
* [Cosmos SDK Modules](#cosmos-sdk-modules)
* [Monitoring](#monitoring)
* [Indexers](#indexers)
* [Frameworks](#frameworks)
* [Virtual Machines](#virtual-machines)
* [IBC](#ibc)
* [Testing](#testing)
* [Templates](#templates)
* [Tools](#tools)
  * [CLI](#cli)
  * [GUI](#gui)
  * [Bots](#bots)
* [Node Operations](#node-operations)
  * [Utilities](#utilities)
* [Ecosystem](#ecosystem)
* [Wallets](#wallets)
* [Blogs](#blogs)
  * [Articles](#articles)
* [Related](#related)

## Core Components

* [Cosmos Hub](https://github.com/cosmos/gaia) ⭐ 575 | 🐛 44 | 🌐 Go | 📅 2026-08-13

<!-- -->

* [Cosmos SDK](https://github.com/cosmos/cosmos-sdk/) ⭐ 7,045 | 🐛 229 | 🌐 Go | 📅 2026-08-12
* [CosmWasm](https://github.com/CosmWasm/cosmwasm) ⭐ 1,148 | 🐛 42 | 🌐 Rust | 📅 2026-07-19
* [CometBFT](https://github.com/cometbft/cometbft) ⭐ 915 | 🐛 270 | 🌐 Go | 📅 2026-08-13
* [CosmJS](https://github.com/cosmos/cosmjs) ⭐ 700 | 🐛 181 | 🌐 TypeScript | 📅 2026-05-04
* [IBC Go](https://github.com/cosmos/ibc-go) ⭐ 645 | 🐛 32 | 🌐 Go | 📅 2026-08-12

<!-- -->

* [IAVL](https://github.com/cosmos/iavl) ⭐ 448 | 🐛 77 | 🌐 Go | 📅 2026-05-18
* [ICS23](https://github.com/cosmos/ics23) ⭐ 129 | 🐛 35 | 🌐 Rust | 📅 2026-04-13
* [Protobuf](https://buf.build/cosmos)

## Documentation

* [Cosmos Developer Portal](https://tutorials.cosmos.network)
* [Interchain Developer Academy](https://ida.interchain.io/)
* [Cosmos SDK](https://docs.cosmos.network/)
* [IBC](https://ibc.cosmos.com/)
* [CometBFT](https://docs.cometbft.com/)
* [Cosmos Hub](https://hub.cosmos.network/)
* [CosmWasm](https://docs.cosmwasm.com/docs/1.0/)
* [Cosmology](https://cosmology.tech/learn)

## Client Libraries

### Go

* [Ignite CLI](https://github.com/ignite/cli) ⭐ 1,350 | 🐛 10 | 🌐 Go | 📅 2026-08-10 - All-in-one platform to build, launch, and maintain any crypto application on a sovereign and secured blockchain. Quickly bootstraps a new Cosmos SDK blockchain with UI and support to create new and work conveniently with existing Cosmos SDK modules.

### JavaScript

* [cosmos/cosmjs](https://github.com/cosmos/cosmjs) ⭐ 700 | 🐛 181 | 🌐 TypeScript | 📅 2026-05-04 - The Cosmos JavaScript library.
* [cosmology-tech/cosmos-kit](https://github.com/cosmology-tech/cosmos-kit) ⭐ 201 | 🐛 45 | 🌐 TypeScript | 📅 2026-03-01 - A wallet connector for the Cosmos.
* [cosmology-tech/create-cosmos-app](https://github.com/cosmology-tech/create-cosmos-app) ⭐ 167 | 🐛 40 | 🌐 TypeScript | 📅 2025-12-11 - A npm package to bootstrap a Cosmos Web UI.
* [telescope](https://github.com/osmosis-labs/telescope) ⭐ 154 | 🐛 165 | 🌐 TypeScript | 📅 2026-04-02 - Typescript library generator built on top of CosmJS.
* [strangelove-ventures/graz](https://github.com/strangelove-ventures/graz) ⭐ 124 | 🐛 17 | 🌐 TypeScript | 📅 2026-07-30 - Collection of React hooks to interact with wallets, signers, signing clients, etc.
* [cosmology-tech/chain-registry](https://github.com/cosmology-tech/chain-registry) ⭐ 70 | 🐛 20 | 🌐 TypeScript | 📅 2026-08-13 - A npm package for the official Cosmos Chain Registry.
* [chainapsis/cosmosjs](https://github.com/chainapsis/cosmosjs) ⚠️ Archived - Chainapsis Signing & API Library.
* [cosmos-client/cosmos-client-ts](https://github.com/cosmos-client/cosmos-client-ts) ⭐ 35 | 🐛 13 | 🌐 JavaScript | 📅 2026-06-08 - JavaScript / TypeScript client for Cosmos SDK blockchains.
* [nabla-studio/quirks](https://github.com/nabla-studio/quirks) ⭐ 18 | 🐛 4 | 🌐 TypeScript | 📅 2025-10-14 - A universal wallet adapter for your Cosmos dApps, that works on both mobile and browser.
* [toschdev/bip44](https://github.com/toschdev/cosmos-bip44) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2024-01-28 - Cosmos BIP44 implementation in JavaScript for development and education learning.

### Python

* [cosmpy](https://github.com/fetchai/cosmpy) ⭐ 150 | 🐛 43 | 🌐 Python | 📅 2026-08-05 - A Python client library for interacting with blockchains based on the Cosmos SDK.
* [mospy](https://github.com/ctrl-Felix/mospy) ⭐ 39 | 🐛 1 | 🌐 Python | 📅 2024-08-03 - A Python library to create and sign transactions for Cosmos SDK based coins.
* [cosmospy-protobuf](https://github.com/ctrl-Felix/cosmospy-protobuf) ⭐ 20 | 🐛 6 | 🌐 Python | 📅 2023-12-30 - A Python library containing all compiled protobuf files (works very good for grpc).
* [pyCosmicWrap](https://github.com/ChihuahuaChain/pyCosmicWrap/) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2023-01-26 - A python3 wrapper around Cosmos API/RPC.
* [fx-py-sdk](https://github.com/functionx/fx-py-sdk) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2024-05-06 - The Cosmos Python client library.

### Rust

* [CosmWasm/cosmwasm](https://github.com/CosmWasm/cosmwasm) ⭐ 1,148 | 🐛 42 | 🌐 Rust | 📅 2026-07-19 - WebAssembly Smart Contracts for the Cosmos SDK.
* [iqlusioninc/stdtx](https://github.com/iqlusioninc/crates) ⭐ 577 | 🐛 50 | 🌐 Rust | 📅 2026-07-15 - A collection of open source Rust crates from iqlusion.
* [peggyjv/ocular](https://github.com/peggyjv/ocular) ⭐ 40 | 🐛 15 | 🌐 Rust | 📅 2024-07-26 - A client library for Cosmos SDK chains focusing on pleasant UX.

## Block Explorers

* [Ping.pub](https://ping.pub) - [Source](https://github.com/ping-pub/explorer) ⭐ 374 | 🐛 56 | 🌐 Vue | 📅 2026-07-09
* [Big Dipper](https://bigdipper.live) - [Source](https://github.com/forbole/big-dipper-2.0-cosmos) ⭐ 150 | 🐛 38 | 🌐 TypeScript | 📅 2024-11-25
* [ATOMScan](https://atomscan.com)
* [IOBScan](https://ibc.iobscan.io/)
* [Mintscan](https://www.mintscan.io)
  * [Mintscan for Cosmos Hub Testnet](https://cosmoshub-testnet.mintscan.io/cosmoshub-testnet)
* [NG Explorers](https://explorers.guru/)
* [Stake ID](https://stake.id)

### Visual Block Explorers

View Inter-Blockchain Communication (IBC) transfer activity. The map traces IBC transactions between different blockchains (called zones in the Cosmos Hub) to display accurate aggregate information about the pulse of the entire Cosmos ecosystem.

* [Map of Zones](https://mapofzones.com/?period=24) - [Source](https://github.com/mapofzones)
* [Mintscan](https://hub.mintscan.io) - Interchain Explorer by Cosmostation.

### Terminal Block Explorers

Explore Cosmos SDK blockchains via a terminal.

* [gex](https://github.com/cosmos/gex) ⚠️ Archived - GEX In-Terminal Explorer.
* [pvtop](https://github.com/blockpane/pvtop) ⚠️ Archived - Consensus visualizer on terminal.
* [tmtop](https://github.com/quokkastake/tmtop) ⭐ 74 | 🐛 4 | 🌐 Go | 📅 2025-05-20 - Htop-like visualiser of consensus inspired by pvtop that allows showing upgrade info, working with consumer chains and non-Cosmos chains and way more.
* [cshtop](https://github.com/gsk967/cshtop) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2023-02-23 - Cosmos htop , Blocks visualizer on terminal.

## Chain Registry

A registry containing standardized metadata from most Cosmos chains.

* [cosmos/chain-registry](https://github.com/cosmos/chain-registry/) ⭐ 574 | 🐛 109 | 🌐 Python | 📅 2026-08-12
* [Cosmos directory](https://cosmos.directory) - [Source](https://github.com/eco-stake/cosmos-directory) ⭐ 86 | 🐛 13 | 🌐 JavaScript | 📅 2025-03-24
* [cosmology-tech/chain-registry](https://github.com/cosmology-tech/chain-registry) ⭐ 70 | 🐛 20 | 🌐 TypeScript | 📅 2026-08-13 - A npm package for the official Cosmos Chain Registry.

## Validators

Popular block explorers provide a list of active validators. The easiest entry point to view validator profiles is from a block explorer:

* [List on Mintscan](https://www.mintscan.io/cosmos/validators)
* [List on ATOMScan](https://atomscan.com/validators)
* [List on BigDipper](https://cosmos.bigdipper.live/validators)
* [List on Kujira POD](https://pod.kujira.app/cosmoshub-4)

DYOR when choosing a validator. Consider delegating your tokens to validators outside of the top 20 to increase the decentralization of the network.
This is also a good practice to avoid 0% commission validators and exchange validators.

## Cosmos SDK Modules

The best place to find an accurate list of the Cosmos SDK modules is the project repository:

* For a list of production-grade modules, see the [List of Modules](https://docs.cosmos.network/main/modules/).
* For a list of well-known third-party modules, see [Cosmod.xyz](https://cosmod.xyz)

## Monitoring

* [Tenderduty](https://github.com/blockpane/tenderduty) ⚠️ Archived - Comprehensive monitoring tool for Tendermint chains. Its primary function is to alert a validator if they are missing blocks, and more.
* [PANIC Monitoring and Alerting For Blockchains](https://github.com/SimplyVC/panic) ⭐ 86 | 🐛 108 | 🌐 Python | 📅 2023-01-24 - An open source monitoring and alerting solution for Cosmos SDK, Substrate, and Chainlink-based nodes.
* [cosmos-validator-monitoring-service(CVMS)](https://github.com/cosmostation/cvms) ⭐ 75 | 🐛 16 | 🌐 Go | 📅 2026-06-16 - Integrated monitoring system for validators in the Cosmos app chain ecosystem.
* [Cosmos Chains Dashboard](https://github.com/zhangyelong/cosmos-dashboard) ⭐ 39 | 🐛 0 | 📅 2019-10-24 - A Grafana dashboard to monitor Cosmos SDK and Tendermint-based blockchain nodes.
* [Cosmon](https://github.com/iqlusioninc/cosmon) ⭐ 36 | 🐛 14 | 🌐 Rust | 📅 2023-05-16 - Observability tool for Cosmos and other Tendermint applications.
* [Prometheus Exporter](https://github.com/node-a-team/Cosmos-IE) ⭐ 19 | 🐛 5 | 🌐 Go | 📅 2023-02-15 - An integrated Prometheus exporter for the Cosmos SDK.
* [cosmos-proposals-checker](https://github.com/QuokkaStake/cosmos-proposals-checker.git) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2025-01-25 - A bot that sends you a notification on multiple Cosmos chains if your wallet hasn't voted on any proposal.
* [cosmos-validators-exporter](https://github.com/QuokkaStake/cosmos-validators-exporter.git) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2026-03-14 - A Prometheus exporter to scrape data about a validator (missed blocks, delegators count, total staked amount, rankings, etc.)
* [cosmos-transactions-bot](https://github.com/QuokkaStake/cosmos-transactions-bot.git) ⭐ 15 | 🐛 1 | 🌐 Go | 📅 2025-01-06 - A bot that sends you notifications on any transactions you want to be subscribed to on multiple Cosmos chains.
* [cosmos-node-exporter](https://github.com/QuokkaStake/cosmos-node-exporter.git) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2025-01-05 - A Prometheus exporter to scrape data on your node sync status, Cosmovisor upgrades and GitHub version mismatches, useful for node operators and validators.
* [missed-blocks-checker](https://github.com/QuokkaStake/missed-blocks-checker) ⭐ 9 | 🐛 1 | 🌐 Go | 📅 2025-01-29 - Monitor validators' missed blocks on multiple Cosmos chains and send its notifications to Telegram.
* [Chain Pulse](https://github.com/informalsystems/chainpulse) ⚠️ Archived - Relayed IBC packets monitor with Prometheus exporter.
* [cosmos-wallets-exporter](https://github.com/QuokkaStake/cosmos-wallets-exporter.git) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2024-09-21 - A Prometheus exporter to scrape data on wallets balance, useful to get notified if your wallet balance is too low.
* [UpgradesWatchdog](https://github.com/ChihuahuaChain/UpgradesWatchdog) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2022-11-27 - SoftwareUpgradeProposal & GitHub Releases telegram monitoring tool.
* [Nodes Checker](https://t.me/NodesGuru_bot) - Check your nodes status online, receive instant notification if something is wrong with your validator node.

## Indexers

* [BDJuno](https://github.com/forbole/bdjuno) ⭐ 94 | 🐛 44 | 🌐 Go | 📅 2024-11-25 - All the chains' data that are queried from the RPC and gRPC endpoints are stored inside a PostgreSQL database on top of which GraphQL APIs can then be created using Hasura.
* [Cosmos Indexer](https://github.com/DefiantLabs/cosmos-indexer) ⭐ 36 | 🐛 11 | 🌐 Go | 📅 2026-07-04 - A generalized DB schema indexer with correlation and direct database indexing in Go.
* [Cosmscan](https://github.com/cosmscan/cosmscan-go) ⚠️ Archived - An indexer engine for Cosmos chains.
* [interchain-indexer](https://github.com/Reecepbcups/interchain-indexer) ⭐ 20 | 🐛 8 | 🌐 Python | 📅 2023-08-04 - A cosmos blockchain indexer in Python.

## Frameworks

* [Cosmos SDK](https://github.com/cosmos/cosmos-sdk/) ⭐ 7,045 | 🐛 229 | 🌐 Go | 📅 2026-08-12 - A Framework for Building High Value Public Blockchains in Go.
* [CosmRS](https://github.com/cosmos/cosmos-rust/tree/main/cosmrs) ⭐ 346 | 🐛 16 | 🌐 Rust | 📅 2025-09-18 - Framework for building Cosmos blockchain applications in Rust.
* [Orga](https://github.com/nomic-io/orga) ⭐ 174 | 🐛 20 | 🌐 Rust | 📅 2025-01-25 - ABCI framework for state machine transitions in Rust.
* [ABCI-RS](https://github.com/devashishdxt/abci-rs) ⭐ 31 | 🐛 2 | 🌐 Rust | 📅 2023-03-07 - Rust crate for creating ABCI applications.
* [CosmosSwift](https://github.com/CosmosSwift) - Build blockchain applications in Swift on top of the Tendermint consensus.

## Virtual Machines

Modules or frameworks for virtual machines that run in the Cosmos SDK

* [Ethermint](https://github.com/evmos/ethermint) ⚠️ Archived - Ethereum Virtual Machine.
* [CosmWasm](https://github.com/CosmWasm/cosmwasm) ⭐ 1,148 | 🐛 42 | 🌐 Rust | 📅 2026-07-19 - WASM Virtual Machine & Rust Smart Contracts.
* [Polaris](https://github.com/berachain/polaris) ⚠️ Archived - Modular Ethereum Virtual Machine.
* [Agoric SDK](https://github.com/Agoric/agoric-sdk) ⭐ 357 | 🐛 1,810 | 🌐 TypeScript | 📅 2026-08-13 - Agoric JavaScript Smart Contract Platform.

## IBC

* [Interchain Standards](https://github.com/cosmos/ibc/) ⭐ 1,017 | 🐛 48 | 🌐 Go | 📅 2026-08-13 - Interchain Standards (ICS) for the Cosmos network & interchain ecosystem.
* [cosmos/ibc-go](https://github.com/cosmos/ibc-go) ⭐ 645 | 🐛 32 | 🌐 Go | 📅 2026-08-12 - Inter-Blockchain Communication protocol (IBC) implementation in Go.
* [informalsystems/hermes](https://github.com/informalsystems/hermes) ⭐ 505 | 🐛 220 | 🌐 Rust | 📅 2025-10-29 - IBC Relayer in Rust.
* [cosmos/relayer](https://github.com/cosmos/relayer) ⚠️ Archived - IBC Relayer in Go.
* [cosmos/ibc-rs](https://github.com/cosmos/ibc-rs) ⭐ 224 | 🐛 116 | 🌐 Rust | 📅 2025-07-10 - Rust implementation of the Inter-Blockchain Communication (IBC) protocol.
* [interchaintest](https://github.com/strangelove-ventures/interchaintest) ⭐ 197 | 🐛 78 | 🌐 Go | 📅 2026-02-11 - E2E testing framework for IBC Chains.
* [confio/ts-relayer](https://github.com/confio/ts-relayer) ⚠️ Archived - IBC Relayer in TypeScript.
* [local-interchain](https://github.com/Reecepbcups/local-interchain) ⚠️ Archived - Quickly spin up a local IBC development environment on any operating system.
* [IBC-escrow-auditor](https://github.com/Cordtus/ibc-escrow) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-28 - Standalone tool to check and report on-chain token amounts against the IBC lockup account on counterparty chain.
* [IBCprotocol.dev](https://ibcprotocol.dev/) - IBC Protocol website.

## Testing

* [quint](https://github.com/informalsystems/quint) ⭐ 1,600 | 🐛 241 | 🌐 TypeScript | 📅 2026-07-20 - Executable specification language with delightful tooling.
* [apalache](https://github.com/informalsystems/apalache) ⭐ 589 | 🐛 254 | 🌐 Scala | 📅 2026-08-11 - APALACHE: symbolic model checker for TLA+ and Quint.
* [interchaintest](https://github.com/strangelove-ventures/interchaintest) ⭐ 197 | 🐛 78 | 🌐 Go | 📅 2026-02-11 - E2E testing framework for IBC Chains.
* [tm-load-test](https://github.com/informalsystems/tm-load-test) ⭐ 47 | 🐛 10 | 🌐 Go | 📅 2024-11-15 - CometBFT load test application.
* [cosmos-sdk-codeql](https://github.com/crypto-com/cosmos-sdk-codeql) ⭐ 30 | 🐛 1 | 🌐 CodeQL | 📅 2023-12-05 - CodeQL queries for common Cosmos SDK bugs.
* [CometMock](https://github.com/informalsystems/CometMock) ⭐ 23 | 🐛 11 | 🌐 Go | 📅 2024-03-15 - Drop-in replacement for CometBFT in end-to-end tests.
* [atomkraft](https://github.com/informalsystems/atomkraft-cosmos) ⭐ 10 | 🐛 13 | 🌐 TLA | 📅 2023-01-10 - E2E testing framework of Cosmos SDK blockchains.
* [python-iavl](https://github.com/crypto-com/python-iavl) ⭐ 5 | 🐛 5 | 🌐 Python | 📅 2025-04-25 - IAVL inspection tool implemented in Python.
* [cosmosloadtester](https://github.com/orijtech/cosmosloadtester) ⭐ 5 | 🐛 3 | 🌐 TypeScript | 📅 2023-01-18 - Load tester for Cosmos SDK blockchains.

## Templates

Templates to help you get started with building a Cosmos SDK blockchain.

* [spawn](https://github.com/rollchains/spawn) ⭐ 114 | 🐛 24 | 🌐 Go | 📅 2026-02-06 -  Generate a new Cosmos SDK blockchain with testing, GitHub integrations, and easy instant testnets.
* [cosmosregistry/chain-minimal](https://github.com/cosmosregistry/chain-minimal) ⚠️ Archived -  Template and example of a minimal Cosmos SDK blockchain.
* [cosmosregistry/example](https://github.com/cosmosregistry/example) ⚠️ Archived - Template and example repository of a Cosmos SDK module.
* [ignite](https://github.com/cli) - Quickly bootstrap a new Cosmos SDK blockchain with UI and support to create new and work conveniently with existing Cosmos SDK modules.

## Tools

### CLI

* [cosmosvisor](https://github.com/cosmos/cosmos-sdk/tree/main/cosmovisor#readme) ⭐ 7,045 | 🐛 229 | 🌐 Go | 📅 2026-08-12 - Automates Cosmos SDK application binary upgrades.
* [tmkms](https://github.com/iqlusioninc/tmkms) ⭐ 367 | 🐛 28 | 🌐 Rust | 📅 2026-04-06 - Key Management System for Tendermint validators.
* [lens](https://github.com/strangelove-ventures/lens) ⚠️ Archived - CLI tool to interact with any Cosmos chain supporting the core Cosmos-SDK modules.
* [cosmos.nix](https://github.com/informalsystems/cosmos.nix) ⭐ 62 | 🐛 13 | 🌐 Nix | 📅 2025-08-29 - [Nix](https://nixos.org/) support for Cosmos and CosmWasm.
* [findaccount](https://github.com/blockpane/findaccount) ⚠️ Archived - Helps identify if an account exists on multiple Cosmos chains with the same address.
* [multisig](https://github.com/informalsystems/multisig) ⭐ 37 | 🐛 19 | 🌐 Go | 📅 2026-04-08 - CLI tool for managing multisig accounts on Cosmos SDK chains.
* [cosmosvanity](https://github.com/hukkinj1/cosmosvanity) ⭐ 35 | 🐛 3 | 🌐 Go | 📅 2023-06-18 - CLI tool for generating Cosmos vanity addresses.
* [airdrop-tools](https://github.com/Reecepbcups/airdrop-tools) ⭐ 20 | 🐛 9 | 🌐 Python | 📅 2024-04-08 - CLI scripts to help distribute a variety of tokens from multiple formats.
* [cosmos-genesis-tinkerer](https://github.com/hyphacoop/cosmos-genesis-tinkerer) ⭐ 17 | 🐛 2 | 🌐 Python | 📅 2026-05-12 - CLI tool for modifying Cosmos genesis files.
* [cosmology](https://github.com/cosmology-tech/cosmology) - CLI tool for making cryptocurrency trades, joining liquidity pools, and stake rewards on Osmosis.

### GUI

* [REStake](https://restake.app) - Auto-compounder app for Cosmos blockchains using Authz ([source](https://github.com/eco-stake/restake) ⭐ 373 | 🐛 31 | 🌐 JavaScript | 📅 2025-09-09).
* [Skip:Go](https://go.skip.build) - IBC token transfers, automated swapping and multi-hop routing ([source](https://github.com/skip-mev/skip-go-app) ⭐ 31 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-13).
* [Cosmfaucet](https://github.com/scalalang2/cosmfaucet) ⭐ 16 | 🐛 1 | 🌐 Go | 📅 2023-03-25 - Self-hosted faucet service for Cosmos based blockchain.
* [Cosmos Notifier](https://cosmos-notifier.decrypto.online) - Governance notification tool for Telegram and Discord ([source](https://github.com/shifty11/cosmos-notifier) ⭐ 4 | 🐛 5 | 🌐 Go | 📅 2025-10-12).

### Bots

* [cosmos-proposals-checker](https://github.com/QuokkaStake/cosmos-proposals-checker.git) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2025-01-25 - A bot to notify you if your wallets didn't vote on proposal on multiple Cosmos SDK chains.
* [cosmos-transactions-bot](https://github.com/QuokkaStake/cosmos-transactions-bot.git) ⭐ 15 | 🐛 1 | 🌐 Go | 📅 2025-01-06 - Get notified about transactions matching the filters you want on multiple Cosmos SDK chains.
* [cosmos-balance-bot](https://github.com/Reecepbcups/cosmos-balance-bot) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2022-11-17 - Get notified about your wallet balance on multiple Cosmos SDK chains at a set interval.
* [Cosmos Discord Bot](https://github.com/okp4/discord-bot) ⭐ 10 | 🐛 19 | 🌐 Rust | 📅 2026-04-22 - A general-purpose Discord bot for Cosmos SDK blockchains.
* [Cosmos Discord Faucet](https://github.com/0x4139/cosmos-discord-faucet) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2023-05-15 - A configurable Discord faucet for Cosmos SDK blockchains.
* [validator-stats-notifications](https://github.com/Reecepbcups/validator-stats-notifs) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2023-06-22 - Discord announcements including ranking, delegations over time, and unique delegators.
* [Secret Stashh NFT Bot](https://github.com/Reecepbcups/stashh-bot) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2023-08-28 - A discord bot to get notified of sales, auctions, and purchases for a Secret Network NFT collection.
* [DAODAO Treasury Bot](https://github.com/Reecepbcups/dao-treasury-bot) - A discord bot that keeps up with a DAO's treasury fiat value.
* [Cosmos Price Bot](https://github.com/Reecepbcups/cosmos-price-bot) - A discord bot that nicknames to the USD price of any cosmos token via a DEX.

## Node Operations

### Utilities

* [cosmos-operator](https://github.com/strangelove-ventures/cosmos-operator) ⭐ 101 | 🐛 53 | 🌐 Go | 📅 2026-04-11 - Cosmos Operator is a kubernetes operator for managing cosmos nodes.
* [Cosmos Cache](https://github.com/Reecepbcups/cosmos-endpoint-cache) ⭐ 26 | 🐛 10 | 🌐 Python | 📅 2023-11-22 - Optimize Cosmos queries by caching responses for predefined sets of time (regex).
* [Wallet-generator](https://github.com/Cordtus/wallet_generator) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-01-07 - Manually generate a keypair + wallet addresses from mnemonic, pubkey + wallet addresses from privkey, or wallet addresses from pubkey. Accepts arbitrary HDpath (incl. cointype)

## Ecosystem

The most up-to-date list of projects built using Cosmos SDK can be found on the [Cosmos Directory](https://cosmos.directory).

## Wallets

A list of wallets supporting Cosmos chains is <https://cosmos.network/ecosystem/wallets>.

## Blogs

As the ecosystem grows, so does the content. DYOR and follow the projects you find interesting.

**Disclaimer: This community-maintained repo does not reflect the views of any official entity.**

* [What is Cosmos?](https://cosmos.network/intro/)
* [Cosmos Blog](https://blog.cosmos.network/)
* [Interchain Foundation Blog](https://interchain-io.medium.com)

### Articles

* [Cosmos Dev Series: Cosmos Blockchain Upgrade](https://zerofruit.medium.com/cosmos-dev-series-cosmos-sdk-based-blockchain-upgrade-b5e99181554c)
* [Hardening guides](https://cyber.orijtech.com/scsec/cosmos-hardening)
* [How to connect your frontend to Cosmos blockchain](https://dev.to/kikiding/how-to-connect-your-frontend-to-cosmos-blockchain-5fcn)
* [(Not So) Smart Cosmos, examples of common Cosmos app vulnerabilities](https://github.com/crytic/building-secure-contracts/tree/master/not-so-smart-contracts/cosmos) ⭐ 2,476 | 🐛 58 | 🌐 Solidity | 📅 2026-04-13
* [Go coding guide](https://cyber.orijtech.com/scsec/cosmos-go-coding-guide)
* [The Cosmos Security Handbook - Part 1](https://www.faulttolerant.xyz/2024-01-16-cosmos-security-1)

## Related

* [Awesome CosmWasm](https://github.com/InterWasm/cw-awesome)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
