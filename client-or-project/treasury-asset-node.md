---
description: treasury as a 'neural' network node
---

# treasury (asset node)

Stablecoins accepted by the clinic:

* DAI
* USDC

## multisig

A transaction can be executed with 2/3 signors.

A single House cannot have more than 1 agent as a signor.

### 1. Origin signor

This signor is the party responsible for the stablecoins placed into the treasury.

If a client puts stablecoins into the treasury, the client's agent is the Origin signor.

If a grantor donates stablecoins to the treasury, the grantor's agent is the Origin signor.

If it's inappropriate for a grantor's agent to act as the Origin signor, a House agent will act as the Origin signor.&#x20;

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

NFT-seals are owned by the treasury.

### mandatory

* [entity](https://app.gitbook.com/o/Ge5x1XBnN4Zr9dpGqkNC/s/cEok3YduYgyOTvIh4rtP/\~/changes/4/seal/entity)
* [engagement](https://app.gitbook.com/o/Ge5x1XBnN4Zr9dpGqkNC/s/cEok3YduYgyOTvIh4rtP/\~/changes/5/seal/engagement), if client-treasury
* [purpose](https://app.gitbook.com/o/Ge5x1XBnN4Zr9dpGqkNC/s/cEok3YduYgyOTvIh4rtP/\~/changes/4/seal/purpose), if project-treasury

### optional

* [charity](https://app.gitbook.com/o/Ge5x1XBnN4Zr9dpGqkNC/s/cEok3YduYgyOTvIh4rtP/\~/changes/4/seal/charity), if tax deductible&#x20;
