---
sidebar_position: 2
---

# Terminology

## JSON RPC
If you are a web 2.0 developer, you should already be familiar with using the `REST` architecture (RESTful API) to build web services. The `JSON-RPC` is a lightweight remote procedure call (RPC) protocol that primarily relies on predefined data structures and rules around their processing. The JSON-RPC is mostly preferred when building web 3.0 applications because it allows for mapping to method calls and communications can be easily understood.

The table below outlines the difference between `REST` and `JSON-RPC`:

| JSON-RPC                        |  REST                                  |
|---------------------------------|----------------------------------------|
| Remote procedure call (RPC)     | Representational State Transfer (REST) |
| Accepted formats: JSON          | Accepted formats: JSON, XML, etc       |
| Easy to implement               | Can be complex                         |
| Stateless in nature             | Maintains a state                      |

You can read more about JSON-RPC from the official website [here](https://www.jsonrpc.org/specification).
## NFT
A non-Fungible Token (NFT) is a financial asset consisting of data securely stored on the blockchain that is transferable from one owner to another making it tradeable on the blockchain. An NFT can contain data of any sort ranging from a piece of art, 3D design, gift cards, vouchers, photographs, etc.

Since NFTs are tokens they can be sold for exchange of cryptocurrencies on the blockchain.

## Utility
A `Utility` is a code name for a resource you create through the Gada API, you can envision a utility to represent a resource created uniquely for a purpose of deploying it to a blockchain. We've developed an array of methods to help you create, mint and export utilities to the blockchain as NFT using Gada API.

## Master Utility
A master utility is like a pre-designed template that other utilities can be derived from them. Think about a master utility as a collection of `NFT`s held by a user on the blockchain. The [createMasterUtility](./API%20Methods/createMasterUtility.md) method allows users to create master utilities using the Gada API.
