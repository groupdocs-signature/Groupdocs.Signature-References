---
title: "PdfMetadataSignature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat ondertekenings‑eigenschappen voor PDF‑metadata."
type: docs
weight: 14
url: /nl/java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

Bevat ondertekenings‑eigenschappen voor PDF‑metadata.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | Maakt een Pdf Metadata-handtekening aan met een vooraf gedefinieerde naam en een lege waarde |
|
|  | [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | Maakt een Pdf Metadata-handtekening aan met vooraf gedefinieerde waarden |
|
|  | [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | Maakt een Pdf Metadata-handtekening aan met vooraf gedefinieerde waarden |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getTagPrefix()](#getTagPrefix--) | Het voorvoegsel van de Pdf Metadata-handtekeningnaam. |
|
|  | [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | Het voorvoegsel van de Pdf Metadata-handtekeningnaam. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
|  | [deepClone()](#deepClone--) | Kloon Metadata Signature-instantie. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Kloon Pdf Metadata Signature-instantie met de opgegeven waarde. |
|
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


Maakt een Pdf Metadata-handtekening aan met een vooraf gedefinieerde naam en een lege waarde


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | Pdf Metadata Signature-naam |
|

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


Maakt een Pdf Metadata-handtekening aan met vooraf gedefinieerde waarden


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | Naam van metadata-handtekeningobject |
|
|  | waarde | java.lang.Object | Waarde van metadata-handtekening |
|

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


Maakt een Pdf Metadata-handtekening aan met vooraf gedefinieerde waarden


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | Naam van metadata-handtekeningobject |
|
|  | waarde | java.lang.Object | Waarde van metadata-handtekening |
|
|  | tag | java.lang.String | Prefix-tag van metadata-handtekening |
|

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


Het voorvoegsel van de Pdf Metadata-handtekeningnaam. Standaard is deze eigenschap ingesteld op "xmp".
Mogelijke waarden zijn


**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


Het voorvoegsel van de Pdf Metadata-handtekeningnaam. Standaard is deze eigenschap ingesteld op "xmp".
Mogelijke waarden zijn


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

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


Kloon Metadata Signature-instantie.


**Returns:**
java.lang.Object - Retourneert een gekloonde Metadata Signature-instantie

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Kloon Pdf Metadata Signature-instantie met de opgegeven waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.Object | Waarde voor het nieuwe gekloonde object. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

