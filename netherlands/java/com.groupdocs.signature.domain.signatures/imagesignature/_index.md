---
title: "ImageSignature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat eigenschappen van afbeeldinghandtekening."
type: docs
weight: 14
url: /nl/java/com.groupdocs.signature.domain.signatures/imagesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class ImageSignature extends BaseSignature
```

Bevat eigenschappen van afbeeldinghandtekening.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ImageSignature(String signatureId)](#ImageSignature-java.lang.String-) | Initialiseer ImageSignature-object met handtekeningidentificatie die is verkregen na het zoekproces. |
|
|  | [ImageSignature()](#ImageSignature--) | Initialiseer ImageSignature met standaardparameters. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSize()](#getSize--) | Bepaalt de grootte in bytes van de handtekeningafbeelding. |
|
|  | [setSize(int value)](#setSize-int-) | Bepaalt de grootte in bytes van de handtekeningafbeelding. |
|
|  | [getFormat()](#getFormat--) | Bepaalt het formaat van de handtekeningafbeelding. |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-) | Bepaalt het formaat van de handtekeningafbeelding. |
|
|  | [getContent()](#getContent--) | Bepaalt de binaire afbeeldingsgegevensinhoud van het type |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
|  | [deepClone()](#deepClone--) | Kloon Barcode Signature‑instantie. |
|
### ImageSignature(String signatureId) {#ImageSignature-java.lang.String-}
```
public ImageSignature(String signatureId)
```


Initialiseer ImageSignature-object met handtekeningidentificatie die is verkregen na het zoekproces.
Deze unieke identificatie wordt gebruikt om extra eigenschappen voor deze handtekening te vinden vanuit de documenthandtekening‑informatielaag.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | signatureId | java.lang.String | Unieke handtekeningidentificatie verkregen via de Sign- of Search-methode van de Signature-klasse [Signature](../../com.groupdocs.signature/signature). |
|

### ImageSignature() {#ImageSignature--}
```
public ImageSignature()
```


Initialiseer ImageSignature met standaardparameters.


### getSize() {#getSize--}
```
public final int getSize()
```


Bepaalt de grootte in bytes van de handtekeningafbeelding.


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Bepaalt de grootte in bytes van de handtekeningafbeelding.



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Bepaalt het formaat van de handtekeningafbeelding.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFormat(FileType value)
```


Bepaalt het formaat van de handtekeningafbeelding.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getContent() {#getContent--}
```
public final byte[] getContent()
```


Bepaalt de binaire afbeeldingsgegevensinhoud van het type
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
Standaard wordt deze eigenschap niet ingesteld.
Gebruik eigenschap
ImageSearchOptions.ReturnContent
({ ImageSearchOptions#getReturnContent}/{ ImageSearchOptions#setReturnContent(boolean)}) om deze functie in te schakelen.


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

