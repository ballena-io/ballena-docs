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

**VRT-BNB** 

**BTCST-BNB**

**WATCH-BNB**

**TWT-BNB**

**CAKE-BNB**

**ADA-BNB**

**TUSD-BUSD**

**TRX-BNB**

**UNI-BNB**

**LINK-BNB**

## Vaults Format

In the "Vaults" section of the [ballena.io](https://ballena.io/) dapp you will find both the currently active vaults and the retired ones.

Here you will find various filters such as: 

* Active/Inactive vaults filter.
* Only deposited vaults. 
* Sort by: Popular, Liquidity, Multiplier and earnings. 
* Search vaults.

![](../../.gitbook/assets/image%20%2829%29.png)

\*\*\*\*

The vault´s cards are as follows.

![](../../.gitbook/assets/image%20%2832%29.png)

![](../../.gitbook/assets/image%20%2831%29.png)



Here you will find information regarding: 

* **ASSET-ASSET:** Name of the pair or asset. The name of the assets will appear in this field. For example, BALLE-BNB for a compound vault or CAKE for a single vault.
* **PLATFORM:** Platforrm where the Liquidity Pools is at. For example, PancakeSwap.
* **MULT.:** BALLE rewards multiplier, i.e. x1 o x10. Vaults provide rewards in the form of BALLE tokens, which are multiplied by this value to obtain higher rewards.
* **APY**: Annual Percentage Yield. This is the return that you will get from your investment in our platform thanks to the auto-compounding. The APY is explained with more detail later in this document.
* **TVL:** Total Value Locked. Total value deposited in the Vault by all users of the platform.
* **BALLE REWARD**: The rewards in the form of BALLE tokens that you have accumulated and their approximate value in USD.
* **Harvest**: With this button we will harvest the BALLE token rewards.
* **ASSET-ASSET BALANCE**: Current balance in your wallet.
* **Deposit Fee:** This fee is added to the vault and distributed among users. This has been designed to avoid the frontrunning/gamification/mischief of the users thus avoiding the continuous instantaneous entry and exit of the vaults.
* **Last ASSET-ASSET**: Value of the deposited assets.

## APY/APR

By clicking on the APY/APR pop-up button, this card will be shown which gives information about the calculation of annual returns.



![](../../.gitbook/assets/image%20%2830%29.png)

\*\*\*\*

* **Farm APR**: This value is the return that the user will get if the user invests directly in the farm, and not through [ballena.io](https://ballena.io/). This value is the theoretical annual / daily return on your tokens deposited in the farm directly without reinvestment. This value is not effective on our platform since [ballena.io](https://ballena.io/) performs the auto-compounding of your returns. This data is merely informative, displayed simply to understand the value of the APY that is achieved on our platform, see the next point.

{% hint style="info" %}
In the event of investing $1000 as LP tokens in the corresponding assets, these will have grown by 345.48% at the end of the year, having then a capital worth $3,454.8 at the time of withdrawal.
{% endhint %}

* **Farm APY:** This value is the annual/daily return on your tokens deposited in this vault after the auto-compounding. As you can see, the value of the returns you get after auto-reinvestment, compared to the value of not reinvesting these returns is enormous.

{% hint style="info" %}
In the event of investing $1000 as LP tokens in the corresponding assets, these will have grown by 2,615.6% at the end of the year, having then a capital worth $26,156 at the time of withdrawal.
{% endhint %}

* **BALLE APR**: This value is the BALLE token reward that users receive for participating in the platform. These tokens do not have the auto-compounding feature, so we always talk about APR for this concept.

{% hint style="warning" %}
Remember that 3% of the benefits of the platform are distributed among users of the BALLE Staking Pool. In addition to keeping your LP tokens in the vaults to generate returns with automatic reinvestment, if you reinvest your BALLE tokens in the Staking Pool you will obtain much higher returns.
{% endhint %}

* **Total APY:** This value is the estimated total return that we will obtain annually/daily, which comes from the sum of the APY returns of the LP tokens plus the BALLE rewards. As we have seen, LP tokens are automatically reinvested but BALLE tokens are not. This is why it is recommended to participate in the BALLE Staking Pool with these rewards, since the user can turn this APY into much higher returns.

For more information about the APY and APR click on this [link](../../tools-for-the-user/faq.md#4-apr-apy).

{% hint style="danger" %}
Calculated over current rates, this compound interest calculation is performed daily. Rates are estimates provided for your convenience only, and in no way represent guaranteed returns.
{% endhint %}





