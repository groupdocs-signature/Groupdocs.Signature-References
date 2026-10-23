---
title: "MetadataSignOptions"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Meta veri imza seçeneklerini temsil eder."
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.signature.options.sign/metadatasignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
```
public class MetadataSignOptions extends SignOptions
```

Meta veri imza seçeneklerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MetadataSignOptions()](#MetadataSignOptions--) | SignMetadataOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [MetadataSignOptions(ArrayList<MetadataSignature> signatures)](#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--) | SignMetadataOptions sınıfının yeni bir örneğini Metadata ile başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSignatures()](#getSignatures--) | İmzanın Metadata'sını alır veya ayarlar. |
| [setSignatures(MetadataSignatureCollection value)](#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-) | İmzanın Metadata'sını alır veya ayarlar. |
| [getDataEncryption()](#getDataEncryption--) | QR-Code İmza Metni veya Veri özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QR-Code İmza Metni veya Veri özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar. |
| [addPdfSignature(String name, Object value, String tag)](#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-) | Geçilen argümanlarla yeni PdfMetadataSignature oluşturur ve koleksiyona ekler. |
| [addImageSignature(int id, Object value)](#addImageSignature-int-java.lang.Object-) | Geçilen argümanlarla yeni ImageMetadataSignature oluşturur ve koleksiyona ekler. |
| [add(MetadataSignature metadataSignature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Mevcut MetadataSignature örneğini koleksiyona ekle. |
| [validate()](#validate--) | Seçenek parametrelerini doğrulamak için iç yöntem. |
| [toString()](#toString--) | Dize dönüşümünü geçersiz kılar. |
| [signature()](#signature--) |  |
### MetadataSignOptions() {#MetadataSignOptions--}
```
public MetadataSignOptions()
```


SignMetadataOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### MetadataSignOptions(ArrayList<MetadataSignature> signatures) {#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--}
```
public MetadataSignOptions(ArrayList<MetadataSignature> signatures)
```


SignMetadataOptions sınıfının yeni bir örneğini Metadata ile başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signatures | java.util.ArrayList<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature> | Metadata İmzalarının koleksiyonu [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature). |

### getSignatures() {#getSignatures--}
```
public final MetadataSignatureCollection getSignatures()
```


İmzanın Metadata'sını alır veya ayarlar.

**Returns:**
[MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection)
### setSignatures(MetadataSignatureCollection value) {#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-}
```
public final void setSignatures(MetadataSignatureCollection value)
```


İmzanın Metadata'sını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


QR-Code İmza Metni veya Veri özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


QR-Code İmza Metni veya Veri özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### addPdfSignature(String name, Object value, String tag) {#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public final PdfMetadataSignature addPdfSignature(String name, Object value, String tag)
```


Geçilen argümanlarla yeni PdfMetadataSignature oluşturur ve koleksiyona ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Metadata imza nesnesinin adı |
| değer | java.lang.Object | Metadata imzanın değeri |
| etiket | java.lang.String | Metadata imzanın ön ek etiketi |

**Returns:**
[PdfMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature) - Newly created signature that was added to MetadataSignatures collection
### addImageSignature(int id, Object value) {#addImageSignature-int-java.lang.Object-}
```
public final ImageMetadataSignature addImageSignature(int id, Object value)
```


Geçilen argümanlarla yeni ImageMetadataSignature oluşturur ve koleksiyona ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kimlik | int | Görüntü Metadata İmza adının benzersiz tanımlayıcısı. Olası kimlik değerleri için Exif etiketleri spesifikasyonlarına bakınız. |
| değer | java.lang.Object | Meta veri değeri |

**Returns:**
[ImageMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature) - Newly created signature that was added to MetadataSignatures collection
### add(MetadataSignature metadataSignature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final MetadataSignOptions add(MetadataSignature metadataSignature)
```


Mevcut MetadataSignature örneğini koleksiyona ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metadataSignature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Eklenecek mevcut MetadataSignature örneği |

**Returns:**
[MetadataSignOptions](../../com.groupdocs.signature.options.sign/metadatasignoptions) - Instance itself
### validate() {#validate--}
```
public void validate()
```


Seçenek parametrelerini doğrulamak için iç yöntem.

### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kılar.

**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
