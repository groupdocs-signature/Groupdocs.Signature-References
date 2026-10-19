---
title: "BarcodeVerifyOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt die Barcode‑Verifizierungsoptionen dar."
type: docs
weight: 10
url: /de/java/com.groupdocs.signature.options.verify/barcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class BarcodeVerifyOptions extends TextVerifyOptions
```

Stellt die Barcode‑Verifizierungsoptionen dar.

<br />

*** ** * ** ***

 **Learn more**  **Learn more**

* Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](../https://docs.groupdocs.com/signature/java/verify-barcode-signatures-in-the-document)
* Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](../)

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [BarcodeVerifyOptions()](#BarcodeVerifyOptions--) | Erstellt die Standard‑Verifizierungsoption für Barcode‑Signatur. |
|
|  | [BarcodeVerifyOptions(String text)](#BarcodeVerifyOptions-java.lang.String-) | Erstellt die Standard‑Verifizierungsoption mit Verifizierungstext |
|
|  | [BarcodeVerifyOptions(BarcodeType encodeType)](#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Erstellt die Standard‑Verifizierungsoption mit Barcode‑Typ‑Verifizierung |
|
|  | [BarcodeVerifyOptions(String text, BarcodeType encodeType)](#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Erstellt die Standard‑Verifizierungsoption mit Barcode‑Typ‑Verifizierung und Text |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Abrufen oder Festlegen der Barcode‑Typ‑Verifizierung. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Abrufen oder Festlegen der Barcode‑Typ‑Verifizierung. |
|
|  | [toString()](#toString--) | Überschreibt die Konvertierung in einen String. |
|
### BarcodeVerifyOptions() {#BarcodeVerifyOptions--}
```
public BarcodeVerifyOptions()
```


Erstellt die Standard‑Verifizierungsoption für Barcode‑Signatur.


### BarcodeVerifyOptions(String text) {#BarcodeVerifyOptions-java.lang.String-}
```
public BarcodeVerifyOptions(String text)
```


Erstellt die Standard‑Verifizierungsoption mit Verifizierungstext


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | Barcode‑Text zur Verifizierung |
|

### BarcodeVerifyOptions(BarcodeType encodeType) {#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(BarcodeType encodeType)
```


Erstellt die Standard‑Verifizierungsoption mit Barcode‑Typ‑Verifizierung


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode‑Typ‑Verifizierung |
|

### BarcodeVerifyOptions(String text, BarcodeType encodeType) {#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(String text, BarcodeType encodeType)
```


Erstellt die Standard‑Verifizierungsoption mit Barcode‑Typ‑Verifizierung und Text


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | Barcode‑Text zur Verifizierung |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode‑Typ‑Verifizierung |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Abrufen oder Festlegen der Barcode‑Typ‑Verifizierung.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Abrufen oder Festlegen der Barcode‑Typ‑Verifizierung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### toString() {#toString--}
```
public String toString()
```


Überschreibt die Konvertierung in einen String.


**Returns:**
java.lang.String -
