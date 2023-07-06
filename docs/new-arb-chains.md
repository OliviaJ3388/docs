---
id: new-arb-chains
title: 'Creating new Arbitrum chains'
sidebar_label: Creating new Arbitrum chains
description: Understanding how and why new Arbitrum chains will be created
dao_author: dzgoldman
dao_sme: dzgoldman
---

import DraftExpectationsPartial from '@site/docs/partials/_draft-expectations-partial.md'; 

<DraftExpectationsPartial />

Ethereum Mainnet is a Layer 1 (L1) chain; <a data-quicklook-from='arbitrum-one'>Arbitrum One</a> and <a data-quicklook-from='arbitrum-nova'>Arbitrum Nova</a> are Layer 2 (L2) chains; Orbit chains are those that settle onto L2s. 

This document explains why the ability to create new L2/Orbit chains chains is exciting, and how the <a data-quicklook-from='arbitrum-dao'>Arbitrum DAO</a> will be involved in the process of creating these new chains moving forward.

## Why multiple chains?

An Ethereum multi-chain ecosystem is vital for several reasons:

1. **Scalability** - Multiple chains help overcome scaling bottlenecks by dividing activity into opt-in environments with separate resource management.
2. **Security models** - Different chains can experiment with various security models, allowing for trade-offs. For example: Arbitrum One and Arbitrum Nova are both L2 chains, with Arbitrum Nova giving developers the ability to optimize for lower fees.
3. **Execution environments** - Different chains can experiment with more-or-less restrictive execution environments that allow for trade-offs. For example, although Arbitrum chains are fully EVM compatible, app-specific chains may restrict smart contract functionality to optimize for performance.

### Terminology: L2s, Orbit chains, and beyond

In this document, "Layer 2 chain" refers to any Arbitrum chain settling directly onto Ethereum (chains with native bridge contracts on Ethereum <a data-quicklook-from='layer-1-l1'>Layer 1</a>), while "Orbit chain" refers to any Arbitrum chain that settles onto L2s. 

## New Arbitrum chains

### Layer 2 (L2) chains: Authorized by Arbitrum DAO

The Arbitrum DAO authorizes the creation of new L2 chains through the constitutional [governance proposal](./how-tos/create-submit-dao-proposal.md) mechanism. If a "new L2 chain" proposal passes, a new L2 chain is created. The DAO can authorize L2 chains that are governed by the Arbitrum DAO (these would be subject to [The Constitution of the Arbitrum DAO](./dao-constitution.md), like One and Nova), and those that are governed by other means.

### Orbit chains: No authorization required

Creating new Orbit chains on top of Arbitrum L2s doesn't require authorization or approval. Orbit chains can be deployed permissionlessly. This includes Orbit chains that run on a customized fork of the Arbitrum Nitro codebase, chains that introduce their own novel governance structures, and so on.

## Conclusion

The architecture supporting Arbitrum's chains ensures that the community enjoys control over how the Arbitrum tech stack is used, while still leaving room to foster the open, permissionless innovation expected from a vibrant web3 ecosystem.
