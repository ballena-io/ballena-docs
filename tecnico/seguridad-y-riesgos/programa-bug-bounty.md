# Programa Bug Bounty

[ballena.io](https://ballena.io/) lanza un programa de bug bounty que remunera hasta en 5.000 dólares y se centra en la búsqueda de vulnerabilidades en los contratos inteligentes y en el código del blockchain.



![](https://cdn-images-1.medium.com/max/800/1*Wb-OXpMQ1E9SbIxANDrFcQ.png)

## **Informar sobre una vulnerabilidad**

Si identificas una posible vulnerabilidad, dirígete a nuestro canal de seguridad en Discord y envía tus hallazgos al equipo de [ballena.io](https://ballena.io/) para que los revisen.

{% embed url="https://discord.com/invite/7dJEAmMX" %}

El equipo de [ballena.io](https://ballena.io/) revisará los bugs reportados mediante un estudio exhaustivo del asunto. En caso de que el bug sea confirmado, el equipo de triage lo notificará a los devs de [ballena.io](https://ballena.io/) para que rectifiquen inmediatamente la vulnerabilidad si así lo consideran.

## **Recompensas por nivel de amenaza**

Las recompensas se distribuyen en función del impacto de la vulnerabilidad, basándose en el [Sistema de Clasificación de la Severidad de la Vulnerabilidad](https://immunefi.com/severity-system/) de **Immunefi**. Se trata de una escala simplificada de 5 niveles, que incluye diferentes escalas para sitios web/aplicaciones y contratos inteligentes/blockchains, teniendo en cuenta la probabilidad de éxito de un exploit y sus consecuencias.

Los pagos son gestionados por el equipo de [ballena.io](https://ballena.io/) directamente y están denominados en **USD**. Los pagos se realizan en tokens **BALLE**.



#### Contratos inteligentes y Blockchain

| Nivel de amenaza | Recompensa |
| :--- | :--- |
| Critical | $5000 |
| High | $1000 |
| Medium | $500 |
| Low | $100 |
| None | $0 |

## Activos en cuestión

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

## Nuestra prioridad

Estamos especialmente interesados en recibir y recompensar vulnerabilidades de los siguientes tipos:

* Smart Contracts y Blockchain.
* Reentrada.
* Errores lógicos incluyendo errores de autenticación de usuarios.
* Detalles de Solidity/EVM no considerados incluyendo:
  * over/under-flow de enteros.
  * errores de redondeo.
  * unhandled exceptions.
* Vulnerabilidades de confianza/dependencia incluyendo vulnerabilidades de composabilidad.
* Fallo/manipulación de Oracle.
* Ataques de gobernanza.
* Ataques económicos/financieros, incluidos los ataques de préstamos flash.
* Congestión y escalabilidad, incluyendo:
  * agotamiento del gas.
  * relleno de bloques.
  * susceptibilidad al frontrunning.
* Fallos de consenso.
* Problemas de criptografía.
* Maleabilidad de firmas.
* Susceptibilidad a los ataques de repetición.
* Aleatoriedad débil.
* Encriptación débil.
* Susceptibilidad a la manipulación de la marca de tiempo del bloque.
* Ausencia de controles de acceso / interfaces internas o de depuración desprotegidas.

## Fuera del alcance y normas

Las siguientes vulnerabilidades están excluidas de las recompensas de este programa de bug bounty:

* Ataques que el informante ha explotado por sí mismo, provocando daños.
* Ataques que requieran acceso a claves/credenciales filtradas.
* Ataques que requieran acceso a direcciones privilegiadas \(gobernanza, estrategia\).

#### **Contratos inteligentes y Blockchain**

* Datos incorrectos suministrados por oráculos de terceros.
* Ataques de manipulación de oráculos/flash loans.
* Ataques básicos a la gobernanza económica \(por ejemplo, un ataque del 51%\).
* Falta de liquidez.
* Críticas a las mejores prácticas.
* Ataques sybil.

Las siguientes **actividades** están **prohibidas** para nuestro programa de bug bounty:

* Cualquier prueba con contratos de la mainnet o de la testnet pública; todas las pruebas deben realizarse en redes de prueba privadas.
* Cualquier prueba con oráculos de precios o contratos inteligentes de terceros.
* Intento de phishing u otros ataques de ingeniería social contra nuestros empleados y/o clientes.
* Cualquier prueba con sistemas y aplicaciones de terceros \(por ejemplo, extensiones del navegador\), así como sitios web \(por ejemplo, proveedores de SSO, redes de publicidad\).
* Cualquier ataque de denegación de servicio.
* Pruebas automatizadas de servicios que generen cantidades significativas de tráfico.
* Divulgación pública de una vulnerabilidad no parcheada en una recompensa embargada.







