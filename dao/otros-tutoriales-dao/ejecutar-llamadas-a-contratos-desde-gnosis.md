# Ejecutar llamadas a contratos desde Gnosis

### 1. **Crear nueva transacción desde el safe que corresponda.**  

![](https://lh5.googleusercontent.com/_MYV2FtTVJ_m0p5b3Of6UFcEkX3DP6jTG4MZ1FgfR2JWbAWZb8ooqh766vxDbnXxlU0bQQ8JjtLhMzTNeFFVV7xGKw8GML9oP9meWWGvPePf-vt3DFMIldWfQgLxN-QJSGtanKNl)

\*\*\*\*

### **2. Seleccionar “Contract Interaction”.**  

![](https://lh6.googleusercontent.com/r1ZemzLSi07ZfYTO4oqKobKFbKfvt1-ylkHM0JKuiy2jg8HvJcO17SdnvESfjw3gE1lTfeLeyC9sdlLIawVCNPlNGWVVjnUZiicucvhT3xiksAHggMKrTyJVpP2SVax_6IAG7H2Z)

### \*\*\*\*

### **3. Introducir la dirección del contrato en “Recipient” y la declaración de la interfaz en ABI.**

El ABI lo podemos obtener en BscScan de la siguiente manera:

Por ejemplo, vamos a convertir BNB en WBNB, esto se hace enviando al contrato de WBNB la cantidad de BNB a convertir y nos devolverá la misma cantidad en WBNB.

Navegando a [https://bscscan.com/address/0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c\#code](https://bscscan.com/address/0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c#code) en la zona inferior de la página encontramos el apartado “Contract ABI” que habrá que copiar y pegar en Gnosis.



![](https://lh4.googleusercontent.com/yFFxY5qDccg_XYPMuGQ4u_ymRXG_fi4ENlgxmOV1DfbAFu1KQWoHtHdcNuTEbCqVo6B7MdqTIsNdrSghX1viDvNLXNAkMv-ZJ8sOc0Flt_qvY2mgaXP3xGdhbWLg4ZAe6vbsWvvC)

### \*\*\*\*

### **4. Seleccionar método del contrato.**

Al tener esos datos aparece un desplegable bajo el campo del ABI que nos permite seleccionar el método del contrato que queremos ejecutar.



![](https://lh5.googleusercontent.com/waAY3tSJATsotRGKhNsZaQi0s0z7yTUHFwyLj6WR2mZgeuS-rCseZgwrWkkoZz-mq9q7RRrhCUTbt1RvcrIrQXzR9c5KyNXwdERPZSs1XrDZ8U5vpaOBMSzKAfS14QWv5kdsA4Lc)



Si el método tiene parámetros, al seleccionarlo, aparecen los campos para introducirlos.

Hay dos tipos de métodos:

* Los de lectura \(read\). Se pueden llamar directamente sin crear una transacción en la blockchain \(no consumen gas\)
* Los de escritura \(write\). Para llamarlos es necesario enviar una transacción a la blockchain que hará que se ejecute y realice la operación correspondiente. Hay que pagar la comisión para dicha transacción. El coste en gas variará en función de la complejidad del código que ejecute ese método o si hace llamadas a más contratos, etc.

Si se selecciona un método de lectura, se activará el botón de “Call” una vez indicados los parámetros.

Si el método es de escritura, tras introducir los parámetros se activará el botón de “Review” que nos lleva a una ventana de confirmación.  
  
****

![](https://lh5.googleusercontent.com/GXNWPOXbp_tKT7Wqdg3SUuT268Bi9Yoxk0aGQxFuzTLn2emI1YfL3eqeWgBN-eIpDbYsd11WClujlV4tb3LzxASZwG8c0SO737GIKpw3Dm_k2cry6Gzrie40sPGLhDX6odMQ1jkV)



![](https://lh4.googleusercontent.com/ihG5L5K1b9YEpyuf-edogkwMc7-1n3LeObkMr_0-eXmnGLTeSugBKlCqNA8pogERJ2OmTezhJ9TZgkXEXZcNbHPSXZrs5Edm47MbfTrPaiGzCFahwn1WWtuJ1-4yz2Keho6n5u_a)

### \*\*\*\*

### **4. Pulsar "Submit".**

Pulsando “Submit” se crea la transacción en cuanto la firmemos con nuestra wallet y quedará pendiente de firma para los demás participantes.  
  
****

![](https://lh5.googleusercontent.com/jp1Mn_pId13KjaUuExiRC0TxUefMnH55KZDO1nfy349YCgV6hc-Fq7d6fb8Ebg-JdPoai4_n7Lef3FGIWGdFcIkkDQMS4Vntx6V9Px5rqxR84FoKt8uzGx_5GqUixUDbhUimPpEx)





