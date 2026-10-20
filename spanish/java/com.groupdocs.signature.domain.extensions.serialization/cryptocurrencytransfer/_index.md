---
title: "TransferenciaCriptomoneda"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa el receptor o la transferencia de criptomoneda para código QR."
type: docs
weight: 11
url: /es/java/com.groupdocs.signature.domain.extensions.serialization/cryptocurrencytransfer/
---
**Inheritance:**
java.lang.Object
```
public class CryptoCurrencyTransfer
```

Representa la transferencia de criptomoneda (receptor o transferencia) para QR-Code.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [CryptoCurrencyTransfer()](#CryptoCurrencyTransfer--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getType()](#getType--) | Obtiene o establece uno de los tipos de criptomoneda compatibles. |
|
|  | [setType(int value)](#setType-int-) | Obtiene o establece uno de los tipos de criptomoneda compatibles. |
|
|  | [getAmount()](#getAmount--) | Obtiene o establece la cantidad de la transferencia. |
|
|  | [setAmount(BigDecimal value)](#setAmount-java.math.BigDecimal-) | Obtiene o establece la cantidad de la transferencia. |
|
|  | [getAddress()](#getAddress--) | Obtiene o establece la dirección pública de la criptomoneda. |
|
|  | [setAddress(String value)](#setAddress-java.lang.String-) | Obtiene o establece la dirección pública de la criptomoneda. |
|
|  | [getMessage()](#getMessage--) | Obtiene o establece el mensaje opcional de la transferencia. |
|
|  | [setMessage(String value)](#setMessage-java.lang.String-) | Obtiene o establece el mensaje opcional de la transferencia. |
|
|  | [getCustomType()](#getCustomType--) | Obtiene o establece el mensaje opcional de la transferencia. |
|
|  | [setCustomType(String value)](#setCustomType-java.lang.String-) | Obtiene o establece el mensaje opcional de la transferencia. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Sobrescribe el método Equals para comparar las propiedades de la transferencia de criptomoneda |
|
|  | [hashCode()](#hashCode--) | Sobrescribe el método GetHashCode |
|
### CryptoCurrencyTransfer() {#CryptoCurrencyTransfer--}
```
public CryptoCurrencyTransfer()
```


### getType() {#getType--}
```
public final int getType()
```


Obtiene o establece uno de los tipos de criptomoneda compatibles.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Obtiene o establece uno de los tipos de criptomoneda compatibles.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getAmount() {#getAmount--}
```
public final BigDecimal getAmount()
```


Obtiene o establece la cantidad de la transferencia.


**Returns:**
java.math.BigDecimal
### setAmount(BigDecimal value) {#setAmount-java.math.BigDecimal-}
```
public final void setAmount(BigDecimal value)
```


Obtiene o establece la cantidad de la transferencia.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.math.BigDecimal |  |

### getAddress() {#getAddress--}
```
public final String getAddress()
```


Obtiene o establece la dirección pública de la criptomoneda.


**Returns:**
java.lang.String
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


Obtiene o establece la dirección pública de la criptomoneda.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


Obtiene o establece el mensaje opcional de la transferencia.


**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


Obtiene o establece el mensaje opcional de la transferencia.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getCustomType() {#getCustomType--}
```
public final String getCustomType()
```


Obtiene o establece el mensaje opcional de la transferencia.


**Returns:**
java.lang.String
### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public final void setCustomType(String value)
```


Obtiene o establece el mensaje opcional de la transferencia.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Sobrescribe el método Equals para comparar las propiedades de la transferencia de criptomoneda


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | Objeto de transferencia de criptomoneda con el que comparar. |
|

**Returns:**
boolean - Devuelve true si el objeto de transferencia de criptomoneda pasado tiene el mismo tipo y todas sus propiedades son iguales a las propiedades de esta instancia.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Sobrescribe el método GetHashCode


**Returns:**
int - Código hash de la transferencia de criptomoneda

