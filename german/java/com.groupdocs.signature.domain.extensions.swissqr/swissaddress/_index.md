---
title: "SwissAddress"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt die Adresse des Gläubigers oder Schuldners dar."
type: docs
weight: 10
url: /de/java/com.groupdocs.signature.domain.extensions.swissqr/swissaddress/
---
**Inheritance:**
java.lang.Object
```
public class SwissAddress
```

Stellt die Adresse des Gläubigers oder Schuldners dar.
Sie können entweder Straße, Hausnummer, Postleitzahl und Ort festlegen (strukturierter Adresstyp)
oder Adresszeile 1 und 2 (kombinierter Adress-Elemente-Typ).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SwissAddress()](#SwissAddress--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getName()](#getName--) | Liest oder setzt den Namen, entweder Vor- und Nachname einer natürlichen Person oder |
den Firmennamen einer juristischen Person.
|
|  | [setName(String value)](#setName-java.lang.String-) | Liest oder setzt den Namen, entweder Vor- und Nachname einer natürlichen Person oder |
den Firmennamen einer juristischen Person.
|
|  | [getAddressLine1()](#getAddressLine1--) | Liest oder setzt die Adresszeile 1. |
|
|  | [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Liest oder setzt die Adresszeile 1. |
|
|  | [getAddressLine2()](#getAddressLine2--) | Liest oder setzt die Adresszeile 2. |
|
|  | [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Liest oder setzt die Adresszeile 2. |
|
|  | [getStreet()](#getStreet--) | Liest oder setzt die Straße. |
|
|  | [setStreet(String value)](#setStreet-java.lang.String-) | Liest oder setzt die Straße. |
|
|  | [getHouseNo()](#getHouseNo--) | Liest oder setzt die Hausnummer. |
|
|  | [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Liest oder setzt die Hausnummer. |
|
|  | [getPostalCode()](#getPostalCode--) | Liest oder setzt die Postleitzahl. |
|
|  | [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Liest oder setzt die Postleitzahl. |
|
|  | [getTown()](#getTown--) | Liest oder setzt den Ort oder die Stadt. |
|
|  | [setTown(String value)](#setTown-java.lang.String-) | Liest oder setzt den Ort oder die Stadt. |
|
|  | [getCountryCode()](#getCountryCode--) | Liest oder setzt den zweibuchstabigen ISO-Ländercode. |
|
|  | [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Liest oder setzt den zweibuchstabigen ISO-Ländercode. |
|
### SwissAddress() {#SwissAddress--}
```
public SwissAddress()
```


### getName() {#getName--}
```
public final String getName()
```


Liest oder setzt den Namen, entweder Vor- und Nachname einer natürlichen Person oder
den Firmennamen einer juristischen Person.
Wert: Der Name.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Liest oder setzt den Namen, entweder Vor- und Nachname einer natürlichen Person oder
den Firmennamen einer juristischen Person.
Wert: Der Name.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getAddressLine1() {#getAddressLine1--}
```
public final String getAddressLine1()
```


Liest oder setzt die Adresszeile 1.
Adresszeile 1 enthält Straßenname, Hausnummer oder Postfach.
Dieses Feld wird nur für kombinierte Elemente-Adressen verwendet und ist optional.
Wert: Die Adresszeile 1.


**Returns:**
java.lang.String
### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public final void setAddressLine1(String value)
```


Liest oder setzt die Adresszeile 1.
Adresszeile 1 enthält Straßenname, Hausnummer oder Postfach.
Dieses Feld wird nur für kombinierte Elemente-Adressen verwendet und ist optional.
Wert: Die Adresszeile 1.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getAddressLine2() {#getAddressLine2--}
```
public final String getAddressLine2()
```


Liest oder setzt die Adresszeile 2.
Adresszeile 2 enthält Postleitzahl und Ort.
Dieses Feld wird nur für kombinierte Elemente-Adressen verwendet. Für diesen Typ ist es obligatorisch.
Wert: Die Adresszeile 2.


**Returns:**
java.lang.String
### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public final void setAddressLine2(String value)
```


Liest oder setzt die Adresszeile 2.
Adresszeile 2 enthält Postleitzahl und Ort.
Dieses Feld wird nur für kombinierte Elemente-Adressen verwendet. Für diesen Typ ist es obligatorisch.
Wert: Die Adresszeile 2.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getStreet() {#getStreet--}
```
public final String getStreet()
```


Liest oder setzt die Straße.
Die Straße muss ohne Hausnummer angegeben werden.
Dieses Feld wird nur für strukturierte Adressen verwendet und ist optional.
Wert: Die Straße.


**Returns:**
java.lang.String
### setStreet(String value) {#setStreet-java.lang.String-}
```
public final void setStreet(String value)
```


Liest oder setzt die Straße.
Die Straße muss ohne Hausnummer angegeben werden.
Dieses Feld wird nur für strukturierte Adressen verwendet und ist optional.
Wert: Die Straße.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getHouseNo() {#getHouseNo--}
```
public final String getHouseNo()
```


Liest oder setzt die Hausnummer.
Dieses Feld wird nur für strukturierte Adressen verwendet und ist optional.
Wert: Die Hausnummer.


**Returns:**
java.lang.String
### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public final void setHouseNo(String value)
```


Liest oder setzt die Hausnummer.
Dieses Feld wird nur für strukturierte Adressen verwendet und ist optional.
Wert: Die Hausnummer.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


Liest oder setzt die Postleitzahl.
Dieses Feld wird nur für strukturierte Adressen verwendet. Für diesen Typ ist es obligatorisch.
Wert: Die Postleitzahl.


**Returns:**
java.lang.String
### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


Liest oder setzt die Postleitzahl.
Dieses Feld wird nur für strukturierte Adressen verwendet. Für diesen Typ ist es obligatorisch.
Wert: Die Postleitzahl.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getTown() {#getTown--}
```
public final String getTown()
```


Liest oder setzt den Ort oder die Stadt.
Dieses Feld wird nur für strukturierte Adressen verwendet. Für diesen Typ ist es obligatorisch.
Wert: Die Stadt oder Gemeinde.


**Returns:**
java.lang.String
### setTown(String value) {#setTown-java.lang.String-}
```
public final void setTown(String value)
```


Liest oder setzt den Ort oder die Stadt.
Dieses Feld wird nur für strukturierte Adressen verwendet. Für diesen Typ ist es obligatorisch.
Wert: Die Stadt oder Gemeinde.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


Liest oder setzt den zweibuchstabigen ISO-Ländercode.
Der Ländercode ist obligatorisch, es sei denn, die gesamte Adresse enthält null- oder leere Werte.
Wert: Der ISO-Ländercode.


**Returns:**
java.lang.String
### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


Liest oder setzt den zweibuchstabigen ISO-Ländercode.
Der Ländercode ist obligatorisch, es sei denn, die gesamte Adresse enthält null- oder leere Werte.
Wert: Der ISO-Ländercode.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

