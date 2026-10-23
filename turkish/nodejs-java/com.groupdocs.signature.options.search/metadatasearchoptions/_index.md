---
title: "MetadataSearchOptions"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Meta veri imzaları için soyut arama seçeneklerini temsil eder."
type: docs
weight: 15
url: /tr/nodejs-java/com.groupdocs.signature.options.search/metadatasearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class MetadataSearchOptions extends SearchOptions
```

Meta veri imzaları için soyut arama seçeneklerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MetadataSearchOptions()](#MetadataSearchOptions--) | SearchMetadataOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getName()](#getName--) | Aranıp eşleşmesi gereken Metadata İmza adını belirtir. |
| [setName(String value)](#setName-java.lang.String-) | Aranıp eşleşmesi gereken Metadata İmza adını belirtir. |
| [getNameMatchType()](#getNameMatchType--) | Metadata adı Eşleşme Tipi aramasını alır veya ayarlar. |
| [setNameMatchType(int value)](#setNameMatchType-int-) | Metadata adı Eşleşme Tipi aramasını alır veya ayarlar. |
| [getIncludeBuiltinProperties()](#getIncludeBuiltinProperties--) | Belge istatistikleri, bilgiler vb. gibi yerleşik belge özelliklerinin Arama sonucuna dahil edilip edilmeyeceğini gösterir. |
| [setIncludeBuiltinProperties(boolean value)](#setIncludeBuiltinProperties-boolean-) | Belge istatistikleri, bilgiler vb. gibi yerleşik belge özelliklerinin Arama sonucuna dahil edilip edilmeyeceğini gösterir. |
| [getDataEncryption()](#getDataEncryption--) | QR-Code İmza Metni veya Veri özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QR-Code İmza Metni veya Veri özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar. |
### MetadataSearchOptions() {#MetadataSearchOptions--}
```
public MetadataSearchOptions()
```


SearchMetadataOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### getName() {#getName--}
```
public final String getName()
```


Aranıp eşleşmesi gereken Metadata İmza adını belirtir.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Aranıp eşleşmesi gereken Metadata İmza adını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getNameMatchType() {#getNameMatchType--}
```
public final int getNameMatchType()
```


Metadata adı Eşleşme Tipi aramasını alır veya ayarlar. Yalnızca Name özelliği ayarlandığında kullanılır.

**Returns:**
int
### setNameMatchType(int value) {#setNameMatchType-int-}
```
public final void setNameMatchType(int value)
```


Metadata adı Eşleşme Tipi aramasını alır veya ayarlar. Yalnızca Name özelliği ayarlandığında kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getIncludeBuiltinProperties() {#getIncludeBuiltinProperties--}
```
public final boolean getIncludeBuiltinProperties()
```


Belge istatistikleri, bilgiler vb. gibi yerleşik belge özelliklerinin Arama sonucuna dahil edilip edilmeyeceğini gösterir. Bu bayrak, Sunum, Elektronik Tablo ve Kelime İşleme belge dosyası türleri için anlam taşır.

**Returns:**
boolean
### setIncludeBuiltinProperties(boolean value) {#setIncludeBuiltinProperties-boolean-}
```
public final void setIncludeBuiltinProperties(boolean value)
```


Belge istatistikleri, bilgiler vb. gibi yerleşik belge özelliklerinin Arama sonucuna dahil edilip edilmeyeceğini gösterir. Bu bayrak, Sunum, Elektronik Tablo ve Kelime İşleme belge dosyası türleri için anlam taşır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

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

