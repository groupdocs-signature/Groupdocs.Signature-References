---
title: "PdfMetadataSignature"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Pdf Metadata imza özelliklerini içerir."
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

Pdf Metadata imza özelliklerini içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | Önceden tanımlı ad ve boş değerle Pdf Metadata imzası oluşturur |
| [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | Önceden tanımlı değerlerle Pdf Metadata imzası oluşturur |
| [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | Önceden tanımlı değerlerle Pdf Metadata imzası oluşturur |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTagPrefix()](#getTagPrefix--) | Pdf Metadata imza adının önek etiketi. |
| [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | Pdf Metadata imza adının önek etiketi. |
| [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar. |
| [hashCode()](#hashCode--) | GetHashCode metodunu geçersiz kılar. |
| [deepClone()](#deepClone--) | Metadata Signature örneğini kopyalar. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Verilen değerle Pdf Metadata Signature örneğini kopyalar. |
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


Önceden tanımlı ad ve boş değerle Pdf Metadata imzası oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Pdf Metadata Signature adı |

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


Önceden tanımlı değerlerle Pdf Metadata imzası oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Metadata imza nesnesinin adı |
| değer | java.lang.Object | Metadata imzanın değeri |

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


Önceden tanımlı değerlerle Pdf Metadata imzası oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Metadata imza nesnesinin adı |
| değer | java.lang.Object | Metadata imzanın değeri |
| etiket | java.lang.String | Metadata imzanın ön ek etiketi |

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


Pdf Metadata imza adının önek etiketi. Varsayılan olarak bu özellik "xmp" olarak ayarlanmıştır. Olası değerler şunlardır

**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


Pdf Metadata imza adının önek etiketi. Varsayılan olarak bu özellik "xmp" olarak ayarlanmıştır. Olası değerler şunlardır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imza | java.lang.Object | Karşılaştırılacak imza nesnesi. |

**Returns:**
boolean - Geçilen imza nesnesi aynı türe sahipse ve tüm özellikleri bu örnek özelliklerine eşitse true döndürür.
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode metodunu geçersiz kılar.

**Returns:**
int - İmza hash kodu
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Metadata Signature örneğini kopyalar.

**Returns:**
java.lang.Object - Kopyalanmış Metadata Signature örneğini döndürür
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Verilen değerle Pdf Metadata Signature örneğini kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object | Yeni kopyalanmış nesne için değer. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
