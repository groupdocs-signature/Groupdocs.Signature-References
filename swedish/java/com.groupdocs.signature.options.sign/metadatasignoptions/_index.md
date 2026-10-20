---
title: "MetadataSignOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar Metadata‑signaturalternativen."
type: docs
weight: 14
url: /sv/java/com.groupdocs.signature.options.sign/metadatasignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
```
public class MetadataSignOptions extends SignOptions
```

Representerar Metadata‑signaturalternativen.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [MetadataSignOptions()](#MetadataSignOptions--) | Initierar en ny instans av klassen SignMetadataOptions med standardvärden. |
|
|  | [MetadataSignOptions(ArrayList<MetadataSignature> signatures)](#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--) | Initierar en ny instans av klassen SignMetadataOptions med Metadata. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSignatures()](#getSignatures--) | Hämtar eller anger signaturens Metadata. |
|
|  | [setSignatures(MetadataSignatureCollection value)](#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-) | Hämtar eller anger signaturens Metadata. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)‑gränssnittet för att koda och avkoda QR‑Code Signature Text eller Data egenskaper. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)‑gränssnittet för att koda och avkoda QR‑Code Signature Text eller Data egenskaper. |
|
|  | [addPdfSignature(String name, Object value, String tag)](#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-) | Skapar en ny PdfMetadataSignature med angivna argument och lägger till den i samlingen. |
|
|  | [addImageSignature(int id, Object value)](#addImageSignature-int-java.lang.Object-) | Skapar en ny ImageMetadataSignature med angivna argument och lägger till den i samlingen. |
|
|  | [add(MetadataSignature metadataSignature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Lägg till befintlig MetadataSignature‑instans i samlingen. |
|
|  | [validate()](#validate--) | Intern metod för att validera alternativens parametrar. |
|
|  | [toString()](#toString--) | Åsidosätt strängkonvertering. |
|
| [signature()](#signature--) |  |
### MetadataSignOptions() {#MetadataSignOptions--}
```
public MetadataSignOptions()
```


Initierar en ny instans av klassen SignMetadataOptions med standardvärden.


### MetadataSignOptions(ArrayList<MetadataSignature> signatures) {#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--}
```
public MetadataSignOptions(ArrayList<MetadataSignature> signatures)
```


Initierar en ny instans av klassen SignMetadataOptions med Metadata.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | signatures | java.util.ArrayList<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature> | Samling av Metadata‑signaturer [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature). |
|

### getSignatures() {#getSignatures--}
```
public final MetadataSignatureCollection getSignatures()
```


Hämtar eller anger signaturens Metadata.


**Returns:**
[MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection)
### setSignatures(MetadataSignatureCollection value) {#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-}
```
public final void setSignatures(MetadataSignatureCollection value)
```


Hämtar eller anger signaturens Metadata.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)‑gränssnittet för att koda och avkoda QR‑Code Signature Text eller Data egenskaper.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Hämtar eller anger implementation av [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)‑gränssnittet för att koda och avkoda QR‑Code Signature Text eller Data egenskaper.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### addPdfSignature(String name, Object value, String tag) {#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public final PdfMetadataSignature addPdfSignature(String name, Object value, String tag)
```


Skapar en ny PdfMetadataSignature med angivna argument och lägger till den i samlingen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på Metadata‑signaturobjekt |
|
|  | värde | java.lang.Object | Värde på Metadata‑signatur |
|
|  | tagg | java.lang.String | Prefix‑tagg för Metadata‑signatur |
|

**Returns:**
[PdfMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### addImageSignature(int id, Object value) {#addImageSignature-int-java.lang.Object-}
```
public final ImageMetadataSignature addImageSignature(int id, Object value)
```


Skapar en ny ImageMetadataSignature med angivna argument och lägger till den i samlingen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | id | int | Unik identifierare för namn på bildmetadata‑signatur. Se referenser för Exif‑tagspecifikationer för möjliga id‑värden |
|
|  | värde | java.lang.Object | Metadata‑värde |
|

**Returns:**
[ImageMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### add(MetadataSignature metadataSignature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final MetadataSignOptions add(MetadataSignature metadataSignature)
```


Lägg till befintlig MetadataSignature‑instans i samlingen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | metadataSignature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Den befintliga MetadataSignature‑instansen som ska läggas till |
|

**Returns:**
[MetadataSignOptions](../../com.groupdocs.signature.options.sign/metadatasignoptions) - Instance itself

### validate() {#validate--}
```
public void validate()
```


Intern metod för att validera alternativens parametrar.


### toString() {#toString--}
```
public String toString()
```


Åsidosätt strängkonvertering.


**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
