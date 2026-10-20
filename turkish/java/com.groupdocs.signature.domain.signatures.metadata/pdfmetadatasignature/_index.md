---
title: "PdfMetadataSignature"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Pdf Meta Verisi imza özelliklerini içerir."
type: docs
weight: 14
url: /tr/java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

Pdf Meta Verisi imza özelliklerini içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | Önceden tanımlı ad ve boş değerle Pdf Metadata imzası oluşturur. |
|
|  | [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | Önceden tanımlı değerlerle Pdf Metadata imzası oluşturur. |
|
|  | [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | Önceden tanımlı değerlerle Pdf Metadata imzası oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getTagPrefix()](#getTagPrefix--) | Pdf Metadata imza adının önek etiketi. |
|
|  | [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | Pdf Metadata imza adının önek etiketi. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar |
|
|  | [hashCode()](#hashCode--) | GetHashCode yöntemini geçersiz kılar |
|
|  | [deepClone()](#deepClone--) | Metadata İmza örneğini kopyalar. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Verilen değerle Pdf Metadata İmza örneğini kopyalar. |
|
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


Önceden tanımlı ad ve boş değerle Pdf Metadata imzası oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | name | java.lang.String | Pdf Metadata İmza adı |
|

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


Önceden tanımlı değerlerle Pdf Metadata imzası oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | name | java.lang.String | Metadata imza nesnesinin adı |
|
|  | değer | java.lang.Object | Metadata imzasının değeri |
|

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


Önceden tanımlı değerlerle Pdf Metadata imzası oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | name | java.lang.String | Metadata imza nesnesinin adı |
|
|  | değer | java.lang.Object | Metadata imzasının değeri |
|
|  | tag | java.lang.String | Metadata imzasının ön ek etiketi |
|

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


Pdf Metadata imza adının önek etiketi. Varsayılan olarak bu özellik "xmp" olarak ayarlanmıştır.
Olası değerler şunlardır


**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


Pdf Metadata imza adının önek etiketi. Varsayılan olarak bu özellik "xmp" olarak ayarlanmıştır.
Olası değerler şunlardır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | imza | java.lang.Object | Karşılaştırılacak imza nesnesi. |
|

**Returns:**
boolean - Geçilen imza nesnesi aynı türe sahipse ve tüm özellikleri bu örnek özelliklerine eşitse true döndürür.

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode yöntemini geçersiz kılar


**Returns:**
int - İmza karma kodu

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Metadata İmza örneğini kopyalar.


**Returns:**
java.lang.Object - Kopyalanmış Metadata İmza örneğini döndürür

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Verilen değerle Pdf Metadata İmza örneğini kopyalar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.Object | Yeni kopyalanmış nesne için değer. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

