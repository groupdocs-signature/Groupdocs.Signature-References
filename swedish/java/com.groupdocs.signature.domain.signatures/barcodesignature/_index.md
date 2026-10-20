---
title: "BarcodeSignature"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Innehåller egenskaper för streckkodssignatur."
type: docs
weight: 10
url: /sv/java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

Innehåller egenskaper för streckkodssignatur.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | Initiera BarcodeSignature-objektet med signaturidentifieraren som erhölls efter sökprocessen. |
|
|  | [BarcodeSignature()](#BarcodeSignature--) | Initiera BarcodeSignature med standardparametrar. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Anger Barcode-kodningstypen. |
|
|  | [getText()](#getText--) | Anger texten för Barcode. |
|
|  | [getFormat()](#getFormat--) | Anger formatet för Barcode-signaturbilden. |
|
|  | [getContent()](#getContent--) | Anger Barcode-binärdata bildinnehåll av typen |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
|  | [deepClone()](#deepClone--) | Klona Barcode Signature-instans. |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


Initiera BarcodeSignature-objektet med signaturidentifieraren som erhölls efter sökprocessen.
Denna unika identifierare används för att hitta ytterligare egenskaper för denna signatur från dokumentets signaturinformationslager.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | signatureId | java.lang.String | Unik signaturidentifierare erhållen av Sign- eller Search-metoden i Signature-klassen [Signature](../../com.groupdocs.signature/signature). |
|

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


Initiera BarcodeSignature med standardparametrar.


### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Anger Barcode-kodningstypen.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### getText() {#getText--}
```
public final String getText()
```


Anger texten för Barcode.


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Anger formatet för Barcode-signaturbilden.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Anger Barcode-binärdata bildinnehåll av typen
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
Som standard kommer denna egenskap inte att sättas.
Använd egenskap
BarcodeSearchOptions.ReturnContent
([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions#setReturnContent-boolean-)) för att aktivera den här funktionen.


**Returns:**
byte[]
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Skriver över Equals-metoden för att jämföra signaturens egenskaper


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | signatur | java.lang.Object | Signaturobjekt att jämföra med. |
|

**Returns:**
boolean - Returnerar true om det överförda signaturobjektet har samma typ och alla dess egenskaper är lika med egenskaperna i denna instans.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Åsidosätter GetHashCode‑metoden.


**Returns:**
int - Signaturens hashkod

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Klona Barcode Signature-instans.


**Returns:**
java.lang.Object - Returnerar en klonad Barcode Signature-instans.

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| bild | java.awt.image.BufferedImage |  |

