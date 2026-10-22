---
title: "CryptoCurrencyTransfer"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt den Empfänger einer Kryptowährungsüberweisung oder die Überweisung für QR-Code dar."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/cryptocurrencytransfer/
---
**Inheritance:**
java.lang.Object
```
public class CryptoCurrencyTransfer
```

Stellt eine Kryptowährungstransaktion (Empfänger oder Übertragung) für QR-Code dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CryptoCurrencyTransfer()](#CryptoCurrencyTransfer--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Liest oder legt einen der unterstützten Kryptowährungstypen fest. |
| [setType(int value)](#setType-int-) | Liest oder legt einen der unterstützten Kryptowährungstypen fest. |
| [getAmount()](#getAmount--) | Liest oder legt den Überweisungsbetrag fest. |
| [setAmount(BigDecimal value)](#setAmount-java.math.BigDecimal-) | Liest oder legt den Überweisungsbetrag fest. |
| [getAddress()](#getAddress--) | Liest oder legt die öffentliche Adresse der Kryptowährung fest. |
| [setAddress(String value)](#setAddress-java.lang.String-) | Liest oder legt die öffentliche Adresse der Kryptowährung fest. |
| [getMessage()](#getMessage--) | Liest oder legt eine optionale Überweisungsnachricht fest. |
| [setMessage(String value)](#setMessage-java.lang.String-) | Liest oder legt eine optionale Überweisungsnachricht fest. |
| [getCustomType()](#getCustomType--) | Liest oder legt eine optionale Überweisungsnachricht fest. |
| [setCustomType(String value)](#setCustomType-java.lang.String-) | Liest oder legt eine optionale Überweisungsnachricht fest. |
| [equals(Object obj)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode, um Eigenschaften von Kryptowährungsüberweisungen zu vergleichen. |
| [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
### CryptoCurrencyTransfer() {#CryptoCurrencyTransfer--}
```
public CryptoCurrencyTransfer()
```


### getType() {#getType--}
```
public final int getType()
```


Liest oder legt einen der unterstützten Kryptowährungstypen fest.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Liest oder legt einen der unterstützten Kryptowährungstypen fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getAmount() {#getAmount--}
```
public final BigDecimal getAmount()
```


Liest oder legt den Überweisungsbetrag fest.

**Returns:**
java.math.BigDecimal
### setAmount(BigDecimal value) {#setAmount-java.math.BigDecimal-}
```
public final void setAmount(BigDecimal value)
```


Liest oder legt den Überweisungsbetrag fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.math.BigDecimal |  |

### getAddress() {#getAddress--}
```
public final String getAddress()
```


Liest oder legt die öffentliche Adresse der Kryptowährung fest.

**Returns:**
java.lang.String
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


Liest oder legt die öffentliche Adresse der Kryptowährung fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


Liest oder legt eine optionale Überweisungsnachricht fest.

**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


Liest oder legt eine optionale Überweisungsnachricht fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getCustomType() {#getCustomType--}
```
public final String getCustomType()
```


Liest oder legt eine optionale Überweisungsnachricht fest.

**Returns:**
java.lang.String
### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public final void setCustomType(String value)
```


Liest oder legt eine optionale Überweisungsnachricht fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Überschreibt die Equals-Methode, um Eigenschaften von Kryptowährungsüberweisungen zu vergleichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Kryptowährungsüberweisungsobjekt zum Vergleichen. |

**Returns:**
boolean - Gibt true zurück, wenn das übergebene Kryptowährungsüberweisungsobjekt denselben Typ hat und alle seine Eigenschaften mit den Eigenschaften dieser Instanz übereinstimmen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Überschreibt die GetHashCode‑Methode

**Returns:**
int - Kryptowährungsüberweisungs-Hashcode
