---
title: "BarcodeVerifyOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Stelt de barcode-verificatieopties voor."
type: docs
weight: 10
url: /nl/java/com.groupdocs.signature.options.verify/barcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class BarcodeVerifyOptions extends TextVerifyOptions
```

Stelt de barcode-verificatieopties voor.

<br />

*** ** * ** ***

 **Learn more**  **Learn more**

* Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](../https://docs.groupdocs.com/signature/java/verify-barcode-signatures-in-the-document)
* Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](../)

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [BarcodeVerifyOptions()](#BarcodeVerifyOptions--) | Maakt standaard verificatieoptie voor barcodehandtekening. |
|
|  | [BarcodeVerifyOptions(String text)](#BarcodeVerifyOptions-java.lang.String-) | Maakt standaard verificatieoptie met verificatietekst. |
|
|  | [BarcodeVerifyOptions(BarcodeType encodeType)](#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Maakt standaard verificatieoptie met verificatie van barcode-type. |
|
|  | [BarcodeVerifyOptions(String text, BarcodeType encodeType)](#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Maakt standaard verificatie‑optie met barcode‑type verificatie en tekst |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Haalt op of stelt barcode‑type verificatie in. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Haalt op of stelt barcode‑type verificatie in. |
|
|  | [toString()](#toString--) | Overschrijft conversie naar string. |
|
### BarcodeVerifyOptions() {#BarcodeVerifyOptions--}
```
public BarcodeVerifyOptions()
```


Maakt standaard verificatieoptie voor barcodehandtekening.


### BarcodeVerifyOptions(String text) {#BarcodeVerifyOptions-java.lang.String-}
```
public BarcodeVerifyOptions(String text)
```


Maakt standaard verificatieoptie met verificatietekst.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekst | java.lang.String | Barcode‑tekst om te verifiëren |
|

### BarcodeVerifyOptions(BarcodeType encodeType) {#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(BarcodeType encodeType)
```


Maakt standaard verificatieoptie met verificatie van barcode-type.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode‑type verificatie |
|

### BarcodeVerifyOptions(String text, BarcodeType encodeType) {#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(String text, BarcodeType encodeType)
```


Maakt standaard verificatie‑optie met barcode‑type verificatie en tekst


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekst | java.lang.String | Barcode‑tekst om te verifiëren |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode‑type verificatie |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Haalt op of stelt barcode‑type verificatie in.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Haalt op of stelt barcode‑type verificatie in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### toString() {#toString--}
```
public String toString()
```


Overschrijft conversie naar string.


**Returns:**
java.lang.String -
