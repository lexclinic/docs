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

* Origin-signor
* Next-signor
* Fix-signor

A single House cannot have more than 1 signor on the multisig.

### 1. Origin-signor

The Origin-signor is the party responsible for the stablecoins that have been placed into the treasury.

* If a patron puts stablecoins into the treasury, the patron's agent is the Origin-signor.
* If a grantor donates stablecoins to the treasury, the grantor's agent is the Origin-signor.
  * If it's inappropriate for a grantor's agent to act as the Origin-signor, a signor from a different house will act as the Origin-signor:
    * the Origin-signor must be a signor without even the appearance of a conflict of interest

The Origin-signor should approve the transactions initiated by the Next-signor, and if not then the contributors might not be a good fit.

### 2. Next-signor

The Next-signor is the party responsible for:

* ensuring all the invoices are in order
* reaching out to Origin-signor&#x20;
  * to get an informal approval of the transaction
* start the transaction
* ensure Origin-signor approves the transaction
* execute the transaction

### 3. Fix signor

In the event one of the other two signors reject or abstain from signing a transaction, the Fix-signor will break the tie.

The Fix-signor will not start a transaction.

The Fix-signor is the arbitrator.

## seal

An NFT-seal collection is used as an arrayed legal wrapper.

### required

* [entity](../seal/entity.md)
* one of:
  * [engagement](../seal/retainer.md), if patron-file
  * [purpose](../seal/purpose.md), if project-file

