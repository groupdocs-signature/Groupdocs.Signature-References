---
title: "BarcodeSignature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat eigenschappen van Barcode-handtekening."
type: docs
weight: 10
url: /nl/java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

Bevat eigenschappen van Barcode-handtekening.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | Initialiseer BarcodeSignature-object met handtekeningidentificatie die is verkregen na het zoekproces. |
|
|  | [BarcodeSignature()](#BarcodeSignature--) | Initialiseer BarcodeSignature met standaardparameters. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Specificeert het Barcode-coderingstype. |
|
|  | [getText()](#getText--) | Specificeert de tekst van de Barcode. |
|
|  | [getFormat()](#getFormat--) | Specificeert het formaat van de Barcode-handtekeningafbeelding. |
|
|  | [getContent()](#getContent--) | Specificeert de binaire data-afbeeldingsinhoud van de Barcode van het type |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
|  | [deepClone()](#deepClone--) | Kloon Barcode Signature‑instantie. |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


Initialiseer BarcodeSignature-object met handtekeningidentificatie die is verkregen na het zoekproces.
Deze unieke identificatie wordt gebruikt om extra eigenschappen voor deze handtekening te vinden vanuit de documenthandtekening‑informatielaag.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | signatureId | java.lang.String | Unieke handtekeningidentificatie verkregen via de Sign- of Search-methode van de Signature-klasse [Signature](../../com.groupdocs.signature/signature). |
|

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


Initialiseer BarcodeSignature met standaardparameters.


### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Specificeert het Barcode-coderingstype.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### getText() {#getText--}
```
public final String getText()
```


Specificeert de tekst van de Barcode.


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Specificeert het formaat van de Barcode-handtekeningafbeelding.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Specificeert de binaire data-afbeeldingsinhoud van de Barcode van het type
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
Standaard wordt deze eigenschap niet ingesteld.
Gebruik eigenschap
BarcodeSearchOptions.ReturnContent
([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions#setReturnContent-boolean-)) om deze functie in te schakelen.


**Returns:**
byte[]
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | handtekening | java.lang.Object | Handtekeningobject om mee te vergelijken. |
|

**Returns:**
boolean - Retourneert true als het meegegeven handtekeningobject hetzelfde type heeft en al zijn eigenschappen gelijk zijn aan de eigenschappen van deze instantie.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Overschrijft de GetHashCode‑methode


**Returns:**
int - Handtekening hashcode

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Kloon Barcode Signature‑instantie.


**Returns:**
java.lang.Object - Retourneert een gekloonde Barcode-handtekening‑instantie.

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| afbeelding | java.awt.image.BufferedImage |  |

