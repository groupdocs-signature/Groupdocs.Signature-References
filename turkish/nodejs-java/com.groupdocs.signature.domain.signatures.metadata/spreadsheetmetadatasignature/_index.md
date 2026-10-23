---
title: "SpreadsheetMetadataSignature"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Spreadsheet Metadata İmza özelliklerini içerir."
type: docs
weight: 17
url: /tr/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/spreadsheetmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class SpreadsheetMetadataSignature extends MetadataSignature
```

Spreadsheet Metadata İmza özelliklerini içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SpreadsheetMetadataSignature(String name)](#SpreadsheetMetadataSignature-java.lang.String-) | Önceden tanımlı ad ve boş değer ile Spreadsheet Metadata Signature oluşturur. |
| [SpreadsheetMetadataSignature(String name, Object value)](#SpreadsheetMetadataSignature-java.lang.String-java.lang.Object-) | Önceden tanımlı değerlerle Spreadsheet Metadata Signature oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone()](#deepClone--) | Metadata Signature örneğini kopyalar. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Verilen değerle Spreadsheet Metadata Signature örneğini klonlar. |
| [toString()](#toString--) | ToString() yöntemiyle geçersiz kılma yaparak String'e dönüştürür |
| [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | Belirtilen formatla String'e dönüştürür |
### SpreadsheetMetadataSignature(String name) {#SpreadsheetMetadataSignature-java.lang.String-}
```
public SpreadsheetMetadataSignature(String name)
```


Önceden tanımlı ad ve boş değer ile Spreadsheet Metadata Signature oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Spreadsheet Metadata Signature adı. |

### SpreadsheetMetadataSignature(String name, Object value) {#SpreadsheetMetadataSignature-java.lang.String-java.lang.Object-}
```
public SpreadsheetMetadataSignature(String name, Object value)
```


Önceden tanımlı değerlerle Spreadsheet Metadata Signature oluşturur.

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


Verilen değerle Spreadsheet Metadata Signature örneğini klonlar.

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
