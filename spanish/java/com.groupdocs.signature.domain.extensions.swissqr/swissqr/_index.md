---
title: "SwissQR"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Clase para codificar y decodificar el texto incrustado en el código SwissQR."
type: docs
weight: 11
url: /es/java/com.groupdocs.signature.domain.extensions.swissqr/swissqr/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class SwissQR implements IComplexData
```

Clase para codificar y decodificar el texto incrustado en el código SwissQR.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [SwissQR()](#SwissQR--) | Crea una instancia de SwissQR. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getAmount()](#getAmount--) | Obtiene o establece el monto del pago. |
|
|  | [setAmount(double value)](#setAmount-double-) | Obtiene o establece el monto del pago. |
|
|  | [getCurrency()](#getCurrency--) | Obtiene o establece la moneda del pago. |
|
|  | [setCurrency(String value)](#setCurrency-java.lang.String-) | Obtiene o establece la moneda del pago. |
|
|  | [getAccount()](#getAccount--) | Obtiene o establece el número de cuenta del acreedor. |
|
|  | [setAccount(String value)](#setAccount-java.lang.String-) | Obtiene o establece el número de cuenta del acreedor. |
|
|  | [getCreditor()](#getCreditor--) | Obtiene o establece la dirección del acreedor. |
|
|  | [setCreditor(SwissAddress value)](#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Obtiene o establece la dirección del acreedor. |
|
|  | [getReference()](#getReference--) | Obtiene o establece la referencia de pago del acreedor. |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | Obtiene o establece la referencia de pago del acreedor. |
|
|  | [getDebtor()](#getDebtor--) | Obtiene o establece la dirección del deudor. |
|
|  | [setDebtor(SwissAddress value)](#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Obtiene o establece la dirección del deudor. |
|
|  | [getUnstructuredMessage()](#getUnstructuredMessage--) | Obtiene o establece el mensaje no estructurado adicional. |
|
|  | [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Obtiene o establece el mensaje no estructurado adicional. |
|
|  | [getBillInformation()](#getBillInformation--) | Obtiene o establece la información de factura estructurada adicional. |
|
|  | [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Obtiene o establece la información de factura estructurada adicional. |
|
### SwissQR() {#SwissQR--}
```
public SwissQR()
```


Crea una instancia de SwissQR.


### getAmount() {#getAmount--}
```
public final double getAmount()
```


Obtiene o establece el monto del pago.
Los valores válidos están entre 0.01 y 999,999,999.99.
Valor: El monto del pago.


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Obtiene o establece el monto del pago.
Los valores válidos están entre 0.01 y 999,999,999.99.
Valor: El monto del pago.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getCurrency() {#getCurrency--}
```
public final String getCurrency()
```


Obtiene o establece la moneda del pago.
Los valores válidos son "CHF" y "EUR".
Valor: La moneda de pago.


**Returns:**
java.lang.String
### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public final void setCurrency(String value)
```


Obtiene o establece la moneda del pago.
Los valores válidos son "CHF" y "EUR".
Valor: La moneda de pago.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getAccount() {#getAccount--}
```
public final String getAccount()
```


Obtiene o establece el número de cuenta del acreedor.
Los números de cuenta deben ser IBAN válidos de un banco de Suiza o Liechtenstein.
Se permiten espacios en el número de cuenta.
Valor: El número de cuenta del acreedor.


**Returns:**
java.lang.String
### setAccount(String value) {#setAccount-java.lang.String-}
```
public final void setAccount(String value)
```


Obtiene o establece el número de cuenta del acreedor.
Los números de cuenta deben ser IBAN válidos de un banco de Suiza o Liechtenstein.
Se permiten espacios en el número de cuenta.
Valor: El número de cuenta del acreedor.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getCreditor() {#getCreditor--}
```
public final SwissAddress getCreditor()
```


Obtiene o establece la dirección del acreedor.
Valor: La dirección del acreedor.


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setCreditor(SwissAddress value) {#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setCreditor(SwissAddress value)
```


Obtiene o establece la dirección del acreedor.
Valor: La dirección del acreedor.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Obtiene o establece la referencia de pago del acreedor.
La referencia es obligatoria para los IBAN SwissQR, es decir, IBAN en el rango CHxx30000xxxxxx
hasta CHxx31999xxxxx.
Si se especifica, la referencia debe ser una referencia SwissQR válida (correspondiente
al formulario de referencia ISR) o una referencia de acreedor válida según ISO 11649 (\"RFxxxx\").
Ambas pueden contener espacios para el formato.
Valor: La referencia de pago del acreedor.


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Obtiene o establece la referencia de pago del acreedor.
La referencia es obligatoria para los IBAN SwissQR, es decir, IBAN en el rango CHxx30000xxxxxx
hasta CHxx31999xxxxx.
Si se especifica, la referencia debe ser una referencia SwissQR válida (correspondiente
al formulario de referencia ISR) o una referencia de acreedor válida según ISO 11649 (\"RFxxxx\").
Ambas pueden contener espacios para el formato.
Valor: La referencia de pago del acreedor.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getDebtor() {#getDebtor--}
```
public final SwissAddress getDebtor()
```


Obtiene o establece la dirección del deudor.
El deudor es opcional. Si se omite, tanto establecer este campo a null como
establecer una dirección con todos los valores null o vacíos está bien.
Valor: La dirección del deudor.


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setDebtor(SwissAddress value) {#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setDebtor(SwissAddress value)
```


Obtiene o establece la dirección del deudor.
El deudor es opcional. Si se omite, tanto establecer este campo a null como
establecer una dirección con todos los valores null o vacíos está bien.
Valor: La dirección del deudor.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public final String getUnstructuredMessage()
```


Obtiene o establece el mensaje no estructurado adicional.
Valor: El mensaje no estructurado.


**Returns:**
java.lang.String
### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public final void setUnstructuredMessage(String value)
```


Obtiene o establece el mensaje no estructurado adicional.
Valor: El mensaje no estructurado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getBillInformation() {#getBillInformation--}
```
public final String getBillInformation()
```


Obtiene o establece la información de factura estructurada adicional.
Valor: La información de factura estructurada.


**Returns:**
java.lang.String
### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public final void setBillInformation(String value)
```


Obtiene o establece la información de factura estructurada adicional.
Valor: La información de factura estructurada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

