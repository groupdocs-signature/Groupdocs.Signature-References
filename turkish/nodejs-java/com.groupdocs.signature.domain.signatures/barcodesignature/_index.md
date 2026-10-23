---
title: "BarcodeSignature"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Barkod İmza özelliklerini içerir."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.signature.domain.signatures/barcodesignature/
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
| [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | Arama işleminden elde edilen imza tanımlayıcısı ile BarcodeSignature nesnesini başlat. |
| [BarcodeSignature()](#BarcodeSignature--) | BarcodeSignature'ı varsayılan parametrelerle başlat. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Barkod Kodlama Türünü belirtir. |
| [getText()](#getText--) | Barkod metnini belirtir. |
| [getFormat()](#getFormat--) | Barkod imza görüntüsünün biçimini belirtir. |
| [getContent()](#getContent--) | Format türünde Barcode ikili veri görüntü içeriğini belirtir (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar. |
| [hashCode()](#hashCode--) | GetHashCode metodunu geçersiz kılar. |
| [deepClone()](#deepClone--) | Barcode Signature örneğini klonlar. |
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


Arama işleminden elde edilen imza tanımlayıcısı ile BarcodeSignature nesnesini başlat. Bu benzersiz tanımlayıcı, belge imza bilgi katmanından bu imza için ek özellikleri bulmakta kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signatureId | java.lang.String | Signature sınıfının Sign veya Search yöntemiyle elde edilen benzersiz imza tanımlayıcısı [Signature](../../com.groupdocs.signature/signature). |

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


Barkod metnini belirtir.

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


Format türünde Barcode ikili veri görüntü içeriğini belirtir (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). Varsayılan olarak bu özellik ayarlanmaz. Bu özelliği etkinleştirmek için BarcodeSearchOptions.ReturnContent özelliğini ([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions\#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions\#setReturnContent-boolean-)) kullanın.

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
### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| görüntü | java.awt.image.BufferedImage |  |

