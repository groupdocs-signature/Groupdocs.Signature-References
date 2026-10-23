---
title: "ImageSearchOptions"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Görüntü imzaları için arama seçeneklerini temsil eder."
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.signature.options.search/imagesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class ImageSearchOptions extends SearchOptions
```

Görüntü imzaları için arama seçeneklerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageSearchOptions()](#ImageSearchOptions--) | ImageSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getReturnContent()](#getReturnContent--) | Belge sayfasındaki imzanın görüntü içeriğini yakalamak için bayrağı alır veya ayarlar. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Belge sayfasındaki imzanın görüntü içeriğini yakalamak için bayrağı alır veya ayarlar. |
| [getMinContentSize()](#getMinContentSize--) | Sıfır olmayan bir değer için bu bayrak, arama kriterleri için görüntülerin minimum boyutunu belirtir. |
| [setMinContentSize(long value)](#setMinContentSize-long-) | Sıfır olmayan bir değer için bu bayrak, arama kriterleri için görüntülerin minimum boyutunu belirtir. |
| [getMaxContentSize()](#getMaxContentSize--) | Sıfır olmayan bir değer için bu bayrak, arama kriterleri için görüntülerin maksimum boyutunu belirtir. |
| [setMaxContentSize(long value)](#setMaxContentSize-long-) | Sıfır olmayan bir değer için bu bayrak, arama kriterleri için görüntülerin maksimum boyutunu belirtir. |
| [getReturnContentType()](#getReturnContentType--) | ReturnContent özelliği etkin olduğunda görüntü imzasının döndürülen içeriğinin dosya tipini belirtir. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | ReturnContent özelliği etkin olduğunda görüntü imzasının döndürülen içeriğinin dosya tipini belirtir. |
### ImageSearchOptions() {#ImageSearchOptions--}
```
public ImageSearchOptions()
```


ImageSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Belge sayfasındaki imzanın görüntü içeriğini yakalamak için bayrağı alır veya ayarlar. Bu bayrak true olarak ayarlanırsa, görüntü imzası içeriği gerekli formatta ham görüntü verisini tutar  ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Varsayılan olarak bu seçenek devre dışıdır.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Belge sayfasındaki imzanın görüntü içeriğini yakalamak için bayrağı alır veya ayarlar. Bu bayrak true olarak ayarlanırsa, görüntü imzası içeriği gerekli formatta ham görüntü verisini tutar  ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Varsayılan olarak bu seçenek devre dışıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getMinContentSize() {#getMinContentSize--}
```
public final long getMinContentSize()
```


Sıfır olmayan bir değer için bu bayrak, arama kriterleri için görüntülerin minimum boyutunu belirtir. Varsayılan olarak bu bayrak sıfıra ayarlanmıştır ve arama sonucunu etkilemez.

**Returns:**
long
### setMinContentSize(long value) {#setMinContentSize-long-}
```
public final void setMinContentSize(long value)
```


Sıfır olmayan bir değer için bu bayrak, arama kriterleri için görüntülerin minimum boyutunu belirtir. Varsayılan olarak bu bayrak sıfıra ayarlanmıştır ve arama sonucunu etkilemez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getMaxContentSize() {#getMaxContentSize--}
```
public final long getMaxContentSize()
```


Sıfır olmayan bir değer için bu bayrak, arama kriterleri için görüntülerin maksimum boyutunu belirtir. Varsayılan olarak bu bayrak sıfıra ayarlanmıştır ve arama sonucunu etkilemez.

**Returns:**
long
### setMaxContentSize(long value) {#setMaxContentSize-long-}
```
public final void setMaxContentSize(long value)
```


Sıfır olmayan bir değer için bu bayrak, arama kriterleri için görüntülerin maksimum boyutunu belirtir. Varsayılan olarak bu bayrak sıfıra ayarlanmıştır ve arama sonucunu etkilemez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


ReturnContent özelliği etkin olduğunda görüntü imzasının döndürülen içeriğinin dosya tipini belirtir. Varsayılan olarak Null ayarlanmıştır. Bu, görüntü içeriğinin orijinal formatta döndürüleceği anlamına gelir. Bu görüntü formatı ImageSignature.Format içinde belirtilir. Desteklenen olası değerler: FileType.JPEG, FileType.PNG, FileType.BMP. Sağlanan format desteklenmiyorsa, görüntü içeriği orijinal formatta döndürülecektir.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


ReturnContent özelliği etkin olduğunda görüntü imzasının döndürülen içeriğinin dosya tipini belirtir. Varsayılan olarak Null ayarlanmıştır. Bu, görüntü içeriğinin orijinal formatta döndürüleceği anlamına gelir. Bu görüntü formatı ImageSignature.Format içinde belirtilir. Desteklenen olası değerler: FileType.JPEG, FileType.PNG, FileType.BMP. Sağlanan format desteklenmiyorsa, görüntü içeriği orijinal formatta döndürülecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

