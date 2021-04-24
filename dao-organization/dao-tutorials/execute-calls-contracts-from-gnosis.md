# Execute calls contracts from Gnosis

### 1. Create a new transaction from the corresponding safe.  ****

![](https://lh5.googleusercontent.com/_MYV2FtTVJ_m0p5b3Of6UFcEkX3DP6jTG4MZ1FgfR2JWbAWZb8ooqh766vxDbnXxlU0bQQ8JjtLhMzTNeFFVV7xGKw8GML9oP9meWWGvPePf-vt3DFMIldWfQgLxN-QJSGtanKNl)

\*\*\*\*

### **2. Select “Contract Interaction”.**  

![](https://lh6.googleusercontent.com/r1ZemzLSi07ZfYTO4oqKobKFbKfvt1-ylkHM0JKuiy2jg8HvJcO17SdnvESfjw3gE1lTfeLeyC9sdlLIawVCNPlNGWVVjnUZiicucvhT3xiksAHggMKrTyJVpP2SVax_6IAG7H2Z)

### \*\*\*\*

### **3. Enter the contract address in “Recipient” and the interface declaration in ABI.**

The ABI can be obtained from BscScan as follows:

For example, we are going to convert BNB to WBNB. This is done by sending the amount of BNB to be converted to the WBNB contract and it will return the same amount in WBNB to us.

Navigating to [https://bscscan.com/address/0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c\#code](https://bscscan.com/address/0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c#code), at the bottom of the page we find the section "Contract ABI" that must be copied and pasted in Gnosis.



![](https://lh4.googleusercontent.com/yFFxY5qDccg_XYPMuGQ4u_ymRXG_fi4ENlgxmOV1DfbAFu1KQWoHtHdcNuTEbCqVo6B7MdqTIsNdrSghX1viDvNLXNAkMv-ZJ8sOc0Flt_qvY2mgaXP3xGdhbWLg4ZAe6vbsWvvC)

### \*\*\*\*

### **4.** Select contract method.

Having these data, a drop-down appears under the ABI field that allows us to select the method of the contract that we want to execute.



![](https://lh5.googleusercontent.com/waAY3tSJATsotRGKhNsZaQi0s0z7yTUHFwyLj6WR2mZgeuS-rCseZgwrWkkoZz-mq9q7RRrhCUTbt1RvcrIrQXzR9c5KyNXwdERPZSs1XrDZ8U5vpaOBMSzKAfS14QWv5kdsA4Lc)



If the method has parameters, they will be displayed when select the method.





There are two types of methods:

* Reading methods \(read\). They can be called directly without creating a transaction on the blockchain \(they do not consume gas\)
* Writing methods\(write\). To call them, it is necessary to send a transaction to the blockchain that will make it execute and perform the corresponding operation. You have to pay the commission for that transaction. The cost in gas will vary depending on the complexity of the code that executes that method or if it calls more contracts, etc.

If a reading method is selected, the “Call” button will be activated once the parameters have been indicated. 

If the method is writing, after entering the parameters, the “Review” button will be activated, which will take us to a confirmation window.



![](https://lh5.googleusercontent.com/GXNWPOXbp_tKT7Wqdg3SUuT268Bi9Yoxk0aGQxFuzTLn2emI1YfL3eqeWgBN-eIpDbYsd11WClujlV4tb3LzxASZwG8c0SO737GIKpw3Dm_k2cry6Gzrie40sPGLhDX6odMQ1jkV)



![](https://lh4.googleusercontent.com/ihG5L5K1b9YEpyuf-edogkwMc7-1n3LeObkMr_0-eXmnGLTeSugBKlCqNA8pogERJ2OmTezhJ9TZgkXEXZcNbHPSXZrs5Edm47MbfTrPaiGzCFahwn1WWtuJ1-4yz2Keho6n5u_a)

### \*\*\*\*

### **4. Click on "Submit".**

Pressing "Submit", the transaction is created as soon as we sign it with our wallet and it will change to a pending status for the other participants.



![](https://lh5.googleusercontent.com/jp1Mn_pId13KjaUuExiRC0TxUefMnH55KZDO1nfy349YCgV6hc-Fq7d6fb8Ebg-JdPoai4_n7Lef3FGIWGdFcIkkDQMS4Vntx6V9Px5rqxR84FoKt8uzGx_5GqUixUDbhUimPpEx)





