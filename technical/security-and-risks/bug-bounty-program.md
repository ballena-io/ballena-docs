# Bug Bounty Program

[ballena.io](https://ballena.io/) launches a bug bounty program payout of up to $5,000 that focuses on finding vulnerabilities in the smart contracts & the blockchain code.

## Reporting a Vulnerability

If you identify a potential vulnerability, please head over to our security channel in Discord and submit your findings to the [ballena.io](https://ballena.io/) team for a review. 

{% embed url="https://discord.com/invite/7dJEAmMX" %}

The [ballena.io](https://ballena.io/) team will filter the reported bugs through an exhaustive study of the matter. In case the bug is confirmed, the triage team will notify the [ballena.io](https://ballena.io/)'s devs for them to immediately rectify the vulnerability should they deem it valid. 

## Rewards by Threat Level

Rewards are distributed according to the impact of the vulnerability based on the [Immunefi Vulnerability Severity Classification System](https://immunefi.com/severity-system/). This is a simplified 5-level scale, which includes different scales for websites/apps and smart contracts/blockchains, taking into account the probability of success for an exploit to happen and its consequences.

Payouts are handled by the [ballena.io](https://ballena.io/) team directly and are denominated in USD. Payouts are done in BALLE tokens.



#### Smart Contracts and Blockchain

| Threat Level | Reward |
| :--- | :--- |
| Critical | $5000 |
| High | $1000 |
| Medium | $500 |
| Low | $100 |
| None | $0 |

## Assets in Scope

{% embed url="https://github.com/ballena-io/ballena-protocol/blob/master/contracts/token/BALLEv2.sol" %}

{% embed url="https://github.com/ballena-io/ballena-protocol/blob/master/contracts/vaults/BalleMaster.sol" %}

{% embed url="https://github.com/ballena-io/ballena-protocol/blob/master/contracts/treasury/BalleTreasury.sol" %}

{% embed url="https://github.com/ballena-io/ballena-protocol/blob/master/contracts/strategies/StratPancakeLpV3.sol" %}

{% embed url="https://github.com/ballena-io/ballena-protocol/blob/master/contracts/strategies/StratBalleLpV1.sol" %}

{% embed url="https://github.com/ballena-io/ballena-protocol/blob/master/contracts/strategies/StratPancakeCakeV2.sol" %}

{% embed url="https://github.com/ballena-io/ballena-protocol/blob/master/contracts/staking/BalleStakingPoolV1.sol" %}

{% embed url="https://github.com/ballena-io/ballena-protocol/blob/master/contracts/staking/BalleRewarder.sol" %}

{% embed url="https://github.com/ballena-io/ballena-protocol/blob/master/contracts/staking/BalleRewardFund.sol" %}

{% embed url="https://github.com/ballena-io/ballena-protocol/blob/master/contracts/staking/BalleRewardDistribution.sol" %}

## Our priority

We are especially interested in receiving and rewarding vulnerabilities of the following types:

* Smart Contracts and Blockchain.
* Re-entrance.
* Logic errors including user authentication errors.
* Solidity/EVM details not considered including:
  * integer over/under-flow.
  * rounding errors.
  * unhandled exceptions.
* Trusting trust/dependency vulnerabilities including composability vulnerabilities.
* Oracle failure/manipulation.
* Novel governance attacks.
* Economic/financial attacks including flash loan attacks.
* Congestion and scalability including:
  * running out of gas.
  * block stuffing.
  * susceptibility to frontrunning.
* Consensus failures.
* Cryptography problems.
* Signature malleability.
* Susceptibility to replay attacks.
* Weak randomness.
* Weak encryption.
* Susceptibility to block timestamp manipulation.
* Missing access controls / unprotected internal or debugging interfaces.

## Out of Scope & Rules

The following vulnerabilities are excluded from the rewards for this bug bounty program:

* Attacks that the reporter has already exploited themselves, leading to damage.
* Attacks requiring access to leaked keys/credentials.
* Attacks requiring access to privileged addresses \(governance, strategist\).

Smart Contracts and Blockchain

* Incorrect data supplied by third party oracles.
* Not to exclude oracle manipulation/flash loan attacks.
* Basic economic governance attacks \(e.g. 51% attack\).
* Lack of liquidity.
* Best practice critiques.
* Sybil attacks.

The following activities are prohibited for our bug bounty program:  


* Any testing with mainnet or public testnet contracts; all testing should be done on private testnets.
* Any testing with pricing oracles or third party smart contracts.
* Attempting phishing or other social engineering attacks against our employees and/or customers.
* Any testing with third party systems and applications \(e.g. browser extensions\) as well as websites \(e.g. SSO providers, advertising networks\).
* Any denial of service attacks.
* Automated testing of services that generate significant amounts of traffic.
* Public disclosure of an unpatched vulnerability before the development team confirms the vulnerability has been corrected.

Public disclosure of an unpatched vulnerability in an embargoed bounty situation due to legal constraints not related to [ballena.io](https://ballena.io/).





