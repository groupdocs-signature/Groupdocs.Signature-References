---
title: "CertificateMetadataSignature"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Sertifika Meta Veri İmza özelliklerini içerir."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/certificatemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class CertificateMetadataSignature extends MetadataSignature
```

Sertifika Meta Veri İmza özelliklerini içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CertificateMetadataSignature(String name)](#CertificateMetadataSignature-java.lang.String-) | Önceden tanımlı ad ve boş değer ile Certificate Metadata Signature oluşturur. |
| [CertificateMetadataSignature(String name, Object value)](#CertificateMetadataSignature-java.lang.String-java.lang.Object-) | Önceden tanımlı değerlerle Certificate Metadata Signature oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone()](#deepClone--) | Metadata Signature örneğini kopyalar. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Verilen değerle Certificate Metadata Signature örneğini klonla. |
| [toString()](#toString--) | ToString() yöntemiyle geçersiz kılma yaparak String'e dönüştürür |
| [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | Belirtilen formatla String'e dönüştürür |
### CertificateMetadataSignature(String name) {#CertificateMetadataSignature-java.lang.String-}
```
public CertificateMetadataSignature(String name)
```


Önceden tanımlı ad ve boş değer ile Certificate Metadata Signature oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Certificate Metadata Signature adı. |

### CertificateMetadataSignature(String name, Object value) {#CertificateMetadataSignature-java.lang.String-java.lang.Object-}
```
public CertificateMetadataSignature(String name, Object value)
```


Önceden tanımlı değerlerle Certificate Metadata Signature oluşturur.

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


Verilen değerle Certificate Metadata Signature örneğini klonla.

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
