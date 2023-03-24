# OPAttest_Graph by [Credence](https://credence.0xprofile.space/)

## Links
- [Main Repo](https://github.com/0xProfile/Credence_op) for Credence

- [Playground](https://api.studio.thegraph.com/query/43982/credence_test_env/0.0.1) of GraphQL

## What is the purpose of Credence?
[Credence](https://credence.0xprofile.space/) is a platform that simplifies tracking and verifying identity and reputation on **Optimism's AttestationStation** for developers and users.

It enables cross-chain attestation, breaking down barriers between different networks, and offers a user-friendly interface, by providing an easy-to-read dashboard, search feature, and graph visualizations.

## [The Graph](https://thegraph.com/en/)'s job in Credence?

Credence has built a custom GraphQL API that indexes data from the Optimism's AttestationStation smart contract and enables users to understand their on-chain reputation and identity with low latency. As Optimism’s AttestationStation grows, our Graph will be more important than ever for product owners to fetch their user’s reputations and identity. 

## Install

```
npm install -g @graphprotocol/graph-cli
```

## Init
```
graph init --studio credence
```

## Authenticate in cli
```
graph auth --studio <api-key-here>
```
## ENTER SUBGRAPH
```
cd credence
```

## Build subgraph
```
graph codegen && graph build
```

## Deploy
```
graph deploy --studio credence
```
