# Gnosis: Multisig system

We are glad to announce **we are the first project working with Gnosis** Multisig system in the Binance Smart Chain. 

A multiple signature wallet is a cryptocurrency wallet that controls access and changes to one or more Smart Contracts. Most of the community governed projects in the Ethereum network often require multiple signers to approve a transaction before it will be executed. 

[ballena.io](https://ballena.io/) is the first project in the BSC implementing Gnosis Safe to run our DAO. We have implemented a structure of 3 Gnosis wallets depending on the degree of risk of the actions to be carried out and therefore varying the level of security for each of the areas.



![](../.gitbook/assets/image.png)



#### Wallet 1: Governance Protocol

This wallet is the most critical one. It is in charge of the daily actions of the platform and has access to all operations that have to do with Smart Contracts and [ballena.io](https://ballena.io/) in general. Changing the contract address of the treasury, changing the Gnosis wallets and treasury operations are examples of the actions that it carries out. 

It is governed by the 3/5 model, that is, it takes 3 signatures out of 5 signing wallets to be able to carry out an operation.



#### Wallet 2: Operations Protocol

It carries out less critical actions but that still require a minimum of signatures so as not to compromise the project. This is in the medium security level. Changing the multiplier of the rewards in BALLE tokens, deactivating the BALLE rewards of the vaults, resuming the vaults or adding a new vault are functions that this wallet can execute. 

It is governed by the 3/5 model, that is, it takes 3 signatures out of 5 signing wallets to be able to carry out an operation \(Number of signatures to be determined\).



#### Wallet 3: Security Emergency Protocol

This protocol is reserved for emergency situations and only one signature will be necessary to execute the actions within its limits. This wallet cannot execute transcendental actions that affect the project, but it is used to take immediate action by a signer in the event of an attack or dangerous situation. Pausing the vaults or pausing the BALLE distributions, for example, are functions that this wallet can carry out.



#### Wallet 4: Donations

In this wallet, the donations that users voluntarily make for the startup and the initial transactions required for the correct launch and operation of the platform are received. 

The donations collected in this wallet are transferred to the treasury and from there, they are distributed to the expense wallets \(the one for deployments and the multisig of Governance, Operations and Security, and to the wallet that performs the harvest\). 

It is governed by the 3/5 model, that is, it takes 3 signatures out of 5 signing wallets to be able to carry out an operation.



In the following file you will see all the functions and their respective description, as well as the wallets that have all these functions assigned.

{% file src="../.gitbook/assets/balle-smartcontracts-smartcontracts-gnosis-access.pdf" caption="Smart Contracts Gnosis Access" %}



For more information about the Gnosis Multisig system, click on the following link.

{% embed url="https://docs.binance.org/smart-chain/developer/gnosis.html" %}





