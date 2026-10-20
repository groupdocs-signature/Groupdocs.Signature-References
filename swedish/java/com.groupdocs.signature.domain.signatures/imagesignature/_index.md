---
title: "ImageSignature"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Innehåller egenskaper för bildsignatur."
type: docs
weight: 14
url: /sv/java/com.groupdocs.signature.domain.signatures/imagesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class ImageSignature extends BaseSignature
```

Innehåller egenskaper för bildsignatur.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [ImageSignature(String signatureId)](#ImageSignature-java.lang.String-) | Initiera ImageSignature-objektet med signaturidentifierare som erhölls efter sökprocessen. |
|
|  | [ImageSignature()](#ImageSignature--) | Initiera ImageSignature med standardparametrar. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSize()](#getSize--) | Anger storleken i byte för signaturbilden. |
|
|  | [setSize(int value)](#setSize-int-) | Anger storleken i byte för signaturbilden. |
|
|  | [getFormat()](#getFormat--) | Anger formatet för signaturbilden. |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-) | Anger formatet för signaturbilden. |
|
|  | [getContent()](#getContent--) | Anger bildens binära datainnehåll av typen |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
|  | [deepClone()](#deepClone--) | Klona Barcode Signature-instans. |
|
### ImageSignature(String signatureId) {#ImageSignature-java.lang.String-}
```
public ImageSignature(String signatureId)
```


Initiera ImageSignature-objektet med signaturidentifierare som erhölls efter sökprocessen.
Denna unika identifierare används för att hitta ytterligare egenskaper för denna signatur från dokumentets signaturinformationslager.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | signatureId | java.lang.String | Unik signaturidentifierare erhållen av Sign- eller Search-metoden i Signature-klassen [Signature](../../com.groupdocs.signature/signature). |
|

### ImageSignature() {#ImageSignature--}
```
public ImageSignature()
```


Initiera ImageSignature med standardparametrar.


### getSize() {#getSize--}
```
public final int getSize()
```


Anger storleken i byte för signaturbilden.


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Anger storleken i byte för signaturbilden.



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Anger formatet för signaturbilden.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFormat(FileType value)
```


Anger formatet för signaturbilden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getContent() {#getContent--}
```
public final byte[] getContent()
```


Anger bildens binära datainnehåll av typen
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
Som standard kommer denna egenskap inte att sättas.
Använd egenskap
ImageSearchOptions.ReturnContent
({ ImageSearchOptions#getReturnContent}/{ ImageSearchOptions#setReturnContent(boolean)}) för att aktivera den här funktionen.


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

