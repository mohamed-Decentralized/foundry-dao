# Foundry DAO Governance

This repository contains the implementation of a custom governance contract, `MyGovernor`, which integrates multiple extensions from OpenZeppelin's Governance framework. It combines the features of token-based voting, quorum calculation, proposal execution, and timelock control to create a full-featured governance system for decentralized organizations.

---

## Features

`MyGovernor` inherits from several OpenZeppelin contracts, enabling the following features:

- **Voting**: Token holders participate in governance proposals.
- **Quorum**: A percentage of the total supply of tokens must vote in favor for a proposal to pass.
- **Timelock**: Execution of proposals is delayed for a predefined time period to allow for the possibility of reversals.
- **Proposal Lifecycle**: Allows for the creation, execution, and cancellation of proposals, as well as tracking proposal states.

## Installation

```
git clone https://github.com/mohamed-Decentralized/foundry-dao.git
cd foundry-dao
forge install
forge build
```