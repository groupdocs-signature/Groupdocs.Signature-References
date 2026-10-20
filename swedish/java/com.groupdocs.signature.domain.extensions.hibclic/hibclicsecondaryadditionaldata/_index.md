---
title: "HIBCLICSecondaryAdditionalData"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Klass för lagring av HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code sekundära och ytterligare data."
type: docs
weight: 13
url: /sv/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICSecondaryAdditionalData implements IComplexData
```

Klass för att lagra HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) sekundära och ytterligare data.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [HIBCLICSecondaryAdditionalData()](#HIBCLICSecondaryAdditionalData--) | Standard ctor() |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getExpiryDateFormat()](#getExpiryDateFormat--) | Identifierar utgångsdatumsformat. |
|
|  | [setExpiryDateFormat(int value)](#setExpiryDateFormat-int-) | Identifierar utgångsdatumsformat. |
|
|  | [getExpiryDate()](#getExpiryDate--) | Identifierar utgångsdatum. |
|
|  | [setExpiryDate(Date value)](#setExpiryDate-java.util.Date-) | Identifierar utgångsdatum. |
|
|  | [getLotNumber()](#getLotNumber--) | Identifierar parti- eller batchnummer. |
|
|  | [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Identifierar parti- eller batchnummer. |
|
|  | [getSerialNumber()](#getSerialNumber--) | Identifierar serienummer. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Identifierar serienummer. |
|
|  | [getDateOfManufacture()](#getDateOfManufacture--) | Identifierar tillverkningsdatum. |
|
|  | [setDateOfManufacture(Date value)](#setDateOfManufacture-java.util.Date-) | Identifierar tillverkningsdatum. |
|
|  | [getQuantity()](#getQuantity--) | Identifierar kvantitet, måste vara ett heltalsvärde från 0 till 500. |
|
|  | [setQuantity(int value)](#setQuantity-int-) | Identifierar kvantitet, måste vara ett heltalsvärde från 0 till 500. |
|
|  | [getLinkCharacter()](#getLinkCharacter--) | Identifierar länktecken i utdata-strängen. |
|
|  | [setLinkCharacter(char value)](#setLinkCharacter-char-) | Identifierar länktecken i utdata-strängen. |
|
|  | [deepClone()](#deepClone--) | Hämtar en kopia av detta objekt. |
|
### HIBCLICSecondaryAdditionalData() {#HIBCLICSecondaryAdditionalData--}
```
public HIBCLICSecondaryAdditionalData()
```


Standard ctor()


### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public final int getExpiryDateFormat()
```


Identifierar utgångsdatumsformat.


**Returns:**
int
### setExpiryDateFormat(int value) {#setExpiryDateFormat-int-}
```
public final void setExpiryDateFormat(int value)
```


Identifierar utgångsdatumsformat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getExpiryDate() {#getExpiryDate--}
```
public final Date getExpiryDate()
```


Identifierar utgångsdatum. Används om ExpiryDateFormat inte är inställt på None.


**Returns:**
java.util.Date
### setExpiryDate(Date value) {#setExpiryDate-java.util.Date-}
```
public final void setExpiryDate(Date value)
```


Identifierar utgångsdatum. Används om ExpiryDateFormat inte är inställt på None.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date |  |

### getLotNumber() {#getLotNumber--}
```
public final String getLotNumber()
```


Identifierar parti- eller batchnummer.
Parti-/batchnummer måste vara en alfanumerisk sträng med upp till 18 tecken.


**Returns:**
java.lang.String
### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public final void setLotNumber(String value)
```


Identifierar parti- eller batchnummer.
Parti-/batchnummer måste vara en alfanumerisk sträng med upp till 18 tecken.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Identifierar serienummer.
Serienummer måste vara en alfanumerisk sträng med upp till 18 tecken.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Identifierar serienummer.
Serienummer måste vara en alfanumerisk sträng med upp till 18 tecken.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getDateOfManufacture() {#getDateOfManufacture--}
```
public final Date getDateOfManufacture()
```


Identifierar tillverkningsdatum.
Tillverkningsdatum kan sättas till DateTime.MinValue för att inte använda detta fält.
Standardvärde: DateTime.MinValue


**Returns:**
java.util.Date
### setDateOfManufacture(Date value) {#setDateOfManufacture-java.util.Date-}
```
public final void setDateOfManufacture(Date value)
```


Identifierar tillverkningsdatum.
Tillverkningsdatum kan sättas till DateTime.MinValue för att inte använda detta fält.
Standardvärde: DateTime.MinValue


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date |  |

### getQuantity() {#getQuantity--}
```
public final int getQuantity()
```


Identifierar kvantitet, måste vara ett heltalsvärde från 0 till 500.
Kvantitet kan sättas till -1 för att inte använda detta fält. Standardvärde: -1


**Returns:**
int
### setQuantity(int value) {#setQuantity-int-}
```
public final void setQuantity(int value)
```


Identifierar kvantitet, måste vara ett heltalsvärde från 0 till 500.
Kvantitet kan sättas till -1 för att inte använda detta fält. Standardvärde: -1


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getLinkCharacter() {#getLinkCharacter--}
```
public final char getLinkCharacter()
```


Identifierar länktecken i utdata-strängen.


**Returns:**
char
### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public final void setLinkCharacter(char value)
```


Identifierar länktecken i utdata-strängen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | char |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Hämtar en kopia av detta objekt.


**Returns:**
java.lang.Object
