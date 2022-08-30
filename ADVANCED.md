# Glossary of Advanced Terms

## Content Addressable Network

A content addressable network is network of machines in which an asset, tracked by the network, can be referenced by its *hash*. That is, 
instead of requesting a file by referring to its human-readable name (i.e. `cat.jpg`), a file is requested by referring to the result of running
the `cat.jpg` file through a cryptographically secure hashing algorithm (i.e. 
[`QmPrrEV81x7Lm8qhKXHAc1Sw8nSsBTMHN3HmRFnc7Q1CjU`](https://ipfs.io/ipfs/QmPrrEV81x7Lm8qhKXHAc1Sw8nSsBTMHN3HmRFnc7Q1CjU)). The benefit of 
requesting an asset by its hash is that once the asset is delivered, the user can independently verify that they have indeed received the information
they were looking for by applying the hashing algorithm to the file delivered by the network. 

Some examples of popular content addressible network protocols include:

1. [IPFS](https://ipfs.io)
2. [SWARM](https://www.ethswarm.org/)
3. [ARWEAVE](https://www.arweave.org/)

## Layer 1

This is an alternative name for a base-layer consensus network. Networks like Bitcoin, Ethereum, and Avalanche are examples of *layer 1* protocols. 
The term layer 1 does not imply a particular ledger data structure, i.e., a layer 1 protocol could be either blockchain-based or based on a 
directed acyclic graph (DAG) topology. 

Helpful links / primers on blockchain, smart contracts, and Ethereum below:

- [3Blue1Brown, Youtube: "How does bitcoin actually work?](https://www.youtube.com/watch?v=bBC-nXj3Ng4&t=3s)
- [Intro to Ethereum](https://ethereum.org/en/developers/docs/intro-to-ethereum/)
- [Smart Contracts](https://ethereum.org/en/developers/docs/smart-contracts/)
- [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/)

## Layer 2

This is a colloquial term for any technology that inherently derives its security from a layer 1 network. Typically, layer 2 technologies are designed to circumvent
the throughput limitations of the layer 1 network they are secured against and therefor are often referred to as off-chain [scaling](https://ethereum.org/en/developers/docs/scaling/) 
techniques. Some common layer 2 approaches that are under active research and development include: [state-channels](https://ethereum.org/en/developers/docs/scaling/state-channels/), 
[zk-rollups](https://ethereum.org/en/developers/docs/scaling/layer-2-rollups/#zk-video), [side-chains](https://ethereum.org/en/developers/docs/scaling/sidechains/#top), etc.

## Payment Channels

[Payment channels](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9300150) are a [layer 2](/documentation/gitbook/definitions-and-key-terms.md#layer-2) technique that is a 
specialization of state-channels. They are designed specifically for scaling trustless value transfers without having to submit transactions directly to a 
[layer 1](/documentation/gitbook/definitions-and-key-terms.md#layer-1) network. This is accomplished via a two-party consensus protocol in which digital 
signatures are shared directly between two participants via a p2p communication layer. 

## State Channels

State channels allow participants to securely transact off-chain while keeping interaction with Ethereum Mainnet at a minimum. Channel peers can conduct an arbitrary number of off-chain transactions while only submitting two on-chain transactions to open and close the channel. This allows for extremely high transaction throughput and results in lower costs for users. ([Source](https://ethereum.org/en/developers/docs/scaling/state-channels/))