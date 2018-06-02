# dapp-ecosystem-map
This repo provides a framework for thinking about the ways blockchain-based projects (primarily using Ethereum) are solving problems for end-users.

For an overview of Ethereum infrastructure layers / tech stack, please refer to the Ethereum Community Foundation's market map: https://github.com/EthereumCommunityFund/ethereum-ecosystem-map

For an overview of EOS's tech stack, please refer to this picture of an empty PokeBall:
![EOS Market Map](https://github.com/ConsenSysLabs/dapp-ecosystem-map/blob/master/figures/pokeball.jpg)

## Background
For both blockchain newcomers and OGs, it can be difficult to understand how projects are using blockchain to solve problems for end users. This document provides a framework for thinking through the various use cases of blockchain and blockchain-based technologies.

For each theme, this document captures examples of related projects. However, the inclusion of specific projects on this list does not denote an endorsement, nor does it signal the legitimacy of said project.

## Roadmap for this document
0) Add more projects and project links
1) Provide map of blockchain projects by industry.
2) "Curate" ecosystem map to only include projects which meet some objective measure of legitimacy and usage.
3) Make it easier for anyone to contribute to this list.

### How to Contribute?
For now, create an issue to recommend a change, error, or addition to our database.

---

## Table of Contents
0. [Taxonomy](#taxonomy)
1. [Markets and liquidity](#markets-and-liquidity)
2. [Tracking and Authentication](#tracking-and-authentication)
3. [Self-Sovereign Identity](#self-sovereign-identity)
4. [Automated Agreements](#automated-agreements)
5. [Token-Incentivized Markets](#token-incentivized-markets)
6. [Governance and Voting](#governance-and-voting)
7. [Shared Data Repos](#shared-data-repos)
8. [Uncensored Activity and Publications](#uncensored-activity-and-publications)

## Taxonomy
Here is a high-level framework to capture core themes for blockchain-based project development:
![Blockchain Thematic Framework](https://github.com/ConsenSysLabs/dapp-ecosystem-map/blob/master/figures/use_case_fw.jpg)

Here is a more specific categorization:
![Blockchain Project Framework](https://github.com/ConsenSysLabs/dapp-ecosystem-map/blob/master/figures/use_case_fw_2.jpg)


Notes:
* Themes are neither mutually exclusive or collectively exhaustive.
* Trustless exchange, decentralization, state mutation, and tokenization span each theme.
* Projects can be industry-specific or generally applicable.
* Examples focus on Ethereum-based projects.

### Markets and Liquidity

Projects in this theme use the blockchain to represent value and support global exchange. They use the blockchain both as a payments / value exchange rail and to create digital scarcity.

In success, such projects will unlock global resource sharing, fractional asset ownership, and frictionless cross-border exchange.

| Project      | Category     |
|--------------|------------- |
| GridPlus     | Fungible asset exchange - energy |
| Pangea   | Nonfungible asset exchange - real estate |
| Airswap     | Decentralized exchange (DEX)|
| Kyber Network     | Decentralized exchange (DEX)|
| Paradex     | Decentralized exchange (DEX) |
| Radar Relay     | Decentralized exchange (DEX) |
| Virtue Poker     | Gambling|
| CryptoKitties     | Gaming|
| Rarebits     | Nonfungible asset exchange|
| Origin Protocol     | Nonfungible asset exchange|
| Funfair     | Gambling |
| SpankChain     | Entertainment (State channel payments) |
| OmiseGo     | Ethereum-based payments (Plasma)|
| Golem     | Decentralized compute resources |
| IPFS     | Nonfungible asset exchange - storage|


### Tracking and Authentication

Projects which use blockchain as a single source of truth for asset ownership as well as provenance of physical and digital goods.


| Project      | Category     |
|--------------|------------- |
| Viant     | Asset track and trace / provenance |
| CryptoKitties     | Gaming (proof of ownership)           |
| ShipChain | Supply chain tracking |
| Ujo Music | Music digital rights tracking |
| R.A.R.E. Arts | Digital art ownership and verifiability|
| POEX | Document verification|

_Note: CryptoKitties also falls into Markets and Liquidity. That's how clustering works._

### Self-Sovereign Identity

Projects which allow individuals to selectively share personal information as well as the data they produce. Under such constructs, individuals are able to monetize their data directly.

| Project      | Category     |
|--------------|------------- |
| uPort     | SSI Solution |
| Status    | SSI Solution |
| Civic  | SSI Solution |
| Dominode  | SSI Solution |
| Basic Attention Token    | Monetize Your Data |


### Automated Agreements

Projects which allow for digitization and automation of business processes. Such processes often involve conditional payments and are multi-party transactions (thus benefiting from the trustless nature of blockchain applications.)

| Project      | Category     |
|--------------|------------- |
| OpenLaw    | Smart legal agreements for conditional value transfer|
| Request Network    | Invoicing on Ethereum |
| BlockFi    | Lending |
| Lendroid    | Non-custodial margin trading |

### Token-Incentivized Markets

Projects which leverage token mechanics to solve coordination problems. Such projects typically incentivize work, create knowledge, and/or "gamify" human coordination.

| Project      | Category     |
|--------------|------------- |
| MakerDAO     | Hiveminded research for stablecoin design |
| Gnosis     | Prediction market |
| Augur     | Prediction market |
| Kauri     | Knowledge network |
| Gitcoin and Bounties Network  | Work bounties |
| Frontier  | Token research platform |
| Civil  | Incentivization of fair and accurate reporting |
| TCR  | Token curated registry of non-fraudulent websites for advertising |

### Governance and Voting

Fairly self-explanatory. Blockchain provides data permanence, immutability, and auditability. Such features are convenience for voting. Blockchain-based voting systems enable blockchain-based governance models, including Decentralized Autonomous Organizations (or DAOs.)

| Project      | Category     |
|--------------|------------- |
| GovernX     | Decentralized governance |
| Aragon     | DAO |
| district0x     | Decentralized communities |
| Voatz     | Blockchain-based voting platform |

### Shared Data Repos

As an open database, blockchain provides a well designed system for connecting disparate data pools. Coupled with micropayments, blockchain-based data markets can enable IoT device interoperability, machine-to-machine economies, and machine learning data markets.

| Project      | Category     |
|--------------|------------- |
| TruSet       |Capital markets reference data  |
| Winding Tree |Decentralized repo for travel industry data  |
| Mediachain | Media datasets  |
| Tierion |Blockchain-based data anchoring  |
| Streamr |Data marketplace  |
| Dbrain | AI data marketplace  |
| Augmate | IoT  |

### Uncensored Activity and Publications

Blockchains are designed to minimize censorability and tamperability. Thus, blockchains enable truly open networks for publication, communication, and value exchange.

| Project      | Category     |
|--------------|------------- |
| Orchid Labs | Open internet platform|
| Decentraland | Uncensorable digital world|
| Leeroy | Decentralized social network|
| Leeroy | Decentralized social network|
| OpenBazaar | P2P commerce platform|
