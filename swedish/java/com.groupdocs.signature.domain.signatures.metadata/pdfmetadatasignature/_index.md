---
title: "PdfMetadataSignature"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Innehåller signaturegenskaper för PDF‑metadata."
type: docs
weight: 14
url: /sv/java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

Innehåller signaturegenskaper för PDF‑metadata.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | Skapar Pdf Metadata-signatur med fördefinierat namn och tomt värde |
|
|  | [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | Skapar Pdf Metadata-signatur med fördefinierade värden |
|
|  | [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | Skapar Pdf Metadata-signatur med fördefinierade värden |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getTagPrefix()](#getTagPrefix--) | Prefixetiketten för Pdf Metadata-signaturens namn. |
|
|  | [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | Prefixetiketten för Pdf Metadata-signaturens namn. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
|  | [deepClone()](#deepClone--) | Klona Metadata Signature-instans. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Klona Pdf Metadata Signature-instans med angivet värde. |
|
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


Skapar Pdf Metadata-signatur med fördefinierat namn och tomt värde


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Pdf Metadata Signature-namn |
|

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


Skapar Pdf Metadata-signatur med fördefinierade värden


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på Metadata‑signaturobjekt |
|
|  | värde | java.lang.Object | Värde på Metadata‑signatur |
|

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


Skapar Pdf Metadata-signatur med fördefinierade värden


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på Metadata‑signaturobjekt |
|
|  | värde | java.lang.Object | Värde på Metadata‑signatur |
|
|  | tagg | java.lang.String | Prefix‑tagg för Metadata‑signatur |
|

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


Prefixetiketten för Pdf Metadata-signaturens namn. Som standard är denna egenskap satt till "xmp".
Möjliga värden är


**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


Prefixetiketten för Pdf Metadata-signaturens namn. Som standard är denna egenskap satt till "xmp".
Möjliga värden är


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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


Klona Metadata Signature-instans.


**Returns:**
java.lang.Object - Returnerar klonad Metadata Signature-instans

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Klona Pdf Metadata Signature-instans med angivet värde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.Object | Värde för nytt klonat objekt. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

