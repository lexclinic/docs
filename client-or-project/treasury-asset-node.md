---
description: treasury as a 'neural' network node
---

# treasury asset-node

The Clinic only accepts stablecoins.

Stablecoins accepted by the Clinic:

* DAI
* USDC

## example

[Treasury](https://app.safe.global/matic:0x2693DD4866BDf8ECCb2288D410C545E434B728C8/home) for the anon client file LC5578 (does not yet include an entity-Seal)

## multisig

A transaction can be executed with 2/3 signors:

* Origin signor
* Next signor
* Fix signor

A single House cannot have more than 1 journeyperson as a signor.

### 1. Origin signor

This signor is the party responsible for the stablecoins placed into the treasury.

* If a client puts stablecoins into the treasury, the client's agent is the Origin signor.
* If a grantor donates stablecoins to the treasury, the grantor's agent is the Origin signor.
  * If it's inappropriate for a grantor's agent to act as the Origin signor, a House journeyperson will act as the Origin signor:
    * without a conflict of interest; and
    * from a different House than the Next signor's House journeyperson

The Origin signor should approve the transactions initiated by the Next signor.

### 2. Next signor

The Next-signor is the party responsible for collecting invoices and initiating treasury transactions to pay invoices.

Invoices include grant distributions.

The Next signor is the House agent hosting the client or project.

### 3. Fix signor

In the event one of the other two signors reject or abstain from signing a transaction, the Fix signor will break the tie.

The Fix signor will not start a transaction.

The Fix signor is the arbitrator.

## seal

An NFT-seal collection is used as a shared legal wrapper.

### required

* [entity](../seal/entity.md)
* one of:
  * [engagement](../seal/retainer.md), if client-file
  * [purpose](../seal/purpose.md), if project-file

