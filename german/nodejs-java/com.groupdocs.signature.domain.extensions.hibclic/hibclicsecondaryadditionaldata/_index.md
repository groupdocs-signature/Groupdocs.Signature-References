---
title: "HIBCLICSecondaryAdditionalData"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Klasse zum Speichern von HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code sekundären und zusätzlichen Daten."
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICSecondaryAdditionalData implements IComplexData
```

Klasse zum Speichern sekundärer und zusätzlicher HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code)-Daten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HIBCLICSecondaryAdditionalData()](#HIBCLICSecondaryAdditionalData--) | Standard ctor() |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | Identifiziert das Ablaufdatumsformat. |
| [setExpiryDateFormat(int value)](#setExpiryDateFormat-int-) | Identifiziert das Ablaufdatumsformat. |
| [getExpiryDate()](#getExpiryDate--) | Identifiziert das Ablaufdatum. |
| [setExpiryDate(Date value)](#setExpiryDate-java.util.Date-) | Identifiziert das Ablaufdatum. |
| [getLotNumber()](#getLotNumber--) | Identifiziert Los- oder Chargennummer. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Identifiziert Los- oder Chargennummer. |
| [getSerialNumber()](#getSerialNumber--) | Identifiziert die Seriennummer. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Identifiziert die Seriennummer. |
| [getDateOfManufacture()](#getDateOfManufacture--) | Identifiziert das Herstellungsdatum. |
| [setDateOfManufacture(Date value)](#setDateOfManufacture-java.util.Date-) | Identifiziert das Herstellungsdatum. |
| [getQuantity()](#getQuantity--) | Identifiziert die Menge, muss ein ganzzahliger Wert von 0 bis 500 sein. |
| [setQuantity(int value)](#setQuantity-int-) | Identifiziert die Menge, muss ein ganzzahliger Wert von 0 bis 500 sein. |
| [getLinkCharacter()](#getLinkCharacter--) | Identifiziert das Verknüpfungszeichen im Ausgabestring. |
| [setLinkCharacter(char value)](#setLinkCharacter-char-) | Identifiziert das Verknüpfungszeichen im Ausgabestring. |
| [deepClone()](#deepClone--) | Liefert eine Kopie dieses Objekts. |
### HIBCLICSecondaryAdditionalData() {#HIBCLICSecondaryAdditionalData--}
```
public HIBCLICSecondaryAdditionalData()
```


Standard ctor()

### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public final int getExpiryDateFormat()
```


Identifiziert das Ablaufdatumsformat.

**Returns:**
int
### setExpiryDateFormat(int value) {#setExpiryDateFormat-int-}
```
public final void setExpiryDateFormat(int value)
```


Identifiziert das Ablaufdatumsformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getExpiryDate() {#getExpiryDate--}
```
public final Date getExpiryDate()
```


Identifiziert das Ablaufdatum. Wird verwendet, wenn ExpiryDateFormat nicht auf None gesetzt ist.

**Returns:**
java.util.Date
### setExpiryDate(Date value) {#setExpiryDate-java.util.Date-}
```
public final void setExpiryDate(Date value)
```


Identifiziert das Ablaufdatum. Wird verwendet, wenn ExpiryDateFormat nicht auf None gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

### getLotNumber() {#getLotNumber--}
```
public final String getLotNumber()
```


Identifiziert Los- oder Chargennummer. Los-/Chargennummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein.

**Returns:**
java.lang.String
### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public final void setLotNumber(String value)
```


Identifiziert Los- oder Chargennummer. Los-/Chargennummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Identifiziert die Seriennummer. Seriennummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein.

**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Identifiziert die Seriennummer. Seriennummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getDateOfManufacture() {#getDateOfManufacture--}
```
public final Date getDateOfManufacture()
```


Identifiziert das Herstellungsdatum. Das Herstellungsdatum kann auf DateTime.MinValue gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: DateTime.MinValue

**Returns:**
java.util.Date
### setDateOfManufacture(Date value) {#setDateOfManufacture-java.util.Date-}
```
public final void setDateOfManufacture(Date value)
```


Identifiziert das Herstellungsdatum. Das Herstellungsdatum kann auf DateTime.MinValue gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: DateTime.MinValue

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

### getQuantity() {#getQuantity--}
```
public final int getQuantity()
```


Identifiziert die Menge, muss ein ganzzahliger Wert von 0 bis 500 sein. Menge kann auf -1 gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: -1

**Returns:**
int
### setQuantity(int value) {#setQuantity-int-}
```
public final void setQuantity(int value)
```


Identifiziert die Menge, muss ein ganzzahliger Wert von 0 bis 500 sein. Menge kann auf -1 gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: -1

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLinkCharacter() {#getLinkCharacter--}
```
public final char getLinkCharacter()
```


Identifiziert das Verknüpfungszeichen im Ausgabestring.

**Returns:**
char
### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public final void setLinkCharacter(char value)
```


Identifiziert das Verknüpfungszeichen im Ausgabestring.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | char |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Liefert eine Kopie dieses Objekts.

**Returns:**
java.lang.Object
