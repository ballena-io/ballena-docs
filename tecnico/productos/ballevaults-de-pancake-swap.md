# BalleVaults de PancakeSwap

Las Vaults, o bóvedas, sirven como generadores pasivos de tokens para los usuarios que aportan liquidez a la misma. Los beneficios obtenidos tienen 3 destinos:

* La mayor parte de los beneficios se devuelve a los usuarios de las BalleVaults en forma de LP tokens y BALLE tokens.
* Pagar las tasas \(Gas Fees\) de las operaciones de harvest o recolección de beneficios. Se aplica un 0.1% de tasa para dichas operaciones.
* El resto es distribuido entre los usuarios que hacen staking de BALLE en la [BALLE Reward Pool](https://github.com/ballena-io/ballena-docs/tree/5bd75cc3a48b7c7fd3639459ce78234cc933dd65/productos/link/README.md) o BALLE Staking Pool. Esta tasa de recompensa para los usuarios que participan activamente en la BALLE Staking Pool es del 3% de los beneficios totales de la plataforma. Además, estos usuarios cuentan con más ventajas. Descúbrelas en [Gobernanza](../gobernanza.md).

Además, los usuarios de las BalleVaults recibirán una recompensa de tokens BALLE como se describe [aquí](../tokenomics.md#distribucion-entre-los-usuarios-de-la-plataforma-yield-optimizer-app). Estos tokens podrán ser reinvertidos en la [BALLE Staking Pool](balle-staking-pool.md) para buscar el máximo rendimiento y beneficios.



### BalleVaults Simples

La estrategia realiza farming con un solo token. A continuación se listan las bóvedas activas:

#### CAKE SMART

Cultiva rendimiento con CAKE y recibe CAKE tokens, [Pancake Swap Native token](https://exchange.pancakeswap.finance/#/swap).



### BalleVaults Compuestas

La estrategia realiza farming con dos tokens LP \(Liquidity pool\). Esto se consigue mediante la obtención de tokens CAKE y posterior venta por los LP tokens correspondientes a la hora de su retirada.

Por ejemplo:

#### CAKE-BNB LP

La estrategia realiza farming con tokens CAKE-BNB LP \(Liquidity pool\). Esto se consigue mediante la obtención de tokens CAKE y posterior venta por los LP tokens CAKE-BNB a la hora de su retirada.

## BalleVaults activas

A continuación se listan las bóvedas activas:

**INJ-BNB LP**

**BALBT-BNB LP**

**DOT-BNB LP**

## Formato de las bóvedas

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



Para más información acerca del APY y APR haz click en este [enlace](../../recursos-para-el-usuario/faq.md#4-apr-apy).

{% hint style="danger" %}
Calculado sobre a las tarifas vigentes, este cálculo del interés compuesto se realiza diariamente. Las tarifas son estimaciones que se proporcionan únicamente para tu comodidad, y en ningún caso representan rendimientos garantizados.
{% endhint %}





