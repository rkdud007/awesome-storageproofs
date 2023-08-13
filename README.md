<div align="center">
  <h1 align="center">Awesome Storage Proofs</h1>

A place where you can find content, codebases, researches, projects and applications related to ZK Storage Proofs. Contributions and suggestions are always welcome, open issues or pull requests with any changes you want to be made and don't forget to join our Telegram community (link below).

  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="https://github.com/rkdud007/awesome-storageproofs/graphs/contributors">
      <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/rkdud007/awesome-storageproofs">
    </a>
    <a href="http://makeapullrequest.com">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>
  </p>

  <p align="center">Storage proofs are a cryptographic way to track blockchain state so that it can be shared across chains. A curated list of Storage Proofs resources. </p>
</div>

# Learn ZK

Here you can find a list of resources to get started with zero-knowledge cryptography.

- [Awesome-zkp-matter-labs](https://github.com/matter-labs/awesome-zero-knowledge-proofs)

# Contents

- [Articles](#articles)
- [Codebases](#codebases)
- [Projects](#projects)
- [Researches](#researches)
- [Usecases](#usecases)

## Articles

- [Cross-chain communication exploration – rollups’ vision](https://taiko.mirror.xyz/ryYEi4gAeOWwyERqYTs7CPbNEOYXaEeiMEui6gdlnyg)
- [Deeper dive on cross-L2 reading for wallets and other use cases](https://vitalik.ca/general/2023/06/20/deeperdive.html)
- [What are Storage Proofs and how can they improve Oracles?](https://starkware.medium.com/what-are-storage-proofs-and-how-can-they-improve-oracles-e0379108720a)

## Codebases

- [herodotus-eth-starknet](https://github.com/HerodotusDev/herodotus-eth-starknet)- Starknet-based State Verifier, Herodotus will allow anyone to trustlessly prove any past or current headers, state, and storage values of L1 contracts to other L2 contracts.
- [oracle-bridge](https://github.com/web3masons/oracle-bridge) - A proof of concept EVM to EVM cross-chain communication protocol using EVM Storage Proofs and Oracles by web3Manson

## Projects

- [Axiom](https://www.axiom.xyz/) - Scale data-rich applications on Ethereum. Access and process historic on-chain data trustlessly from your smart contract.
- [Herodotus](https://herodotus.dev/) - Storage proof technology that enables cross-domain data access between Ethereum layers
- [Lagrange Labs](https://www.lagrange.dev/)- Seamlessly interact between chains with cryptographically secure state proofs, not opaque intermediaries. Run expressive and dynamic distributed ZK computation at a Big Data scale on top of multi-chain contract states.
- [nil Foundataon](https://nil.foundation/about) =nil; Foundation is a pioneer in zero-knowledge technology, dedicated to making zkProofs and trustless data management accessible for developers.
- [Sunninct Labs](https://www.succinct.xyz/) - Powered by this proof of consensus, light client contracts on the target chain store the block headers of Ethereum. This enables anyone to supply state proofs of Ethereum (balances, storage, transactions, events, etc.)
- ZeroSync

## Usecases

- [StarkBadge](https://twitter.com/piapark_eth/status/1666435331112026112) - Reflect your historical data (storage proof of ownership storage) in Ethereum into a Starknet.

## Researches

### Merkle Mountain Ranges

#### Articles

- [Grin Documentation-MMR](https://docs.grin.mw/wiki/chain-state/merkle-mountain-range/)
- [Minimizing Storage Using Merkle Mountain Ranges](https://neptune.cash/learn/mmr/)
- [Over the Proofs: 🌎 a World of Trees Merkle Mountain Ranges Edition 🛰️](https://codyx.medium.com/over-the-proofs-a-world-of-trees-merkle-mountain-ranges-edition-%EF%B8%8F-dd4ac0e540fc)

#### Codebases

- [cairo-mmr](https://github.com/HerodotusDev/cairo-mmr) - An implementation of Merkle Mountain Ranges in Cairo, using Pedersen hash.
- [merkle-mountain-ranges](https://github.com/HerodotusDev/merkle-mountain-ranges) - An implementation of Merkle Mountain Ranges in TypeScript using the Pedersen hashing function.
- [Merkle mountain range](https://github.com/nervosnetwork/merkle-mountain-range) - A generalized merkle mountain range implementation in Rust.

### Storage Layout

#### Project

- [evm.storage](https://evm.storage/) - Increasing transparency and accessibility for EVM contracts: [Read article](https://blog.smlxl.io/introducing-evm-storage-c9fae8055286)

#### Articles

- [What is Smart Contract Storage Layout?](https://docs.alchemy.com/docs/smart-contract-storage-layout)
