# Glossary of Advanced Terms

## State Channels

State channels allow participants to securely transact off-chain while keeping interaction with Ethereum Mainnet at a minimum. Channel peers can conduct an arbitrary number of off-chain transactions while only submitting two on-chain transactions to open and close the channel. This allows for extremely high transaction throughput and results in lower costs for users. ([Source](https://ethereum.org/en/developers/docs/scaling/state-channels/))

## Payment Channels

[Payment channels](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9300150) are a [layer 2](/documentation/gitbook/definitions-and-key-terms.md#layer-2) technique that is a 
specialization of state-channels. They are designed specifically for scaling trustless value transfers without having to submit transactions directly to a 
[layer 1](/documentation/gitbook/definitions-and-key-terms.md#layer-1) network. This is accomplished via a two-party consensus protocol in which digital 
signatures are shared directly between two participants via a p2p communication layer. 