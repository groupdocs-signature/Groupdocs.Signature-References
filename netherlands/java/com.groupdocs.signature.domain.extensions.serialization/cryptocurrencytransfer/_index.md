---
title: "CryptoCurrencyTransfer"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Stelt de ontvanger van een cryptovaluta-overdracht of een overdracht voor QR-code voor."
type: docs
weight: 11
url: /nl/java/com.groupdocs.signature.domain.extensions.serialization/cryptocurrencytransfer/
---
**Inheritance:**
java.lang.Object
```
public class CryptoCurrencyTransfer
```

Stelt een cryptovaluta‑overdracht (ontvanger of overdracht) voor voor QR‑Code.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CryptoCurrencyTransfer()](#CryptoCurrencyTransfer--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getType()](#getType--) | Haalt op of stelt een van de ondersteunde cryptovaluta-types in. |
|
|  | [setType(int value)](#setType-int-) | Haalt op of stelt een van de ondersteunde cryptovaluta-types in. |
|
|  | [getAmount()](#getAmount--) | Haalt op of stelt het overdrachtsbedrag in. |
|
|  | [setAmount(BigDecimal value)](#setAmount-java.math.BigDecimal-) | Haalt op of stelt het overdrachtsbedrag in. |
|
|  | [getAddress()](#getAddress--) | Haalt op of stelt het openbare cryptovaluta-adres in. |
|
|  | [setAddress(String value)](#setAddress-java.lang.String-) | Haalt op of stelt het openbare cryptovaluta-adres in. |
|
|  | [getMessage()](#getMessage--) | Haalt op of stelt een optioneel overdrachtsbericht in. |
|
|  | [setMessage(String value)](#setMessage-java.lang.String-) | Haalt op of stelt een optioneel overdrachtsbericht in. |
|
|  | [getCustomType()](#getCustomType--) | Haalt op of stelt een optioneel overdrachtsbericht in. |
|
|  | [setCustomType(String value)](#setCustomType-java.lang.String-) | Haalt op of stelt een optioneel overdrachtsbericht in. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om cryptovaluta-overdrachts-eigenschappen te vergelijken |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
### CryptoCurrencyTransfer() {#CryptoCurrencyTransfer--}
```
public CryptoCurrencyTransfer()
```


### getType() {#getType--}
```
public final int getType()
```


Haalt op of stelt een van de ondersteunde cryptovaluta-types in.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Haalt op of stelt een van de ondersteunde cryptovaluta-types in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getAmount() {#getAmount--}
```
public final BigDecimal getAmount()
```


Haalt op of stelt het overdrachtsbedrag in.


**Returns:**
java.math.BigDecimal
### setAmount(BigDecimal value) {#setAmount-java.math.BigDecimal-}
```
public final void setAmount(BigDecimal value)
```


Haalt op of stelt het overdrachtsbedrag in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.math.BigDecimal |  |

### getAddress() {#getAddress--}
```
public final String getAddress()
```


Haalt op of stelt het openbare cryptovaluta-adres in.


**Returns:**
java.lang.String
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


Haalt op of stelt het openbare cryptovaluta-adres in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


Haalt op of stelt een optioneel overdrachtsbericht in.


**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


Haalt op of stelt een optioneel overdrachtsbericht in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getCustomType() {#getCustomType--}
```
public final String getCustomType()
```


Haalt op of stelt een optioneel overdrachtsbericht in.


**Returns:**
java.lang.String
### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public final void setCustomType(String value)
```


Haalt op of stelt een optioneel overdrachtsbericht in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Overschrijft de Equals-methode om cryptovaluta-overdrachts-eigenschappen te vergelijken


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | obj | java.lang.Object | Crypto currency transfer object om mee te vergelijken. |
|

**Returns:**
boolean - Retourneert true als het meegegeven Crypto currency transfer object hetzelfde type heeft en al zijn eigenschappen gelijk zijn aan de eigenschappen van deze instantie.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Overschrijft de GetHashCode‑methode


**Returns:**
int - Crypto currency transfer hashcode

