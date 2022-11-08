---
title: MetadataSignOptions
second_title: GroupDocs.Signature for Java API Reference
description: Represents Metadata signature options.
type: docs
weight: 14
url: /java/com.groupdocs.signature.options.sign/metadatasignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
```
public class MetadataSignOptions extends SignOptions
```

Represents Metadata signature options.
## Constructors

| Constructor | Description |
| --- | --- |
| [MetadataSignOptions()](#MetadataSignOptions--) | Initializes a new instance of the SignMetadataOptions class with default values. |
| [MetadataSignOptions(ArrayList<MetadataSignature> signatures)](#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--) | Initializes a new instance of the SignMetadataOptions class with Metadata. |
## Methods

| Method | Description |
| --- | --- |
| [getSignatures()](#getSignatures--) | Gets or sets the Metadata of signature. |
| [setSignatures(MetadataSignatureCollection value)](#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-) | Gets or sets the Metadata of signature. |
| [getDataEncryption()](#getDataEncryption--) | Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text or Data properties. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text or Data properties. |
| [addPdfSignature(String name, Object value, String tag)](#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-) | Creates new PdfMetadataSignature with passed arguments and adds it to collection. |
| [addImageSignature(int id, Object value)](#addImageSignature-int-java.lang.Object-) | Creates new ImageMetadataSignature with passed arguments and adds it to collection. |
| [add(MetadataSignature metadataSignature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Add existing MetadataSignature instance to collection. |
| [validate()](#validate--) | Internal method to validate the options parameters. |
| [toString()](#toString--) | Override string conversion. |
| [signature()](#signature--) |  |
### MetadataSignOptions() {#MetadataSignOptions--}
```
public MetadataSignOptions()
```


Initializes a new instance of the SignMetadataOptions class with default values.

### MetadataSignOptions(ArrayList<MetadataSignature> signatures) {#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--}
```
public MetadataSignOptions(ArrayList<MetadataSignature> signatures)
```


Initializes a new instance of the SignMetadataOptions class with Metadata.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signatures | java.util.ArrayList<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature> | Collection of Metadata Signatures [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature). |

### getSignatures() {#getSignatures--}
```
public final MetadataSignatureCollection getSignatures()
```


Gets or sets the Metadata of signature.

**Returns:**
[MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection)
### setSignatures(MetadataSignatureCollection value) {#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-}
```
public final void setSignatures(MetadataSignatureCollection value)
```


Gets or sets the Metadata of signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text or Data properties.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text or Data properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### addPdfSignature(String name, Object value, String tag) {#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public final PdfMetadataSignature addPdfSignature(String name, Object value, String tag)
```


Creates new PdfMetadataSignature with passed arguments and adds it to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of Metadata signature object |
| value | java.lang.Object | Value of Metadata signature |
| tag | java.lang.String | Prefix tag of Metadata signature |

**Returns:**
[PdfMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature) - Newly created signature that was added to MetadataSignatures collection
### addImageSignature(int id, Object value) {#addImageSignature-int-java.lang.Object-}
```
public final ImageMetadataSignature addImageSignature(int id, Object value)
```


Creates new ImageMetadataSignature with passed arguments and adds it to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | Unique identifier Image Metadata Signature name. See references for Exif tags specifications for possible id values |
| value | java.lang.Object | Metadata value |

**Returns:**
[ImageMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature) - Newly created signature that was added to MetadataSignatures collection
### add(MetadataSignature metadataSignature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final MetadataSignOptions add(MetadataSignature metadataSignature)
```


Add existing MetadataSignature instance to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| metadataSignature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | The existing MetadataSignature instance to be added |

**Returns:**
[MetadataSignOptions](../../com.groupdocs.signature.options.sign/metadatasignoptions) - Instance itself
### validate() {#validate--}
```
public void validate()
```


Internal method to validate the options parameters.

### toString() {#toString--}
```
public String toString()
```


Override string conversion.

**Returns:**
java.lang.String - 
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
