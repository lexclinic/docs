---
description: double-entry bookkeeping & contributor access
---

# token (liability node)

Tokens are non-transferable and are not intended to have any monetary value.

This is an experimental use of tokens. The idea is that these tokens represent liabilities rather than assets.&#x20;

In other words, burning one of these tokens means a release from liability.

## example

This example is for an anonymous client.&#x20;

[https://app.kali.gg/daos/137/0xfed8909bcbb6f4a0feb9e1ede3ee0d0e83f5ec21](https://app.kali.gg/daos/137/0xfed8909bcbb6f4a0feb9e1ede3ee0d0e83f5ec21)

## proposal

This proposal system is designed with the idea that each contributor is an administrator who can unilaterally modify the liability node's state.

* voting period: 1 day&#x20;
* participation needed: 1%
*
* token transferability: disabled
* grace period: 0

We're still determining how to mint tokens.&#x20;

## seal

An NFT-seal collection is used as a shared legal wrapper.

### treasury owned

* [entity](https://app.gitbook.com/o/Ge5x1XBnN4Zr9dpGqkNC/s/cEok3YduYgyOTvIh4rtP/\~/changes/4/seal/entity)
* one of:
  * [engagement](https://app.gitbook.com/o/Ge5x1XBnN4Zr9dpGqkNC/s/cEok3YduYgyOTvIh4rtP/\~/changes/5/seal/engagement) parent, if client-treasury
  * [purpose](https://app.gitbook.com/o/Ge5x1XBnN4Zr9dpGqkNC/s/cEok3YduYgyOTvIh4rtP/\~/changes/4/seal/purpose) parent, if project-treasury
* [charity](https://app.gitbook.com/o/Ge5x1XBnN4Zr9dpGqkNC/s/cEok3YduYgyOTvIh4rtP/\~/changes/4/seal/charity), if tax deductible (optional)

### multisig signor owned

* one of:
  * [engagement](https://app.gitbook.com/o/Ge5x1XBnN4Zr9dpGqkNC/s/cEok3YduYgyOTvIh4rtP/\~/changes/5/seal/engagement) parent, if client-treasury
  * [purpose](https://app.gitbook.com/o/Ge5x1XBnN4Zr9dpGqkNC/s/cEok3YduYgyOTvIh4rtP/\~/changes/4/seal/purpose) parent, if project-treasury
