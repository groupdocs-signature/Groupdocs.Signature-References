---
title: "BarcodeSignature"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Barkod İmza özelliklerini içerir."
type: docs
weight: 10
url: /tr/java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

Barkod İmza özelliklerini içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | Arama işleminden sonra elde edilen imza tanımlayıcısı ile BarcodeSignature nesnesini başlat. |
|
|  | [BarcodeSignature()](#BarcodeSignature--) | BarcodeSignature'ı varsayılan parametrelerle başlat. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Barkod Kodlama Türünü belirtir. |
|
|  | [getText()](#getText--) | Barkodun metnini belirtir. |
|
|  | [getFormat()](#getFormat--) | Barkod imza görüntüsünün biçimini belirtir. |
|
|  | [getContent()](#getContent--) | Barkod ikili veri görüntü içeriğinin türünü belirtir. |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar |
|
|  | [hashCode()](#hashCode--) | GetHashCode yöntemini geçersiz kılar |
|
|  | [deepClone()](#deepClone--) | Barcode Signature örneğini klonla. |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


Arama işleminden sonra elde edilen imza tanımlayıcısı ile BarcodeSignature nesnesini başlat.
Bu benzersiz tanımlayıcı, bu imzanın ek özelliklerini belge imza bilgi katmanından bulmak için kullanılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | signatureId | java.lang.String | Sign veya Search yöntemiyle Signature sınıfından elde edilen benzersiz imza tanımlayıcısı [Signature](../../com.groupdocs.signature/signature). |
|

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


BarcodeSignature'ı varsayılan parametrelerle başlat.


### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Barkod Kodlama Türünü belirtir.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### getText() {#getText--}
```
public final String getText()
```


Barkodun metnini belirtir.


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Barkod imza görüntüsünün biçimini belirtir.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Barkod ikili veri görüntü içeriğinin türünü belirtir.
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
Varsayılan olarak bu özellik ayarlanmayacaktır.
Özelliği kullan
BarcodeSearchOptions.ReturnContent
([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions#setReturnContent-boolean-)) bu özelliği etkinleştirmek için.


**Returns:**
byte[]
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


Barcode Signature örneğini klonla.


**Returns:**
java.lang.Object - Kopyalanmış Barkod İmza örneğini döndürür.

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| görüntü | java.awt.image.BufferedImage |  |

