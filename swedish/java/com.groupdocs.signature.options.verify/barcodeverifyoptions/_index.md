---
title: "BarcodeVerifyOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar Barcode-verifieringsalternativen."
type: docs
weight: 10
url: /sv/java/com.groupdocs.signature.options.verify/barcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class BarcodeVerifyOptions extends TextVerifyOptions
```

Representerar Barcode-verifieringsalternativen.

<br />

*** ** * ** ***

 **Learn more**  **Learn more**

* Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](../https://docs.groupdocs.com/signature/java/verify-barcode-signatures-in-the-document)
* Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](../)

<br />


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [BarcodeVerifyOptions()](#BarcodeVerifyOptions--) | Skapar standardverifieringsalternativ för streckkodssignatur. |
|
|  | [BarcodeVerifyOptions(String text)](#BarcodeVerifyOptions-java.lang.String-) | Skapar standardverifieringsalternativ med verifieringstext |
|
|  | [BarcodeVerifyOptions(BarcodeType encodeType)](#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Skapar standardverifieringsalternativ med verifiering av streckkodstyp |
|
|  | [BarcodeVerifyOptions(String text, BarcodeType encodeType)](#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Skapar standardverifieringsalternativ med verifiering av streckkodstyp och text |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Hämtar eller anger verifiering av streckkodstyp. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Hämtar eller anger verifiering av streckkodstyp. |
|
|  | [toString()](#toString--) | Åsidosätter konvertering till sträng. |
|
### BarcodeVerifyOptions() {#BarcodeVerifyOptions--}
```
public BarcodeVerifyOptions()
```


Skapar standardverifieringsalternativ för streckkodssignatur.


### BarcodeVerifyOptions(String text) {#BarcodeVerifyOptions-java.lang.String-}
```
public BarcodeVerifyOptions(String text)
```


Skapar standardverifieringsalternativ med verifieringstext


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | Streckkodstext att verifiera |
|

### BarcodeVerifyOptions(BarcodeType encodeType) {#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(BarcodeType encodeType)
```


Skapar standardverifieringsalternativ med verifiering av streckkodstyp


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Verifiering av streckkodstyp |
|

### BarcodeVerifyOptions(String text, BarcodeType encodeType) {#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(String text, BarcodeType encodeType)
```


Skapar standardverifieringsalternativ med verifiering av streckkodstyp och text


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | Streckkodstext att verifiera |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Verifiering av streckkodstyp |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Hämtar eller anger verifiering av streckkodstyp.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Hämtar eller anger verifiering av streckkodstyp.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### toString() {#toString--}
```
public String toString()
```


Åsidosätter konvertering till sträng.


**Returns:**
java.lang.String -
