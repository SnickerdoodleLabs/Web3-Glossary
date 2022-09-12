---
coverY: 0
---

# Common Terms

## Altcoin

Any cryptocurrency that isn’t [Bitcoin](https://bitcoin.org/en/) or [Ether](https://ethereum.org/en/) (some even consider Ether to be an altcoin), the two largest and most influential in the industry. Popular altcoins include [Polygon](https://polygon.technology/), [Solana](https://solana.com/), [Ripple](https://ripple.com/) and our own 
forthcoming protocol token.

## Anti-Money Laundering (AML)

Anti-money laundering laws, regulations, and policies are intended to prevent criminal individuals, organizations and enterprises from shielding illegally obtained funds from scrutiny or disguising them as legitimate legal income. AML rules require that businesses actively take part in preventing and combating money laundering, terrorism financing, and other financial crimes. In the United States, AML laws are enforced primarily by [FinCEN](https://www.fincen.gov/history-anti-money-laundering-laws).

## Centralized Exchange (CEX)

A centralized exchange, commonly referred to as a CEX, is typically a for-profit business that facilitates the purchasing of crypto/digital assets with fiat currency (like USD). A
CEX will likely require that a user pass [KYC](#know-your-customer-kyc) and [AML](#anti-money-laundering-aml) checks before they are allowed to onboard into the application in 
order to comply with regulatory requirements. CEXs often support traditional order-book style trading with limit and market orders for obtaining fungible and [non-fungible](#non-fungible-token-nft) digital assets. 

## Cold Storage

Cold storage refers to the use of an offline piece of hardware to store passwords to online wallets. Written notes can also be considered a form of cold storage (often referred to as [*paper wallets*](https://en.bitcoin.it/wiki/Paper_wallet)). The term primarily implies that the technology storing the user's private key is not directly connected to the internet. 

## Decentralized Autonomous Organization (DAO)

A [DAO](https://en.wikipedia.org/wiki/Decentralized\_autonomous\_organization) is a [smart contract](#smart-contract) program deployed to a blockchain. Specifically, DAOs enable 
organization members to propose and vote on the execution of rules built into the organization's on-chain protocol in a manner that is fully transparent, auditable, and 
tamper-resistant. DAOs and their use-cases are an active area of [interdisciplinary research](https://ralphmerkle.com/papers/DAOdemocracyDraft.pdf), and new applications for 
decentralized governance are constantly being explored.  

## Decentralized Exchange (DEX)

A decentralized exchange, commonly referred to as a DEX, is a [smart contract](#smart-contract) program deployed to a blockchain that enables owners of fungible tokens to 
exchange them for other fungible tokens without the need for a trusted third party to facilitate the trade. See our tutorial on [DEXs](tutorials/how-do-i-use-a-dex.md) to learn 
how to use some of the most popular ones in Web3. Some of the most popular DEXs in Web3 include:

- [Uniswap](https://uniswap.org/)
- [Curve](https://curve.fi/)
- [Trader Joe XYZ](https://traderjoexyz.com/)

## Hot Storage

Hot storage refers to a crypto [wallet](#wallet) software application that is connected to the internet. Hot storage wallets are more convenient to use than 
[cold storage](#cold-storage) wallets at the cost of reduced security. Most hot storage wallets take the form of a 
[browser extension](/tutorials/getting-a-wallet.md/#browser-based-wallets) or [mobile application](/tutorials/getting-a-wallet.md/#mobile-based-wallets).

## Know Your Customer (KYC)

Institutions of all sizes use KYC processes to ensure that they know enough about each person with whom they are doing business. These processes are often necessary to ensure that the institution complies with regulations such as the US Department of Treasury’s 
[Office of Foreign Asset Controls](https://home.treasury.gov/policy-issues/office-of-foreign-assets-control-sanctions-programs-and-information) (OFAC) and other asset 
control regulations applicable in different jurisdictions.

## Non-Fungible Token (NFT)

A non-fungible token (NFT) is a unique digital asset that exists on the blockchain that you can buy and trade. It can be owned and interacted with via the functionality provided by a crypto [wallet](#wallet). 

An NFT consists of three parts: 

- a contract address (the storage location on the blockchain)
- a token ID (a unique reference number within that storage location)
- metadata (like a URL)

Currently, the most common code standard for implementing NFTs is given by the [EIP-721](https://eips.ethereum.org/EIPS/eip-721) standard definition which is a technical 
specification for how wallets and exchanges can interact with the asset. Other consensus protocols, that are not based on the 
[Ethereum Virtual Machine](https://ethereum.org/en/developers/docs/evm/) (EVM), have developed their own NFT standard definitions.

## Proof-of-Work (PoW)

Proof-of-Work is a cryptographic algorithm that allows a computer (or really anything) to prove beyond a reasonable doubt that at least some amount of effort has been expended. 
Historically, PoW algorithms were used to [fight email spam](https://en.wikipedia.org/wiki/Hashcash). Today, PoW algorithms are used in many blockchain networks as the mechanism 
by which a computer proves that it has the right to decide on what transactions are included in the next block added to the block chain. The most important protocol that still 
uses PoW is [Bitcoin](https://bitcoin.org/en/how-it-works#processing). Computers running the blockchain protocol compete to produce a Proof-of-Work receipt that fits a certain 
pre-agreed upon pattern before anyone else. The parameters that produce the pattern are hard to find, but trivially easy to verify. 

## Smart Contract

A smart contract is a special computer program that is designed specifically to run on a blockchain. The primary purpose of smart contracts is to try to remove the need for 
a trusted third party or intermediary by implementing customized logic for executing a transfer of value with special conditions or registering a commitment of information. Specific examples of applications that are fundamentally enabled by smart contracts include:

- [DEXs](#decentralized-exchange-dex)
- [DAOs](#decentralized-autonomous-organization-dao)
- [Stablecoins](#stablecoin)
- [Non-Fungible Tokens](#non-fungible-token-nft)
-  Multi-Signature Accounts

The [Etheruem Virtual Machine](https://ethereum.org/en/developers/docs/evm/) is smart contract operating system that has been adopted by the largest number of blockchain 
protocols and also has the currently enjoys the largest developer base. 

## Stablecoin

Stablecoins are a type of digital currency that is backed by existing reserve assets to help them avoid drastic changes in valuation. There are four subcategories of stablecoin:

1. fiat-backed (tied to a government issued currency)
2. commodity-backed (tied to a physical commodity like oil or gold)
3. Crypto-backed (tied to other cryptocurrencies)
4. algorithmic (tied to the number of tokens in circulation).

Stablecoins are an [active area of research](https://fdc.stanford.edu/) both from a technical implementation perspective but also from a regulatory and compliance context. 

## Subnet

A [subnet](https://docs.avax.network/subnets) is **a sovereign network which defines its own rules regarding its membership and token economics** based on the [Avalanche Protocol](https://docs.avax.network/). It is composed of a dynamic subset of Avalanche validators working together to achieve consensus on the state of one or more blockchains.

## Transaction Fee

Every blockchain requires that a fee be paid by a user in order to interact with their digital assets. You interact with your digital assets (i.e. trade them or move them to new accounts) by broadcasting a transaction to the blockchain network through your [wallet](#wallet) software. In order to prevent the blockchain network from being spammed by frivolous transactions, a monetary cost is imposed, called a transaction fee. In the case of the Ethereum network or Ethereum-like networks, the transaction fee is referred to as [_gas_](https://ethereum.org/en/developers/docs/gas/).

## Wallet

A crypto wallet (also commonly referred to as a digital wallet), is a piece of software that lets you interact with your digital assets on the blockchain. The wallet does this through the use of public-key cryptography technology to generate account addresses.

Nearly all consumer crypto wallets on the market today are Hierarchical Deterministic (HD) wallets. This means that when you set up a new crypto wallet, it produces, in a mathematically secure fashion, a human-readable secret recovery phrase (also known as a mnemonic or seed phrase) that itself is then used to algorithmically generate a deterministic sequence of account addresses, each account having its own public-private key pair. It is these addresses themselves (along with signatures generated from their private keys) that are used to prove ownership of digital assets on the blockchain. Your secret recovery phrase can be used to regenerate your accounts and the accounts’ public-private key pairs by importing the seed into a new wallet software application.

{% hint style="danger" %}
**WARNING**: Store your secret recovery phrase somewhere secure to recover your accounts in case of an emergency and keep the private keys it generates private; A legitimate application will never ask you for your private keys or seed phrase and you should never reveal them to any third party, ever.
{% endhint %}

See our [tutorial](tutorials/getting-a-wallet.md) for getting started with your first wallet.
