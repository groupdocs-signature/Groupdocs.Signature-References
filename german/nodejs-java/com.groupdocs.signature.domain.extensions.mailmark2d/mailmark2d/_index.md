---
title: "Mailmark2D"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Klasse zum Kodieren und Dekodieren des in der Royal Mail 2D Mailmark eingebetteten Textes."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

Klasse zum Kodieren und Dekodieren des in der Royal Mail 2D Mailmark eingebetteten Textes.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Mailmark2D()](#Mailmark2D--) | Erstellt kombinierte Royal Mail Mailmark-Daten mit Standardwerten für primäre und sekundäre Daten. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getUPUCountryID()](#getUPUCountryID--) | Identifiziert die UPU-Ländercode-ID.Maximale Länge: 4 Zeichen. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Identifiziert die UPU-Ländercode-ID.Maximale Länge: 4 Zeichen. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifiziert die Barcode-Nutzlast des Royal Mail Mailmark für jeden Produkttyp. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifiziert die Barcode-Nutzlast des Royal Mail Mailmark für jeden Produkttyp. |
| [getVersionID()](#getVersionID--) | Identifiziert die Barcode-Version, die für jede Informations‑Typ‑ID relevant ist. |
| [getClass_()](#getClass---) | Identifiziert die Klasse des Elements. |
| [setClass(String value)](#setClass-java.lang.String-) | Identifiziert die Klasse des Elements. |
| [getSupplyChainID()](#getSupplyChainID--) | Identifiziert die eindeutige Kundengruppe, die am Versand beteiligt ist. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Identifiziert die eindeutige Kundengruppe, die am Versand beteiligt ist. |
| [getItemID()](#getItemID--) | Identifiziert das eindeutige Element innerhalb der Supply‑Chain‑ID. |
| [setItemID(int value)](#setItemID-int-) | Identifiziert das eindeutige Element innerhalb der Supply‑Chain‑ID. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Enthält die Postleitzahl der Lieferadresse mit DPS. Bei Binnenland enthält die Postleitzahl/DP die folgende Anzahl von Zeichen. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Enthält die Postleitzahl der Lieferadresse mit DPS. Bei Binnenland enthält die Postleitzahl/DP die folgende Anzahl von Zeichen. |
| [getRTSFlag()](#getRTSFlag--) | Kennzeichen, das angibt, welche Ebene des Rücksendeservices angefordert wird. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Kennzeichen, das angibt, welche Ebene des Rücksendeservices angefordert wird. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Enthält die Rücksende-Postleitzahl, jedoch kein DPS. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Enthält die Rücksende-Postleitzahl, jedoch kein DPS. |
| [getCustomerContent()](#getCustomerContent--) | Optionaler Raum für die Nutzung durch den Kunden. |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Optionaler Raum für die Nutzung durch den Kunden. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Kodiermodus des DataMatrix-Barcodes. |
| [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | Kodiermodus des DataMatrix-Barcodes. |
| [getDataMatrixType()](#getDataMatrixType--) | Der 2D‑Mailmark‑Typ definiert die Größe des Data‑Matrix‑Barcodes. |
| [setDataMatrixType(int value)](#setDataMatrixType-int-) | Der 2D‑Mailmark‑Typ definiert die Größe des Data‑Matrix‑Barcodes. |
| [deepClone()](#deepClone--) | Liefert eine Kopie dieses Objekts. |
### Mailmark2D() {#Mailmark2D--}
```
public Mailmark2D()
```


Erstellt kombinierte Royal Mail Mailmark-Daten mit Standardwerten für primäre und sekundäre Daten.

### getUPUCountryID() {#getUPUCountryID--}
```
public final String getUPUCountryID()
```


Identifiziert die UPU-Ländercode-ID.Maximale Länge: 4 Zeichen.

**Returns:**
java.lang.String
### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public final void setUPUCountryID(String value)
```


Identifiziert die UPU-Ländercode-ID.Maximale Länge: 4 Zeichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getInformationTypeID() {#getInformationTypeID--}
```
public final String getInformationTypeID()
```


Identifiziert die Barcode-Nutzlast des Royal Mail Mailmark für jeden Produkttyp.

--------------------

Gültige Werte: \"0\" - Inland sortiert und unsortiert \"A\" - Online-Postage \"B\" - Frankierung \"C\" - Konsolidierung

**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


Identifiziert die Barcode-Nutzlast des Royal Mail Mailmark für jeden Produkttyp.

--------------------

Gültige Werte: \"0\" - Inland sortiert und unsortiert \"A\" - Online-Postage \"B\" - Frankierung \"C\" - Konsolidierung

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


Identifiziert die Barcode-Version, die für jede Informations‑Typ‑ID relevant ist.

--------------------

Gültige Werte: \"1\" - derzeit wird nur dieser Wert verwendet (Standard) \"0\" und \"2\" bis \"9\" sowie \"A\" bis \"Z\" sind als Reserve für potenzielle zukünftige Nutzung reserviert.

**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


Identifiziert die Klasse des Elements.

--------------------

Gültige Werte: \"1\" - 1C (Einzelhandel) \"2\" - 2C (Einzelhandel) \"3\" - Economy (Einzelhandel) \"5\" - Deferred (Einzelhandel) \"8\" - Premium (Netzwerkzugriff) \"9\" - Standard (Netzwerkzugriff)

**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


Identifiziert die Klasse des Elements.

--------------------

Gültige Werte: \"1\" - 1C (Einzelhandel) \"2\" - 2C (Einzelhandel) \"3\" - Economy (Einzelhandel) \"5\" - Deferred (Einzelhandel) \"8\" - Premium (Netzwerkzugriff) \"9\" - Standard (Netzwerkzugriff)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


Identifiziert die eindeutige Kundengruppe, die am Versand beteiligt ist. Maximalwert: 9999999.

**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


Identifiziert die eindeutige Kundengruppe, die am Versand beteiligt ist. Maximalwert: 9999999.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


Identifiziert das eindeutige Element innerhalb der Supply‑Chain‑ID. Jeder Mailmark-Barcode muss eine ID tragen, damit er mindestens 90 Tage eindeutig identifiziert werden kann. Maximalwert: 99999999.

**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


Identifiziert das eindeutige Element innerhalb der Supply‑Chain‑ID. Jeder Mailmark-Barcode muss eine ID tragen, damit er mindestens 90 Tage eindeutig identifiziert werden kann. Maximalwert: 99999999.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


Enthält die Postleitzahl der Lieferadresse mit DPS. Bei Binnenland enthält die Postleitzahl/DP die folgende Anzahl von Zeichen: Gebiet (1 oder 2 Zeichen) Bezirk (1 oder 2 Zeichen) Sektor (1 Zeichen) Einheit (2 Zeichen) DPS (2 Zeichen). Die Postleitzahl und das DPS müssen einem gültigen PAF®‑Format entsprechen. Maximale Länge ist 9.

**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


Enthält die Postleitzahl der Lieferadresse mit DPS. Bei Binnenland enthält die Postleitzahl/DP die folgende Anzahl von Zeichen: Gebiet (1 oder 2 Zeichen) Bezirk (1 oder 2 Zeichen) Sektor (1 Zeichen) Einheit (2 Zeichen) DPS (2 Zeichen). Die Postleitzahl und das DPS müssen einem gültigen PAF®‑Format entsprechen. Maximale Länge ist 9.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


Flagge, die angibt, welche Ebene des Rücksendeservices angefordert wird. Maximale Länge ist 1

**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


Flagge, die angibt, welche Ebene des Rücksendeservices angefordert wird. Maximale Länge ist 1

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


Enthält den Rücksendepostcode, jedoch kein DPS. Der PC (ohne DPS) muss dem PAF®‑Format entsprechen.

**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


Enthält den Rücksendepostcode, jedoch kein DPS. Der PC (ohne DPS) muss dem PAF®‑Format entsprechen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


Optionaler Raum für die Nutzung durch den Kunden.

--------------------

Maximale Länge nach Typ [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Typ 7: 6 Zeichen Typ 9: 45 Zeichen Typ 29: 25 Zeichen

**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


Optionaler Raum für die Nutzung durch den Kunden.

--------------------

Maximale Länge nach Typ [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Typ 7: 6 Zeichen Typ 9: 45 Zeichen Typ 29: 25 Zeichen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public final int getCustomerContentEncodeMode()
```


Kodierungsmodus des DataMatrix‑Barcodes. Standardwert: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)

**Returns:**
int
### setCustomerContentEncodeMode(int value) {#setCustomerContentEncodeMode-int-}
```
public final void setCustomerContentEncodeMode(int value)
```


Kodierungsmodus des DataMatrix‑Barcodes. Standardwert: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDataMatrixType() {#getDataMatrixType--}
```
public final int getDataMatrixType()
```


Der 2D‑Mailmark‑Typ definiert die Größe des Data‑Matrix‑Barcodes.

**Returns:**
int
### setDataMatrixType(int value) {#setDataMatrixType-int-}
```
public final void setDataMatrixType(int value)
```


Der 2D‑Mailmark‑Typ definiert die Größe des Data‑Matrix‑Barcodes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Liefert eine Kopie dieses Objekts.

**Returns:**
java.lang.Object
