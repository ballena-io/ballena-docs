# Programa Bug Bounty

[ballena.io](https://ballena.io/) lanza un programa de bug bounty que remunera hasta en 5.000 dólares y se centra en la búsqueda de vulnerabilidades en los contratos inteligentes y en el código del blockchain.



![](https://cdn-images-1.medium.com/max/800/1*Wb-OXpMQ1E9SbIxANDrFcQ.png)

## **Informar sobre una vulnerabilidad**

Si identificas una posible vulnerabilidad, dirígete a nuestro canal de seguridad en Discord y envía tus hallazgos al equipo de [ballena.io](https://ballena.io/) para que los revisen.

{% embed url="https://discord.com/invite/7dJEAmMX" %}

El equipo de [ballena.io](https://ballena.io/) revisará los bugs reportados mediante un estudio exhaustivo del asunto. En caso de que el bug sea confirmado, el equipo de triage lo notificará a los devs de [ballena.io](https://ballena.io/) para que rectifiquen inmediatamente la vulnerabilidad si así lo consideran.

## **Recompensas por nivel de amenaza**

Las recompensas se distribuyen en función del impacto de la vulnerabilidad, basándose en el [Sistema de Clasificación de la Severidad de la Vulnerabilidad](https://immunefi.com/severity-system/) de **Immunefi**. Se trata de una escala simplificada de 5 niveles, que incluye diferentes escalas para sitios web/aplicaciones y contratos inteligentes/blockchains, teniendo en cuenta la probabilidad de éxito de un exploit y sus consecuencias.  
Los pagos son manejados por el equipo de ballena.io directamente y están denominados en **USD**. Los pagos se realizan en tokens **BALLE**.

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

* Incorrect data supplied by third-party oracles.
* Not to exclude oracle manipulation/flash loan attacks.
* Basic economic governance attacks \(e.g. 51% attack\).
* Lack of liquidity.
* Best practice critiques.
* Sybil attacks.

The following activities are prohibited for our bug bounty program:

* Any testing with mainnet or public testnet contracts; all testing should be done on private testnets.
* Any testing with pricing oracles or third-party smart contracts.
* Attempting phishing or other social engineering attacks against our employees and/or customers.
* Any testing with third-party systems and applications \(e.g. browser extensions\) as well as websites \(e.g. SSO providers, advertising networks\).
* Any denial of service attacks.
* Automated testing of services that generate significant amounts of traffic.

Public disclosure of an unpatched vulnerability in an embargoed bounty situation due to legal constraints not related to [ballena.io](https://ballena.io/).





