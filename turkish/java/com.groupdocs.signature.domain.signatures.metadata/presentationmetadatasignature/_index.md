---
title: "PresentationMetadataSignature"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Sunum meta verisi imza özelliklerini içerir."
type: docs
weight: 16
url: /tr/java/com.groupdocs.signature.domain.signatures.metadata/presentationmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PresentationMetadataSignature extends MetadataSignature
```

Sunum meta verisi imza özelliklerini içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PresentationMetadataSignature(String name)](#PresentationMetadataSignature-java.lang.String-) | Önceden tanımlı ad ve boş değerle Presentation Metadata Signature oluşturur. |
|
|  | [PresentationMetadataSignature(String name, Object value)](#PresentationMetadataSignature-java.lang.String-java.lang.Object-) | Önceden tanımlı değerlerle Presentation Metadata Signature oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [deepClone()](#deepClone--) | Metadata İmza örneğini kopyalar. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Verilen değerle Slides Metadata Signature örneğini kopyalar. |
|
|  | [toString()](#toString--) | ToString() yöntemiyle geçersiz kılınmış String'e dönüştürür. |
|
|  | [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | Belirtilen formatla String'e dönüştürür. |
|
### PresentationMetadataSignature(String name) {#PresentationMetadataSignature-java.lang.String-}
```
public PresentationMetadataSignature(String name)
```


Önceden tanımlı ad ve boş değerle Presentation Metadata Signature oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | name | java.lang.String | Presentation Metadata Signature adı |
|

### PresentationMetadataSignature(String name, Object value) {#PresentationMetadataSignature-java.lang.String-java.lang.Object-}
```
public PresentationMetadataSignature(String name, Object value)
```


Önceden tanımlı değerlerle Presentation Metadata Signature oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | name | java.lang.String | Metadata imza nesnesinin adı |
|
|  | değer | java.lang.Object | Metadata imzasının değeri |
|

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


Verilen değerle Slides Metadata Signature örneğini kopyalar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.Object | Yeni kopyalanmış nesne için değer. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

### toString() {#toString--}
```
public String toString()
```


ToString() yöntemiyle geçersiz kılınmış String'e dönüştürür.


**Returns:**
java.lang.String - Metadata İmza değerini String olarak döndürür.

<br />

*** ** * ** ***

Bir boolean özelliği "True" veya "False" değerine dönüştürür. Başka bir veri tipi için varsayılan veri formatı sağlayıcı kullanılacaktır.

<br />


### toString(String format, System.IFormatProvider provider) {#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-}
```
public String toString(String format, System.IFormatProvider provider)
```


Belirtilen formatla String'e dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | biçim | java.lang.String | Veri formatı dizesi. |
|
|  | provider | com.aspose.ms.System.IFormatProvider | Veri dönüştürme işlemlerinde kullanılacak format veri sağlayıcı. |

<br />

*** ** * ** ***

Bir boolean özelliği "True" veya "False" değerine dönüştürür.

<br />

|

**Returns:**
java.lang.String - Metadata İmza değerini String olarak döndürür.

