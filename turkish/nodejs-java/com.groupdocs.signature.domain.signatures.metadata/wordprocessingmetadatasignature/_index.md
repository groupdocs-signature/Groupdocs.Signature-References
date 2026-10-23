---
title: "WordProcessingMetadataSignature"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "WordProcessing Metadata İmza özelliklerini içerir."
type: docs
weight: 18
url: /tr/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/wordprocessingmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class WordProcessingMetadataSignature extends MetadataSignature
```

WordProcessing Metadata İmza özelliklerini içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WordProcessingMetadataSignature(String name)](#WordProcessingMetadataSignature-java.lang.String-) | Önceden tanımlı ad ve boş değerle WordProcessing Metadata Signature oluşturur. |
| [WordProcessingMetadataSignature(String name, Object value)](#WordProcessingMetadataSignature-java.lang.String-java.lang.Object-) | Önceden tanımlı değerlerle WordProcessing Metadata Signature oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone()](#deepClone--) | Metadata Signature örneğini kopyalar. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Verilen değerle Words Metadata Signature örneğini klonlar. |
| [toString()](#toString--) | ToString() yöntemiyle geçersiz kılma yaparak String'e dönüştürür |
| [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | Belirtilen formatla String'e dönüştürür |
### WordProcessingMetadataSignature(String name) {#WordProcessingMetadataSignature-java.lang.String-}
```
public WordProcessingMetadataSignature(String name)
```


Önceden tanımlı ad ve boş değerle WordProcessing Metadata Signature oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | WordProcessing Metadata Signature adı. |

### WordProcessingMetadataSignature(String name, Object value) {#WordProcessingMetadataSignature-java.lang.String-java.lang.Object-}
```
public WordProcessingMetadataSignature(String name, Object value)
```


Önceden tanımlı değerlerle WordProcessing Metadata Signature oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Metadata imza nesnesinin adı. |
| değer | java.lang.Object | Metadata imzasının değeri. |

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


Verilen değerle Words Metadata Signature örneğini klonlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object | Yeni kopyalanmış nesne için değer. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
### toString() {#toString--}
```
public String toString()
```


ToString() yöntemiyle geçersiz kılma yaparak String'e dönüştürür

**Returns:**
java.lang.String - Metadata İmza değerini String olarak döndürür.

--------------------

Bir boolean özelliği "True" veya "False" değerine dönüştürür. Başka bir veri tipi için varsayılan veri biçim sağlayıcısı kullanılacaktır.
### toString(String format, System.IFormatProvider provider) {#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-}
```
public String toString(String format, System.IFormatProvider provider)
```


Belirtilen formatla String'e dönüştürür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| biçim | java.lang.String | Veri biçim dizesi. |
|  | sağlayıcı | com.aspose.ms.System.IFormatProvider | Veri dönüşüm işlemlerinde kullanılacak veri sağlayıcıyı biçimlendir. |

--------------------

Bir boolean özelliği "True" veya "False" değerine dönüştürür. |

**Returns:**
java.lang.String - Metadata İmza değerini String olarak döndürür.
