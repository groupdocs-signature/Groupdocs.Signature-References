---
title: "PresentationMetadataSignature"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Innehåller signaturegenskaper för presentationsmetadata."
type: docs
weight: 16
url: /sv/java/com.groupdocs.signature.domain.signatures.metadata/presentationmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PresentationMetadataSignature extends MetadataSignature
```

Innehåller signaturegenskaper för presentationsmetadata.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [PresentationMetadataSignature(String name)](#PresentationMetadataSignature-java.lang.String-) | Skapar Presentation Metadata Signature med fördefinierat namn och tomt värde |
|
|  | [PresentationMetadataSignature(String name, Object value)](#PresentationMetadataSignature-java.lang.String-java.lang.Object-) | Skapar Presentation Metadata Signature med fördefinierade värden |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [deepClone()](#deepClone--) | Klona Metadata Signature-instans. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Klona Slides Metadata Signature‑instans med angivet värde. |
|
|  | [toString()](#toString--) | Konverterar till String med överskriven ToString()-metod |
|
|  | [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | Konverterar till String med angivet format |
|
### PresentationMetadataSignature(String name) {#PresentationMetadataSignature-java.lang.String-}
```
public PresentationMetadataSignature(String name)
```


Skapar Presentation Metadata Signature med fördefinierat namn och tomt värde


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Presentation Metadata Signature‑namn |
|

### PresentationMetadataSignature(String name, Object value) {#PresentationMetadataSignature-java.lang.String-java.lang.Object-}
```
public PresentationMetadataSignature(String name, Object value)
```


Skapar Presentation Metadata Signature med fördefinierade värden


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på Metadata‑signaturobjekt |
|
|  | värde | java.lang.Object | Värde på Metadata‑signatur |
|

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


Klona Slides Metadata Signature‑instans med angivet värde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.Object | Värde för nytt klonat objekt. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

### toString() {#toString--}
```
public String toString()
```


Konverterar till String med överskriven ToString()-metod


**Returns:**
java.lang.String - Returnerar Metadata Signature‑värdet som String.

<br />

*** ** * ** ***

Konverterar en boolesk egenskap till "True" eller "False". För en annan datatyp används standarddatformatleverantören.

<br />


### toString(String format, System.IFormatProvider provider) {#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-}
```
public String toString(String format, System.IFormatProvider provider)
```


Konverterar till String med angivet format


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | format | java.lang.String | Dataformatsträng. |
|
|  | leverantör | com.aspose.ms.System.IFormatProvider | Formatera dataleverantör att använda med datakonverteringsoperationer. |

<br />

*** ** * ** ***

Konverterar en boolesk egenskap till "True" eller "False".

<br />

|

**Returns:**
java.lang.String - Returnerar Metadata Signature‑värdet som String.

