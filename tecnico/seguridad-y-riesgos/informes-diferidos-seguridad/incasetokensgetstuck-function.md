# Función inCaseTokensGetStuck

**Código fuente del contrato \(líneas involucradas\)**

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

Estas líneas de código fuente se pueden encontrar en la línea 90 del contrato inteligente:

{% embed url="https://bscscan.com/address/0x9714c04b34e6300964161c3ac37b86451e79152d\#code" %}

Esta función puede parecer una brecha de seguridad para algunos de los inspectores de contratos inteligentes, emitiendo una advertencia para estas líneas debido a la capacidad de obtener la cantidad deseada de tokens de esta dirección.

{% hint style="success" %}
Sin embargo, esta función no implica un riesgo de seguridad y no debería constatar como una alerta de advertencia roja.
{% endhint %}

Esta parte del código permite a la DAO recuperar tokens atascados que se enviaron por error a esta dirección de contrato. A veces, los usuarios confusos envían tokens a esta dirección, tokens que quedarían atascados para siempre si no fuera por estas líneas de código. De esta manera, la DAO puede devolver los tokens a este usuario después del proceso de creación y votación de la propuesta correspondiente.

{% hint style="danger" %}
No hay garantía de que la gobernanza vote a favor de devolver estos tokens al usuario.
{% endhint %}

El Safe Gnosis multi-firma de Gobernanza es el encargado de esta operación, lo que significa que se necesita un número mínimo de 3 firmas de 5 para realizar esta transacción. 

No se almacenan otros tokens bajo este contrato, por lo que no existen implicaciones de seguridad.





