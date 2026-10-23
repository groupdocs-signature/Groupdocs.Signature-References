---
title: "QrCodeSignature"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "QR-kod imza özelliklerini içerir."
type: docs
weight: 16
url: /tr/nodejs-java/com.groupdocs.signature.domain.signatures/qrcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class QrCodeSignature extends BaseSignature
```

QR-kod imza özelliklerini içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [QrCodeSignature(String signatureId)](#QrCodeSignature-java.lang.String-) | Arama işleminden elde edilen imza tanımlayıcısı ile QrCodeSignature nesnesini başlat. |
| [QrCodeSignature()](#QrCodeSignature--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | QR kodu Kodlama Türünü belirtir. |
| [getText()](#getText--) | QR kodunun metnini belirtir. |
| [getFormat()](#getFormat--) | QR kodu imza görüntüsünün formatını belirtir. |
| [getContent()](#getContent--) | Format türünde QR kodu ikili veri görüntü içeriğini belirtir (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [<T>getData(Class<T> type)](#-T-getData-java.lang.Class-T--) | QR-Code İmza Metninden nesneyi serileştirme yoluyla elde edin. |
| [<T>getData(IDataEncryption dataEncryption, Class<T> type)](#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--) | QR-Code İmza Metninden nesneyi serileştirme yoluyla elde edin. |
| [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar. |
| [hashCode()](#hashCode--) | GetHashCode metodunu geçersiz kılar. |
| [deepClone()](#deepClone--) | QR-Code İmza örneğini kopyala. |
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### QrCodeSignature(String signatureId) {#QrCodeSignature-java.lang.String-}
```
public QrCodeSignature(String signatureId)
```


Arama işleminden elde edilen imza tanımlayıcısı ile QrCodeSignature nesnesini başlat. Bu benzersiz tanımlayıcı, bu imza için belge imza bilgi katmanından ek özellikleri bulmakta kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signatureId | java.lang.String | İmza veya arama yöntemiyle elde edilen benzersiz imza tanımlayıcısı. |

### QrCodeSignature() {#QrCodeSignature--}
```
public QrCodeSignature()
```


### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QR kodu Kodlama Türünü belirtir.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### getText() {#getText--}
```
public final String getText()
```


QR kodunun metnini belirtir.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


QR kodu imza görüntüsünün formatını belirtir.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Format türünde QR kodu ikili veri görüntü içeriğini belirtir (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). Varsayılan olarak bu özellik ayarlanmaz. Bu özelliği etkinleştirmek için QrCodeSearchOptions.ReturnContent özelliğini kullanın ([QrCodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/qrcodesearchoptions\#getReturnContent)/[QrCodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/qrcodesearchoptions\#setReturnContent-boolean-)).

**Returns:**
byte[]
### <T>getData(Class<T> type) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> type)
```


QR-Code İmza Metninden nesneyi serileştirme yoluyla elde edin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | java.lang.Class<T> |  |

**Returns:**
T -  T : QR-Code Metninden serileştirilecek nesnenin türü
### <T>getData(IDataEncryption dataEncryption, Class<T> type) {#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--}
```
public final T <T>getData(IDataEncryption dataEncryption, Class<T> type)
```


QR-Code İmza Metninden nesneyi serileştirme yoluyla elde edin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Özel veri şifreleme uygulamasını ayarla |

T : QR-Code Metninden serileştirilecek nesnenin türü |
| tür | java.lang.Class<T> |  |

**Returns:**
T -
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


QR-Code İmza örneğini kopyala.

**Returns:**
java.lang.Object - Kopyalanmış QR-code İmza örneğini döndürür.
### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| görüntü | java.awt.image.BufferedImage |  |

