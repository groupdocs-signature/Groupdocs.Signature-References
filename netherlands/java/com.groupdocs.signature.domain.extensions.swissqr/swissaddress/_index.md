---
title: "SwissAddress"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Stelt het adres van de crediteur of schuldenaar voor."
type: docs
weight: 10
url: /nl/java/com.groupdocs.signature.domain.extensions.swissqr/swissaddress/
---
**Inheritance:**
java.lang.Object
```
public class SwissAddress
```

Stelt het adres van de crediteur of schuldenaar voor.
U kunt ofwel straat, huisnummer, postcode en plaats instellen (gestructureerd adrestype).
of adresregel 1 en 2 (type gecombineerde adresselementen).

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SwissAddress()](#SwissAddress--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getName()](#getName--) | Haalt op of stelt de naam in, ofwel de voor- en achternaam van een natuurlijke persoon of |
de bedrijfsnaam van een rechtspersoon.
|
|  | [setName(String value)](#setName-java.lang.String-) | Haalt op of stelt de naam in, ofwel de voor- en achternaam van een natuurlijke persoon of |
de bedrijfsnaam van een rechtspersoon.
|
|  | [getAddressLine1()](#getAddressLine1--) | Haalt op of stelt adresregel 1 in. |
|
|  | [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Haalt op of stelt adresregel 1 in. |
|
|  | [getAddressLine2()](#getAddressLine2--) | Haalt op of stelt adresregel 2 in. |
|
|  | [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Haalt op of stelt adresregel 2 in. |
|
|  | [getStreet()](#getStreet--) | Haalt op of stelt de straat in. |
|
|  | [setStreet(String value)](#setStreet-java.lang.String-) | Haalt op of stelt de straat in. |
|
|  | [getHouseNo()](#getHouseNo--) | Haalt op of stelt het huisnummer in. |
|
|  | [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Haalt op of stelt het huisnummer in. |
|
|  | [getPostalCode()](#getPostalCode--) | Haalt op of stelt de postcode in. |
|
|  | [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Haalt op of stelt de postcode in. |
|
|  | [getTown()](#getTown--) | Haalt op of stelt de plaats of stad in. |
|
|  | [setTown(String value)](#setTown-java.lang.String-) | Haalt op of stelt de plaats of stad in. |
|
|  | [getCountryCode()](#getCountryCode--) | Haalt op of stelt de tweeletterige ISO-landcode in. |
|
|  | [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Haalt op of stelt de tweeletterige ISO-landcode in. |
|
### SwissAddress() {#SwissAddress--}
```
public SwissAddress()
```


### getName() {#getName--}
```
public final String getName()
```


Haalt op of stelt de naam in, ofwel de voor- en achternaam van een natuurlijke persoon of
de bedrijfsnaam van een rechtspersoon.
Waarde: De naam.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Haalt op of stelt de naam in, ofwel de voor- en achternaam van een natuurlijke persoon of
de bedrijfsnaam van een rechtspersoon.
Waarde: De naam.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getAddressLine1() {#getAddressLine1--}
```
public final String getAddressLine1()
```


Haalt op of stelt adresregel 1 in.
Adresregel 1 bevat de straatnaam, het huisnummer of een postbus.
Dit veld wordt alleen gebruikt voor gecombineerde elementenadressen en is optioneel.
Waarde: De adresregel 1.


**Returns:**
java.lang.String
### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public final void setAddressLine1(String value)
```


Haalt op of stelt adresregel 1 in.
Adresregel 1 bevat de straatnaam, het huisnummer of een postbus.
Dit veld wordt alleen gebruikt voor gecombineerde elementenadressen en is optioneel.
Waarde: De adresregel 1.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getAddressLine2() {#getAddressLine2--}
```
public final String getAddressLine2()
```


Haalt op of stelt adresregel 2 in.
Adresregel 2 bevat postcode en plaats.
Dit veld wordt alleen gebruikt voor gecombineerde elementenadressen. Voor dit type is het verplicht.
Waarde: De adresregel 2.


**Returns:**
java.lang.String
### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public final void setAddressLine2(String value)
```


Haalt op of stelt adresregel 2 in.
Adresregel 2 bevat postcode en plaats.
Dit veld wordt alleen gebruikt voor gecombineerde elementenadressen. Voor dit type is het verplicht.
Waarde: De adresregel 2.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getStreet() {#getStreet--}
```
public final String getStreet()
```


Haalt op of stelt de straat in.
De straat moet worden opgegeven zonder huisnummer.
Dit veld wordt alleen gebruikt voor gestructureerde adressen en is optioneel.
Waarde: De straat.


**Returns:**
java.lang.String
### setStreet(String value) {#setStreet-java.lang.String-}
```
public final void setStreet(String value)
```


Haalt op of stelt de straat in.
De straat moet worden opgegeven zonder huisnummer.
Dit veld wordt alleen gebruikt voor gestructureerde adressen en is optioneel.
Waarde: De straat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getHouseNo() {#getHouseNo--}
```
public final String getHouseNo()
```


Haalt op of stelt het huisnummer in.
Dit veld wordt alleen gebruikt voor gestructureerde adressen en is optioneel.
Waarde: Het huisnummer.


**Returns:**
java.lang.String
### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public final void setHouseNo(String value)
```


Haalt op of stelt het huisnummer in.
Dit veld wordt alleen gebruikt voor gestructureerde adressen en is optioneel.
Waarde: Het huisnummer.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


Haalt op of stelt de postcode in.
Dit veld wordt alleen gebruikt voor gestructureerde adressen. Voor dit type is het verplicht.
Waarde: De postcode.


**Returns:**
java.lang.String
### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


Haalt op of stelt de postcode in.
Dit veld wordt alleen gebruikt voor gestructureerde adressen. Voor dit type is het verplicht.
Waarde: De postcode.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getTown() {#getTown--}
```
public final String getTown()
```


Haalt op of stelt de plaats of stad in.
Dit veld wordt alleen gebruikt voor gestructureerde adressen. Voor dit type is het verplicht.
Waarde: De plaats of stad.


**Returns:**
java.lang.String
### setTown(String value) {#setTown-java.lang.String-}
```
public final void setTown(String value)
```


Haalt op of stelt de plaats of stad in.
Dit veld wordt alleen gebruikt voor gestructureerde adressen. Voor dit type is het verplicht.
Waarde: De plaats of stad.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


Haalt op of stelt de tweeletterige ISO-landcode in.
De landcode is verplicht tenzij het volledige adres null- of lege waarden bevat.
Waarde: De ISO-landcode.


**Returns:**
java.lang.String
### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


Haalt op of stelt de tweeletterige ISO-landcode in.
De landcode is verplicht tenzij het volledige adres null- of lege waarden bevat.
Waarde: De ISO-landcode.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

