---
title: "SpreadsheetMetadataSignature"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Elektronik tablo Meta Verisi İmza özelliklerini içerir."
type: docs
weight: 17
url: /tr/java/com.groupdocs.signature.domain.signatures.metadata/spreadsheetmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class SpreadsheetMetadataSignature extends MetadataSignature
```

Elektronik tablo Meta Verisi İmza özelliklerini içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [SpreadsheetMetadataSignature(String name)](#SpreadsheetMetadataSignature-java.lang.String-) | Önceden tanımlı ad ve boş değerle Spreadsheet Metadata Signature oluşturur. |
|
|  | [SpreadsheetMetadataSignature(String name, Object value)](#SpreadsheetMetadataSignature-java.lang.String-java.lang.Object-) | Önceden tanımlı değerlerle Spreadsheet Metadata Signature oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [deepClone()](#deepClone--) | Metadata İmza örneğini kopyalar. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Verilen değerle Spreadsheet Metadata Signature örneğini kopyalar. |
|
|  | [toString()](#toString--) | ToString() yöntemiyle geçersiz kılınmış String'e dönüştürür. |
|
|  | [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | Belirtilen formatla String'e dönüştürür. |
|
### SpreadsheetMetadataSignature(String name) {#SpreadsheetMetadataSignature-java.lang.String-}
```
public SpreadsheetMetadataSignature(String name)
```


Önceden tanımlı ad ve boş değerle Spreadsheet Metadata Signature oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | name | java.lang.String | Spreadsheet Metadata Signature adı. |
|

### SpreadsheetMetadataSignature(String name, Object value) {#SpreadsheetMetadataSignature-java.lang.String-java.lang.Object-}
```
public SpreadsheetMetadataSignature(String name, Object value)
```


Önceden tanımlı değerlerle Spreadsheet Metadata Signature oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | name | java.lang.String | Metadata signature nesnesinin adı. |
|
|  | değer | java.lang.Object | Metadata signature değeri. |
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


Verilen değerle Spreadsheet Metadata Signature örneğini kopyalar.


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

