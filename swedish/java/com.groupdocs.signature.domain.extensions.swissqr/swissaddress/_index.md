---
title: "SwissAddress"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar adressen för borgenären eller gäldenären."
type: docs
weight: 10
url: /sv/java/com.groupdocs.signature.domain.extensions.swissqr/swissaddress/
---
**Inheritance:**
java.lang.Object
```
public class SwissAddress
```

Representerar adressen för borgenären eller gäldenären.
Du kan antingen ange gata, husnummer, postnummer och ort (strukturerad adresstyp)
eller adressrad 1 och 2 (kombinerad adresselementtyp).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SwissAddress()](#SwissAddress--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getName()](#getName--) | Hämtar eller anger namnet, antingen förnamn och efternamn på en fysisk person eller |
företagsnamnet på en juridisk person.
|
|  | [setName(String value)](#setName-java.lang.String-) | Hämtar eller anger namnet, antingen förnamn och efternamn på en fysisk person eller |
företagsnamnet på en juridisk person.
|
|  | [getAddressLine1()](#getAddressLine1--) | Hämtar eller anger adressrad 1. |
|
|  | [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Hämtar eller anger adressrad 1. |
|
|  | [getAddressLine2()](#getAddressLine2--) | Hämtar eller anger adressrad 2. |
|
|  | [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Hämtar eller anger adressrad 2. |
|
|  | [getStreet()](#getStreet--) | Hämtar eller anger gatan. |
|
|  | [setStreet(String value)](#setStreet-java.lang.String-) | Hämtar eller anger gatan. |
|
|  | [getHouseNo()](#getHouseNo--) | Hämtar eller anger husnumret. |
|
|  | [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Hämtar eller anger husnumret. |
|
|  | [getPostalCode()](#getPostalCode--) | Hämtar eller anger postnumret. |
|
|  | [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Hämtar eller anger postnumret. |
|
|  | [getTown()](#getTown--) | Hämtar eller anger orten eller staden. |
|
|  | [setTown(String value)](#setTown-java.lang.String-) | Hämtar eller anger orten eller staden. |
|
|  | [getCountryCode()](#getCountryCode--) | Hämtar eller anger den tvåbokstaviga ISO-landskoden. |
|
|  | [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Hämtar eller anger den tvåbokstaviga ISO-landskoden. |
|
### SwissAddress() {#SwissAddress--}
```
public SwissAddress()
```


### getName() {#getName--}
```
public final String getName()
```


Hämtar eller anger namnet, antingen förnamn och efternamn på en fysisk person eller
företagsnamnet på en juridisk person.
Värde: Namnet.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Hämtar eller anger namnet, antingen förnamn och efternamn på en fysisk person eller
företagsnamnet på en juridisk person.
Värde: Namnet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getAddressLine1() {#getAddressLine1--}
```
public final String getAddressLine1()
```


Hämtar eller anger adressrad 1.
Adressrad 1 innehåller gatunamn, husnummer eller postbox.
Detta fält används endast för kombinerade elementadresser och är valfritt.
Värde: Adressrad 1.


**Returns:**
java.lang.String
### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public final void setAddressLine1(String value)
```


Hämtar eller anger adressrad 1.
Adressrad 1 innehåller gatunamn, husnummer eller postbox.
Detta fält används endast för kombinerade elementadresser och är valfritt.
Värde: Adressrad 1.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getAddressLine2() {#getAddressLine2--}
```
public final String getAddressLine2()
```


Hämtar eller anger adressrad 2.
Adressrad 2 innehåller postnummer och ort.
Detta fält används endast för kombinerade elementadresser. För denna typ är det obligatoriskt.
Värde: Adressrad 2.


**Returns:**
java.lang.String
### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public final void setAddressLine2(String value)
```


Hämtar eller anger adressrad 2.
Adressrad 2 innehåller postnummer och ort.
Detta fält används endast för kombinerade elementadresser. För denna typ är det obligatoriskt.
Värde: Adressrad 2.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getStreet() {#getStreet--}
```
public final String getStreet()
```


Hämtar eller anger gatan.
Gatan måste anges utan husnummer.
Detta fält används endast för strukturerade adresser och är valfritt.
Värde: Gatan.


**Returns:**
java.lang.String
### setStreet(String value) {#setStreet-java.lang.String-}
```
public final void setStreet(String value)
```


Hämtar eller anger gatan.
Gatan måste anges utan husnummer.
Detta fält används endast för strukturerade adresser och är valfritt.
Värde: Gatan.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getHouseNo() {#getHouseNo--}
```
public final String getHouseNo()
```


Hämtar eller anger husnumret.
Detta fält används endast för strukturerade adresser och är valfritt.
Värde: Husnumret.


**Returns:**
java.lang.String
### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public final void setHouseNo(String value)
```


Hämtar eller anger husnumret.
Detta fält används endast för strukturerade adresser och är valfritt.
Värde: Husnumret.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


Hämtar eller anger postnumret.
Detta fält används endast för strukturerade adresser. För denna typ är det obligatoriskt.
Värde: postnumret.


**Returns:**
java.lang.String
### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


Hämtar eller anger postnumret.
Detta fält används endast för strukturerade adresser. För denna typ är det obligatoriskt.
Värde: postnumret.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getTown() {#getTown--}
```
public final String getTown()
```


Hämtar eller anger orten eller staden.
Detta fält används endast för strukturerade adresser. För denna typ är det obligatoriskt.
Värde: staden eller orten.


**Returns:**
java.lang.String
### setTown(String value) {#setTown-java.lang.String-}
```
public final void setTown(String value)
```


Hämtar eller anger orten eller staden.
Detta fält används endast för strukturerade adresser. För denna typ är det obligatoriskt.
Värde: staden eller orten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


Hämtar eller anger den tvåbokstaviga ISO-landskoden.
Landskoden är obligatorisk om inte hela adressen innehåller null eller tomma värden.
Värde: ISO-landskoden.


**Returns:**
java.lang.String
### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


Hämtar eller anger den tvåbokstaviga ISO-landskoden.
Landskoden är obligatorisk om inte hela adressen innehåller null eller tomma värden.
Värde: ISO-landskoden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

