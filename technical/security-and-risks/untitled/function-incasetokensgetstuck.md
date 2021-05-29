# Function inCaseTokensGetStuck

**Contract Source Code \(Involved lines\)**

```text
function inCaseTokensGetStuck(
    address _token,
    uint256 _amount,
    address _to
) public onlyGovernance {
    require(_to != address(0), "zero address");

    IERC20(_token).safeTransfer(_to, _amount);
}
```

These source code lines can be found at line 90 in the smart contract:

{% embed url="https://bscscan.com/address/0x9714c04b34e6300964161c3ac37b86451e79152d\#code" %}

This function may appear as a security breach for some of the smart contract inspectors, issuing a warning for these few lines due to the ability to get the desired amount of tokens from this address.

{% hint style="success" %}
However, his function doesn´t imply a security risk and should not be targeted as a red warning alert. 
{% endhint %}

This part of the code allows the DAO to get back stuck tokens that were sent by mistake to this contract address. Sometimes, confused users send tokens to this address, which would get stuck forever if it was not for these code lines. This way, the DAO can give the tokens back to this user after the proper creation and voting of the proposal. 

{% hint style="danger" %}
There is no guarantee governance will vote to return these tokens back to the user.
{% endhint %}

The Governance Gnosis Multisig Safe is the one in charge of this operation, meaning a minimum number of 3 signatures out of 5 are needed to perform this transaction.

No other tokens are stored under this contract, so no security implications are present.





