---
title: "CryptoCurrencyTransfer"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar mottagare av kryptovalutaöverföring eller överföring för QR‑kod."
type: docs
weight: 11
url: /sv/java/com.groupdocs.signature.domain.extensions.serialization/cryptocurrencytransfer/
---
**Inheritance:**
java.lang.Object
```
public class CryptoCurrencyTransfer
```

Representerar kryptovalutaöverföring (mottagare eller överföring) för QR-kod.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [CryptoCurrencyTransfer()](#CryptoCurrencyTransfer--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getType()](#getType--) | Hämtar eller anger en av de stödjade kryptovalutatyperna. |
|
|  | [setType(int value)](#setType-int-) | Hämtar eller anger en av de stödjade kryptovalutatyperna. |
|
|  | [getAmount()](#getAmount--) | Hämtar eller anger överföringsbelopp. |
|
|  | [setAmount(BigDecimal value)](#setAmount-java.math.BigDecimal-) | Hämtar eller anger överföringsbelopp. |
|
|  | [getAddress()](#getAddress--) | Hämtar eller anger kryptovalutans offentliga adress. |
|
|  | [setAddress(String value)](#setAddress-java.lang.String-) | Hämtar eller anger kryptovalutans offentliga adress. |
|
|  | [getMessage()](#getMessage--) | Hämtar eller anger valfritt överföringsmeddelande. |
|
|  | [setMessage(String value)](#setMessage-java.lang.String-) | Hämtar eller anger valfritt överföringsmeddelande. |
|
|  | [getCustomType()](#getCustomType--) | Hämtar eller anger valfritt överföringsmeddelande. |
|
|  | [setCustomType(String value)](#setCustomType-java.lang.String-) | Hämtar eller anger valfritt överföringsmeddelande. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Skriver över Equals‑metoden för att jämföra egenskaper för kryptovalutaöverföring |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
### CryptoCurrencyTransfer() {#CryptoCurrencyTransfer--}
```
public CryptoCurrencyTransfer()
```


### getType() {#getType--}
```
public final int getType()
```


Hämtar eller anger en av de stödjade kryptovalutatyperna.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Hämtar eller anger en av de stödjade kryptovalutatyperna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getAmount() {#getAmount--}
```
public final BigDecimal getAmount()
```


Hämtar eller anger överföringsbelopp.


**Returns:**
java.math.BigDecimal
### setAmount(BigDecimal value) {#setAmount-java.math.BigDecimal-}
```
public final void setAmount(BigDecimal value)
```


Hämtar eller anger överföringsbelopp.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.math.BigDecimal |  |

### getAddress() {#getAddress--}
```
public final String getAddress()
```


Hämtar eller anger kryptovalutans offentliga adress.


**Returns:**
java.lang.String
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


Hämtar eller anger kryptovalutans offentliga adress.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


Hämtar eller anger valfritt överföringsmeddelande.


**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


Hämtar eller anger valfritt överföringsmeddelande.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getCustomType() {#getCustomType--}
```
public final String getCustomType()
```


Hämtar eller anger valfritt överföringsmeddelande.


**Returns:**
java.lang.String
### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public final void setCustomType(String value)
```


Hämtar eller anger valfritt överföringsmeddelande.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Skriver över Equals‑metoden för att jämföra egenskaper för kryptovalutaöverföring


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | Crypto currency transfer-objekt att jämföra med. |
|

**Returns:**
boolean - Returnerar true om det överförda Crypto currency transfer-objektet har samma typ och alla dess egenskaper är lika med egenskaperna i denna instans.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Åsidosätter GetHashCode‑metoden.


**Returns:**
int - Crypto currency transfer hashkod

