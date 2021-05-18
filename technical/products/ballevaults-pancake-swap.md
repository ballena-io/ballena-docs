# BalleVaults - Pancake Swap

Vaults serve as passive token generator for users who provide liquidity to them. The farmed revenue has 3 destinations:

* Part of the revenue is returned to the BalleVaults´ users as LP tokens and BALLE tokens.
* Pay the gas fees of harvest calls \(0.1% fee is applied for each call\).
* The rest is distributed to users who stake BALLE in the [BALLE Reward Pool](balle-staking-pool.md). This reward fee is a 3% of the total revenue of the platform. These users are also able to participate in the voting process of the community, discover more in [Governance](../governance.md).



The BalleVaults´ users will receive a reward in the form of BALLE tokens as stated [here](../tokenomics.md#platform-users-distribution-yield-optimizer-app). These tokens can be reinvested in the BALLE Staking Pool for further yield and benefits.



### Single Mode BalleVaults

This strategy farms one only token. You can see currently active vaults listed here:

#### CAKE SMART

Farm yield with the token CAKE and receive more CAKE, the [Pancake Swap Native token](https://exchange.pancakeswap.finance/#/swap).



### Compound BalleVaults

This strategy farms two assets´ LP tokens. This is obtained through the gain of CAKE tokens for its subsequent swap for the corresponding LP tokens at its harvest time.

For example:

#### CAKE-BNB LP

This strategy farms CAKE-BNB LP tokens. This is obtained through the gain of CAKE tokens for its subsequent swap for the CAKE-BNB LP tokens at its harvest time.



## Active BalleVaults

You can see the active vaults listed here:

**INJ-BNB LP**

**BALBT-BNB LP**

**DOT-BNB LP**

\*\*\*\*

## Vaults Format

In the "Vaults" section of the dapp of ballena.io you will find both the currently active Vaults and the retired ones.

En el apartado "Vaults" de la Dapp de [ballena.io](https://ballena.io/) encontrarás tanto las Vaults activas actualmente como las retiradas.

Aquí encontrarás varios filtros como:

* La división entre activas y inactivas.
* Solo depositadas.
* Ordenar por: Popular, Liquidez, Multiplicador y ganancias.
* Buscar bóvedas.



![](../../.gitbook/assets/image%20%2827%29.png)

\*\*\*\*

Las tarjetas de las bóvedas, o vaults, son de la siguiente forma. 



![](../../.gitbook/assets/image%20%2822%29.png)

![](../../.gitbook/assets/image%20%2821%29.png)



Aquí encontrarás información acerca de:

* **ASSET-ASSET:** Nombre del par o asset. En este campo aparecerá el nombre de los assets en cuestión. Por ejemplo, BALLE-BNB para una vault compuesta o CAKE para una vault simple.
* **PLATAFORMA:** Plataforma donde se encuentra la pool de liquidez. Por ejemplo, PancakeSwap.
* **MULT.:** Multiplicador Rewards BALLE, por ejemplo, x1 o x10. Las vaults proporcionan rewards en forma de tokens BALLE, los cuales se multiplican por este valor para obtener recompensas mayores. 
* **APY**: Annual Percentage Yield. Este es el porcentaje de retorno que obtendrás de tu inversión en nuestra plataforma gracias al auto-compounding, la reinversión automática. Más adelante se muestra el APY con más detalle.
* **TVL:** Valor total depositado en la Vault por todos los usuarios de la plataforma.
* **BALLE RECOMPENSA**: Las recompensas en forma de tokens BALLE que tienes acumuladas y su valor aproximado en USD.
* **Cosechar**: Con este botón cosecharemos las recompensas de tokens BALLE.
* **ASSET-ASSET SALDO**: Saldo actual de los assets en tu wallet.
* **Tasa de depósito:** Esta tasa se acumula en la vault y se reparte entre los usuarios. Esta se ha diseñado para evitar el frontrunning/gamificación/picardía de los usuarios y evitar así la continua entrada y salida instantánea de las vaults.
* **1 x ASSET-ASSET**: Valor de cada token de los assets depositados.

## APY/APR

Al hacer click en el botón pop-up del APY, nos aparecerá esta tarjeta acerca del cálculo de los retornos anuales.

![](../../.gitbook/assets/image%20%2828%29.png)

\*\*\*\*

* **APR en Granja**: En el caso de invertir directamente en la granja en cuestión, y no a través de 

  [ballena.io](https://ballena.io/), es el retorno que generaría nuestra inversión. Este valor es el retorno teórico anual/diario sobre tus tokens depositados en la granja directamente sin reinversión.   
  Este valor no es efectivo en nuestra plataforma ya que [ballena.io](https://ballena.io/) realiza el auto-compounding, reinversión, de tus retornos. Este dato es meramente informativo para entender el valor del APY que se consigue en nuestra plataforma, ver el siguiente punto.

{% hint style="info" %}
En el caso de invertir 1000$ como LP tokens en los assets correspondientes, estos habrán crecido un 345.48% a final de año, teniendo ahora un capital de 3.454,8$ a la hora de la retirada.
{% endhint %}

\*\*\*\*

* **APY en Granja:** Este valor es el retorno anual/diario sobre tus tokens depositados en esta bóveda tras la reinversión instantánea de tus retornos. Este es el punto fuerte de la plataforma. Como ves, el valor de los retornos que obtienes tras la reinversión, en comparativa con el valor al no reinvertir estos retornos es abismal. 

{% hint style="info" %}
En el caso de invertir 1000$ como LP tokens en los assets correspondientes, estos habrán crecido un 2,615.6% a final de año, teniendo ahora un capital de 26.156$ a la hora de la retirada.
{% endhint %}

\*\*\*\*

* **APR en BALLE**: Este valor es la recompensa de tokens BALLE que reciben los usuarios por participar en la plataforma. Estos tokens no tienen auto-compounding, con lo que hablamos siempre de APR para este concepto. 

{% hint style="warning" %}
Recuerda que el 3% de los beneficios de la plataforma se destinan a los usuarios de la BALLE Staking Pool. Además de mantener tus LP tokens en las vaults para generar retornos con reinversión automática, si reinviertes tus tokens BALLE en la misma obtendrás retornos mucho mayores.
{% endhint %}

\*\*\*\*

* **APY Total:** Este valor es el retorno total estimado que obtendremos anual/diariamente, el cual proviene de la suma de los retornos de APY de los LP tokens más las recompensas de BALLE. Como hemos visto, los LP tokens se reinvierten automáticamente pero los BALLE tokens en cambio, no.  Al participar únicamente en las vaults, el valor total del APY se ve ampliamente más beneficiado y afectado por los retornos de los LP que por las recompensas de BALLE. Es por esto que se recomienda participar en la BALLE Staking Pool con estas recompensas, ya que el usuario puede convertir este APY en retornos muchísimo mayores.



Para más información acerca del APY y APR haz click en este [enlace](../../tools-for-the-user/faq.md#4-apr-apy).

{% hint style="danger" %}
Calculado sobre a las tarifas vigentes, este cálculo del interés compuesto se realiza diariamente. Las tarifas son estimaciones que se proporcionan únicamente para tu comodidad, y en ningún caso representan rendimientos garantizados.
{% endhint %}







