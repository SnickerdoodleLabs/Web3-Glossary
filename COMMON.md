---
coverY: 0
---

# Common Terms

## Wallet

A crypto wallet (also commonly referred to as a digital wallet), is a piece of software that lets you interact with your digital assets on the blockchain. The wallet does this through the use of public-key cryptography technology to generate account addresses.

Nearly all consumer crypto wallets on the market today are Heirarchical Deterministic (HD) wallets. This means that when you set up a new crypto wallet, it produces, in a mathematically secure fashion, a human-readable secret recovery phrase (also known as a mnemonic or seed phrase) that itself is then used to algorithmically generate a deterministic sequence of account addresses, each account having its own public-private key pair. It is these addresses themselves (along with signatures generated from their private keys) that are used to prove ownership of digital assets on the blockchain. Your secret recovery phrase can be used to regenerate your accounts and the accounts’ public-private key pairs by importing the seed into a new wallet software application.

**WARNING**: Store your seed phrase somewhere secure to recover your accounts in case of an emergency and keep the private keys it generates private; A legitimate application will never ask you for your private keys or seed phrase and you should never reveal them to any third party, ever.

See our tutorial on [how to set up a wallet ](tutorials/getting-a-wallet.md)to learn more.&#x20;

## Non-Fungible Token (NFT)

A non-fungible token (NFT) is a unique digital asset that exists on the blockchain. It can be owned and interacted with via the functionality provided by a crypto wallet. Simply put, an NFT consists of three parts: a contract address (the storage location on the blockchain), a token ID (a unique reference number within that storage location), and metadata (like a URL). Currently, the most common code standard for implementing NFTs is given by the [EIP721](https://eips.ethereum.org/EIPS/eip-721) standard definition. Other consensus protocols that are not based on the [Ethereum Virtual Machine](https://ethereum.org/en/developers/docs/evm/) (EVM) have developed their own NFT standard definitions.

## Decentralized Exchange (DEX)

A decentralized exchange, commonly referred to as a DEX, is a smart contract program deployed to a blockchain that enables owners of fungible tokens to exchange them for other fungible tokens without the need for a third party to facilitate the trade. See our tutorial on [DEXs ](tutorials/how-do-i-use-a-dex.md)to learn how to use some of the most popular ones in Web3.&#x20;

## Decentralized Autonomous Organization (DAO)

A [DAO](https://en.wikipedia.org/wiki/Decentralized\_autonomous\_organization) is a smart contract program deployed to a blockchain. DAOs enable organization members to propose and vote on the execution of rules built into the organization's on-chain protocol in a manner that is fully transparent, auditable, and tamper-resistant.

## Layer 1

This is an alternative name for a base-layer consensus network. Networks like Bitcoin, Ethereum, and Avalanche are examples of _layer 1_ protocols. The term layer 1 does not imply a particular ledger data structure, i.e., a layer 1 protocol could be either blockchain-based or based on a directed acyclic graph (DAG) topology.

Helpful links / primers on blockchain, smart contracts, and Ethereum below:

* [3Blue1Brown, Youtube: "How does bitcoin actually work?](https://www.youtube.com/watch?v=bBC-nXj3Ng4\&t=3s)
* [Intro to Ethereum](https://ethereum.org/en/developers/docs/intro-to-ethereum/)
* [Smart Contracts](https://ethereum.org/en/developers/docs/smart-contracts/)
* [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/)

## Layer 2

This is a colloquial term for any technology that inherently derives its security from a layer 1 network. Typically, layer 2 technologies are designed to circumvent the throughput limitations of the layer 1 network they are secured against and therefor are often referred to as off-chain [scaling](https://ethereum.org/en/developers/docs/scaling/) techniques. Some common layer 2 approaches that are under active research and development include: [state-channels](https://ethereum.org/en/developers/docs/scaling/state-channels/), [zk-rollups](https://ethereum.org/en/developers/docs/scaling/layer-2-rollups/#zk-video), [side-chains](https://ethereum.org/en/developers/docs/scaling/sidechains/#top), etc.
