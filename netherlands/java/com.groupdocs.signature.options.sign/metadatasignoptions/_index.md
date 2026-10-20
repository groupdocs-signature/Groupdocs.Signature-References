---
title: "MetadataSignOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Vertegenwoordigt metadata-handtekeningopties."
type: docs
weight: 14
url: /nl/java/com.groupdocs.signature.options.sign/metadatasignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
```
public class MetadataSignOptions extends SignOptions
```

Vertegenwoordigt metadata-handtekeningopties.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [MetadataSignOptions()](#MetadataSignOptions--) | Initialiseert een nieuw exemplaar van de SignMetadataOptions-klasse met standaardwaarden. |
|
|  | [MetadataSignOptions(ArrayList<MetadataSignature> signatures)](#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--) | Initialiseert een nieuw exemplaar van de SignMetadataOptions-klasse met metadata. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSignatures()](#getSignatures--) | Haalt of stelt de metadata van de handtekening in. |
|
|  | [setSignatures(MetadataSignatureCollection value)](#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-) | Haalt of stelt de metadata van de handtekening in. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Haalt op of stelt de implementatie van de [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-interface in om QR-Code-handtekeningtekst of -dataproperties te coderen en decoderen. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Haalt op of stelt de implementatie van de [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-interface in om QR-Code-handtekeningtekst of -dataproperties te coderen en decoderen. |
|
|  | [addPdfSignature(String name, Object value, String tag)](#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-) | Maakt een nieuwe PdfMetadataSignature met de meegegeven argumenten en voegt deze toe aan de collectie. |
|
|  | [addImageSignature(int id, Object value)](#addImageSignature-int-java.lang.Object-) | Maakt een nieuwe ImageMetadataSignature met de meegegeven argumenten en voegt deze toe aan de collectie. |
|
|  | [add(MetadataSignature metadataSignature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Voeg een bestaande MetadataSignature-instantie toe aan de collectie. |
|
|  | [validate()](#validate--) | Interne methode om de optieregels te valideren. |
|
|  | [toString()](#toString--) | Overschrijf tekenreeksconversie. |
|
| [signature()](#signature--) |  |
### MetadataSignOptions() {#MetadataSignOptions--}
```
public MetadataSignOptions()
```


Initialiseert een nieuw exemplaar van de SignMetadataOptions-klasse met standaardwaarden.


### MetadataSignOptions(ArrayList<MetadataSignature> signatures) {#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--}
```
public MetadataSignOptions(ArrayList<MetadataSignature> signatures)
```


Initialiseert een nieuw exemplaar van de SignMetadataOptions-klasse met metadata.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | signatures | java.util.ArrayList<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature> | Collectie van metadata-handtekeningen [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature). |
|

### getSignatures() {#getSignatures--}
```
public final MetadataSignatureCollection getSignatures()
```


Haalt of stelt de metadata van de handtekening in.


**Returns:**
[MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection)
### setSignatures(MetadataSignatureCollection value) {#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-}
```
public final void setSignatures(MetadataSignatureCollection value)
```


Haalt of stelt de metadata van de handtekening in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Haalt op of stelt de implementatie van de [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-interface in om QR-Code-handtekeningtekst of -dataproperties te coderen en decoderen.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Haalt op of stelt de implementatie van de [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-interface in om QR-Code-handtekeningtekst of -dataproperties te coderen en decoderen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### addPdfSignature(String name, Object value, String tag) {#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public final PdfMetadataSignature addPdfSignature(String name, Object value, String tag)
```


Maakt een nieuwe PdfMetadataSignature met de meegegeven argumenten en voegt deze toe aan de collectie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | Naam van metadata-handtekeningobject |
|
|  | waarde | java.lang.Object | Waarde van metadata-handtekening |
|
|  | tag | java.lang.String | Prefix-tag van metadata-handtekening |
|

**Returns:**
[PdfMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### addImageSignature(int id, Object value) {#addImageSignature-int-java.lang.Object-}
```
public final ImageMetadataSignature addImageSignature(int id, Object value)
```


Maakt een nieuwe ImageMetadataSignature met de meegegeven argumenten en voegt deze toe aan de collectie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | id | int | Unieke identifier van de Image Metadata Signature-naam. Zie referenties voor Exif-tag specificaties voor mogelijke id-waarden |
|
|  | waarde | java.lang.Object | Metadatawaarde |
|

**Returns:**
[ImageMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### add(MetadataSignature metadataSignature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final MetadataSignOptions add(MetadataSignature metadataSignature)
```


Voeg een bestaande MetadataSignature-instantie toe aan de collectie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | metadataSignature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | De bestaande MetadataSignature-instantie die moet worden toegevoegd |
|

**Returns:**
[MetadataSignOptions](../../com.groupdocs.signature.options.sign/metadatasignoptions) - Instance itself

### validate() {#validate--}
```
public void validate()
```


Interne methode om de optieregels te valideren.


### toString() {#toString--}
```
public String toString()
```


Overschrijf tekenreeksconversie.


**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
