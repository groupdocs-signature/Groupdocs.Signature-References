---
title: "ImageSignature"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Görüntü imza özelliklerini içerir."
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.signature.domain.signatures/imagesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class ImageSignature extends BaseSignature
```

Görüntü imza özelliklerini içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageSignature(String signatureId)](#ImageSignature-java.lang.String-) | Arama işleminden elde edilen imza tanımlayıcısı ile ImageSignature nesnesini başlat. |
| [ImageSignature()](#ImageSignature--) | ImageSignature'ı varsayılan parametrelerle başlat. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSize()](#getSize--) | İmza görüntüsünün bayt cinsinden boyutunu belirtir. |
| [setSize(int value)](#setSize-int-) | İmza görüntüsünün bayt cinsinden boyutunu belirtir. |
| [getFormat()](#getFormat--) | İmza görüntüsünün biçimini belirtir. |
| [setFormat(FileType value)](#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-) | İmza görüntüsünün biçimini belirtir. |
| [getContent()](#getContent--) | Format türündeki görüntü ikili veri içeriğini belirtir (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar. |
| [hashCode()](#hashCode--) | GetHashCode metodunu geçersiz kılar. |
| [deepClone()](#deepClone--) | Barcode Signature örneğini klonlar. |
### ImageSignature(String signatureId) {#ImageSignature-java.lang.String-}
```
public ImageSignature(String signatureId)
```


Arama işleminden sonra elde edilen imza tanımlayıcısı ile ImageSignature nesnesini başlatır. Bu benzersiz tanımlayıcı, bu imzanın ek özelliklerini belge imza bilgi katmanından bulmak için kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signatureId | java.lang.String | Signature sınıfının Sign veya Search yöntemiyle elde edilen benzersiz imza tanımlayıcısı [Signature](../../com.groupdocs.signature/signature). |

### ImageSignature() {#ImageSignature--}
```
public ImageSignature()
```


ImageSignature'ı varsayılan parametrelerle başlat.

### getSize() {#getSize--}
```
public final int getSize()
```


İmza görüntüsünün bayt cinsinden boyutunu belirtir.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


İmza görüntüsünün bayt cinsinden boyutunu belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


İmza görüntüsünün biçimini belirtir.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFormat(FileType value)
```


İmza görüntüsünün biçimini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getContent() {#getContent--}
```
public final byte[] getContent()
```


Format türündeki görüntü ikili veri içeriğini belirtir (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). Varsayılan olarak bu özellik ayarlanmaz. Bu özelliği etkinleştirmek için ImageSearchOptions.ReturnContent özelliğini (\{ ImageSearchOptions\#getReturnContent\}/\{ ImageSearchOptions\#setReturnContent(boolean)\}) kullanın.

**Returns:**
byte[]
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


Barcode Signature örneğini klonlar.

**Returns:**
java.lang.Object - Kopyalanmış Barcode Signature örneğini döndürür.
