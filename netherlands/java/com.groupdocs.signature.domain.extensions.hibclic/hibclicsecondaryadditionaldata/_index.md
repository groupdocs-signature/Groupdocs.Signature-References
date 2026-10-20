---
title: "HIBCLICSecondaryAdditionalData"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Klasse voor het opslaan van HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code secundaire en aanvullende gegevens."
type: docs
weight: 13
url: /nl/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICSecondaryAdditionalData implements IComplexData
```

Klasse voor het opslaan van HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) secundaire en aanvullende gegevens.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [HIBCLICSecondaryAdditionalData()](#HIBCLICSecondaryAdditionalData--) | Standaard ctor() |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getExpiryDateFormat()](#getExpiryDateFormat--) | Identificeert het vervaldatumformaat. |
|
|  | [setExpiryDateFormat(int value)](#setExpiryDateFormat-int-) | Identificeert het vervaldatumformaat. |
|
|  | [getExpiryDate()](#getExpiryDate--) | Identificeert de vervaldatum. |
|
|  | [setExpiryDate(Date value)](#setExpiryDate-java.util.Date-) | Identificeert de vervaldatum. |
|
|  | [getLotNumber()](#getLotNumber--) | Identificeert lot- of batchnummer. |
|
|  | [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Identificeert lot- of batchnummer. |
|
|  | [getSerialNumber()](#getSerialNumber--) | Identificeert serienummer. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Identificeert serienummer. |
|
|  | [getDateOfManufacture()](#getDateOfManufacture--) | Identificeert productiedatum. |
|
|  | [setDateOfManufacture(Date value)](#setDateOfManufacture-java.util.Date-) | Identificeert productiedatum. |
|
|  | [getQuantity()](#getQuantity--) | Identificeert hoeveelheid, moet een geheel getal zijn van 0 tot 500. |
|
|  | [setQuantity(int value)](#setQuantity-int-) | Identificeert hoeveelheid, moet een geheel getal zijn van 0 tot 500. |
|
|  | [getLinkCharacter()](#getLinkCharacter--) | Identificeert koppelingskarakter in de uitvoerreeks. |
|
|  | [setLinkCharacter(char value)](#setLinkCharacter-char-) | Identificeert koppelingskarakter in de uitvoerreeks. |
|
|  | [deepClone()](#deepClone--) | Krijgt een kopie van dit object. |
|
### HIBCLICSecondaryAdditionalData() {#HIBCLICSecondaryAdditionalData--}
```
public HIBCLICSecondaryAdditionalData()
```


Standaard ctor()


### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public final int getExpiryDateFormat()
```


Identificeert het vervaldatumformaat.


**Returns:**
int
### setExpiryDateFormat(int value) {#setExpiryDateFormat-int-}
```
public final void setExpiryDateFormat(int value)
```


Identificeert het vervaldatumformaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getExpiryDate() {#getExpiryDate--}
```
public final Date getExpiryDate()
```


Identificeert vervaldatum. Wordt gebruikt als ExpiryDateFormat niet op None is ingesteld.


**Returns:**
java.util.Date
### setExpiryDate(Date value) {#setExpiryDate-java.util.Date-}
```
public final void setExpiryDate(Date value)
```


Identificeert vervaldatum. Wordt gebruikt als ExpiryDateFormat niet op None is ingesteld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Date |  |

### getLotNumber() {#getLotNumber--}
```
public final String getLotNumber()
```


Identificeert lot- of batchnummer.
Lot-/batchnummer moet een alfanumerieke tekenreeks zijn met een maximale lengte van 18 tekens.


**Returns:**
java.lang.String
### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public final void setLotNumber(String value)
```


Identificeert lot- of batchnummer.
Lot-/batchnummer moet een alfanumerieke tekenreeks zijn met een maximale lengte van 18 tekens.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Identificeert serienummer.
Serienummer moet een alfanumerieke tekenreeks zijn met een maximale lengte van 18 tekens.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Identificeert serienummer.
Serienummer moet een alfanumerieke tekenreeks zijn met een maximale lengte van 18 tekens.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getDateOfManufacture() {#getDateOfManufacture--}
```
public final Date getDateOfManufacture()
```


Identificeert productiedatum.
Productiedatum kan worden ingesteld op DateTime.MinValue om dit veld niet te gebruiken.
Standaardwaarde: DateTime.MinValue


**Returns:**
java.util.Date
### setDateOfManufacture(Date value) {#setDateOfManufacture-java.util.Date-}
```
public final void setDateOfManufacture(Date value)
```


Identificeert productiedatum.
Productiedatum kan worden ingesteld op DateTime.MinValue om dit veld niet te gebruiken.
Standaardwaarde: DateTime.MinValue


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Date |  |

### getQuantity() {#getQuantity--}
```
public final int getQuantity()
```


Identificeert hoeveelheid, moet een geheel getal zijn van 0 tot 500.
Hoeveelheid kan worden ingesteld op -1 om dit veld niet te gebruiken. Standaardwaarde: -1


**Returns:**
int
### setQuantity(int value) {#setQuantity-int-}
```
public final void setQuantity(int value)
```


Identificeert hoeveelheid, moet een geheel getal zijn van 0 tot 500.
Hoeveelheid kan worden ingesteld op -1 om dit veld niet te gebruiken. Standaardwaarde: -1


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getLinkCharacter() {#getLinkCharacter--}
```
public final char getLinkCharacter()
```


Identificeert koppelingskarakter in de uitvoerreeks.


**Returns:**
char
### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public final void setLinkCharacter(char value)
```


Identificeert koppelingskarakter in de uitvoerreeks.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | char |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Krijgt een kopie van dit object.


**Returns:**
java.lang.Object
