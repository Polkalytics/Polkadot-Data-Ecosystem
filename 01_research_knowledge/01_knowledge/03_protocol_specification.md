# Polkaot Protocol Specification

The Polkadot Protocol Specification describes the Polkadot Host and Polkadot Runtime. It is the shared implementation of the Rust, Go, and C++ implementations that are also referenced there.

- URL: https://spec.polkadot.network/

## BABE
BABE is a protocol for propabilistic finality. It is an extension of Ouroboros Praos that works without relying on centralized NTP servers.

- Article: https://polkadot.network/blog/polkadot-consensus-part-3-babe
- Paper: https://research.web3.foundation/Polkadot/protocols/block-production/Babe

## GRANDPA
GRANDPA is Polkadot's finality gadget to achieve absolute finality.

- Article: https://polkadot.network/blog/polkadot-consensus-part-2-grandpa
- Paper: https://arxiv.org/abs/2007.01560?ref=cms.polkadot.network

## SASSAFRAS
SASSAFRAS is planned to replace BABE + Aura. It improves over BABE by ensuring that there is always a leader selected and it is always only one per slot.

- Paper https://research.web3.foundation/Polkadot/protocols/block-production/SASSAFRAS