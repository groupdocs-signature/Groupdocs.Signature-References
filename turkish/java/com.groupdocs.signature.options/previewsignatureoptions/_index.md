---
title: "PreviewSignatureOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "İmza önizleme seçeneklerini temsil eder."
type: docs
weight: 12
url: /tr/java/com.groupdocs.signature.options/previewsignatureoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewSignatureOptions
```

İmza önizleme seçeneklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)](#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-) | PreviewSignatureOptions nesnesini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSignatureId()](#getSignatureId--) | İmzayı ayırt etmek için benzersiz değer. |
|
|  | [setSignatureId(String value)](#setSignatureId-java.lang.String-) | İmzayı ayırt etmek için benzersiz değer. |
|
|  | [getSignOptions()](#getSignOptions--) | Önizleme oluşturmak için İmza Seçenekleri. |
|
|  | [setSignOptions(SignOptions value)](#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-) | Önizleme oluşturmak için İmza Seçenekleri. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Önizleme görüntü formatını alır veya ayarlar. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Önizleme görüntü formatını alır veya ayarlar. |
|
### PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory) {#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-}
```
public PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)
```


PreviewSignatureOptions nesnesini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Önizleme oluşturulacak imza seçenekleri. |
|
|  | pageStreamFactory | [PageSignatureStreamFactory](../../com.groupdocs.signature.options/pagesignaturestreamfactory) | Çıktı sayfa önizleme akışı oluşturmak için yöntemi tanımlayan arayüz. |
|

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


İmzayı ayırt etmek için benzersiz değer.
Önizleme seçeneklerini tanımlamak için SignatureId kullanın.


**Returns:**
java.lang.String
### setSignatureId(String value) {#setSignatureId-java.lang.String-}
```
public final void setSignatureId(String value)
```


İmzayı ayırt etmek için benzersiz değer.
Önizleme seçeneklerini tanımlamak için SignatureId kullanın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSignOptions() {#getSignOptions--}
```
public final SignOptions getSignOptions()
```


Önizleme oluşturmak için İmza Seçenekleri.


**Returns:**
[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
### setSignOptions(SignOptions value) {#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-}
```
public final void setSignOptions(SignOptions value)
```


Önizleme oluşturmak için İmza Seçenekleri.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Önizleme görüntü formatını alır veya ayarlar.
Varsayılan değer PNG'dir


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Önizleme görüntü formatını alır veya ayarlar.
Varsayılan değer PNG'dir


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

