---
title: "CryptoCurrencyTransfer"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt den Empfänger einer Kryptowährungstransaktion oder die Übertragung für einen QR‑Code dar."
type: docs
weight: 11
url: /de/java/com.groupdocs.signature.domain.extensions.serialization/cryptocurrencytransfer/
---
**Inheritance:**
java.lang.Object
```
public class CryptoCurrencyTransfer
```

Stellt eine Kryptowährungsübertragung (Empfänger oder Transfer) für QR-Code dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CryptoCurrencyTransfer()](#CryptoCurrencyTransfer--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getType()](#getType--) | Liest oder setzt einen der unterstützten Kryptowährungstypen. |
|
|  | [setType(int value)](#setType-int-) | Liest oder setzt einen der unterstützten Kryptowährungstypen. |
|
|  | [getAmount()](#getAmount--) | Liest oder setzt den Überweisungsbetrag. |
|
|  | [setAmount(BigDecimal value)](#setAmount-java.math.BigDecimal-) | Liest oder setzt den Überweisungsbetrag. |
|
|  | [getAddress()](#getAddress--) | Liest oder setzt die öffentliche Adresse der Kryptowährung. |
|
|  | [setAddress(String value)](#setAddress-java.lang.String-) | Liest oder setzt die öffentliche Adresse der Kryptowährung. |
|
|  | [getMessage()](#getMessage--) | Liest oder setzt die optionale Überweisungsnachricht. |
|
|  | [setMessage(String value)](#setMessage-java.lang.String-) | Liest oder setzt die optionale Überweisungsnachricht. |
|
|  | [getCustomType()](#getCustomType--) | Liest oder setzt die optionale Überweisungsnachricht. |
|
|  | [setCustomType(String value)](#setCustomType-java.lang.String-) | Liest oder setzt die optionale Überweisungsnachricht. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Überschreibt die Equals‑Methode, um Eigenschaften von Kryptowährungstransfers zu vergleichen |
|
|  | [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
|
### CryptoCurrencyTransfer() {#CryptoCurrencyTransfer--}
```
public CryptoCurrencyTransfer()
```


### getType() {#getType--}
```
public final int getType()
```


Liest oder setzt einen der unterstützten Kryptowährungstypen.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Liest oder setzt einen der unterstützten Kryptowährungstypen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getAmount() {#getAmount--}
```
public final BigDecimal getAmount()
```


Liest oder setzt den Überweisungsbetrag.


**Returns:**
java.math.BigDecimal
### setAmount(BigDecimal value) {#setAmount-java.math.BigDecimal-}
```
public final void setAmount(BigDecimal value)
```


Liest oder setzt den Überweisungsbetrag.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.math.BigDecimal |  |

### getAddress() {#getAddress--}
```
public final String getAddress()
```


Liest oder setzt die öffentliche Adresse der Kryptowährung.


**Returns:**
java.lang.String
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


Liest oder setzt die öffentliche Adresse der Kryptowährung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


Liest oder setzt die optionale Überweisungsnachricht.


**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


Liest oder setzt die optionale Überweisungsnachricht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getCustomType() {#getCustomType--}
```
public final String getCustomType()
```


Liest oder setzt die optionale Überweisungsnachricht.


**Returns:**
java.lang.String
### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public final void setCustomType(String value)
```


Liest oder setzt die optionale Überweisungsnachricht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Überschreibt die Equals‑Methode, um Eigenschaften von Kryptowährungstransfers zu vergleichen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Krypto-Währungsübertragungsobjekt zum Vergleich. |
|

**Returns:**
boolean - Gibt true zurück, wenn das übergebene Krypto‑Währungsübertragungsobjekt denselben Typ hat und alle seine Eigenschaften den Eigenschaften dieser Instanz entsprechen.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Überschreibt die GetHashCode‑Methode


**Returns:**
int - Krypto‑Währungsübertragungs-Hashcode

