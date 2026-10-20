---
title: "SignatureSettings"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Davranışı özelleştirmek için ayarları tanımlar."
type: docs
weight: 11
url: /tr/java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

 [Signature](../../com.groupdocs.signature/signature) davranışını özelleştirmek için ayarları tanımlar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [SignatureSettings()](#SignatureSettings--) | Varsayılan değerlerle varsayılan SignatureSettings örneğini oluşturur. |
|
|  | [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | Logger uygulamasıyla varsayılan SignatureSettings örneğini oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getDefaultCulture()](#getDefaultCulture--) | Belge işleme sırasında kullanılacak varsayılan kültürü alır veya ayarlar. |
|
|  | [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | Belge işleme sırasında kullanılacak varsayılan kültürü alır veya ayarlar. |
|
|  | [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | Silinen imzaları Document Info sonucuna dahil eden bayrağı alır veya ayarlar. |
|
|  | [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | Silinen imzaları Document Info sonucuna dahil eden bayrağı alır veya ayarlar. |
|
|  | [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | Update yöntemi güncellenecek imza içermediğinde kaynak belgeyi yeniden kaydetmek için bayrağı alır veya ayarlar. |
|
|  | [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | Update yöntemi güncellenecek imza içermediğinde kaynak belgeyi yeniden kaydetmek için bayrağı alır veya ayarlar. |
|
|  | [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | Delete yöntemi kaldırılacak etkilenmiş imza içermediğinde kaynak belgeyi yeniden kaydetmek için bayrağı alır veya ayarlar. |
|
|  | [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | Delete yöntemi kaldırılacak etkilenmiş imza içermediğinde kaynak belgeyi yeniden kaydetmek için bayrağı alır veya ayarlar. |
|
|  | [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | Yazar, Sahip, belge oluşturma tarihi, değiştirilme tarihi vb. gibi gömülü standart belge meta verisi imzalarını Metadata Listesine dahil etmek için bayrağı alır veya ayarlar. |
|
|  | [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | Yazar, Sahip, belge oluşturma tarihi, değiştirilme tarihi vb. gibi gömülü standart belge meta verisi imzalarını Metadata Listesine dahil etmek için bayrağı alır veya ayarlar. |
|
|  | [getLogger()](#getLogger--) | Günlükleme (Hatalar, Uyarılar, İzler) için kullanılan logger uygulaması. |
|
|  | [getLogLevel()](#getLogLevel--) | Logger'a iletilen mesaj türlerini alır veya ayarlar. |
|
|  | [setLogLevel(int value)](#setLogLevel-int-) | Logger'a iletilen mesaj türlerini alır veya ayarlar. |
|
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


Varsayılan değerlerle varsayılan SignatureSettings örneğini oluşturur.


### SignatureSettings(ILogger logger) {#SignatureSettings-com.groupdocs.signature.logging.ILogger-}
```
public SignatureSettings(ILogger logger)
```


Logger uygulamasıyla varsayılan SignatureSettings örneğini oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.signature.logging/ilogger) |  |

### getDefaultCulture() {#getDefaultCulture--}
```
public static Locale getDefaultCulture()
```


Belge işleme sırasında kullanılacak varsayılan kültürü alır veya ayarlar. Varsayılan değer "en-US".


**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


Belge işleme sırasında kullanılacak varsayılan kültürü alır veya ayarlar. Varsayılan değer "en-US".


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


Silinen imzaları Document Info sonucuna dahil eden bayrağı alır veya ayarlar.
Her Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) bir Deleted bayrağına sahiptir
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) silinip silinmediğini tespit etmek için.


**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


Silinen imzaları Document Info sonucuna dahil eden bayrağı alır veya ayarlar.
Her Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) bir Deleted bayrağına sahiptir
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) silinip silinmediğini tespit etmek için.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


Update yöntemi güncellenecek imza içermediğinde kaynak belgeyi yeniden kaydetmek için bayrağı alır veya ayarlar.
Bu bayrak true (varsayılan) olarak ayarlanırsa, Update yöntemi güncellenecek imza içermese bile belge ilgili tarih ve işlem türü geçmiş kaydıyla kaydedilecektir.
Bu bayrak false olarak ayarlandığında kaynak belge hiç değiştirilmeyecektir.


**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


Update yöntemi güncellenecek imza içermediğinde kaynak belgeyi yeniden kaydetmek için bayrağı alır veya ayarlar.
Bu bayrak true (varsayılan) olarak ayarlanırsa, Update yöntemi güncellenecek imza içermese bile belge ilgili tarih ve işlem türü geçmiş kaydıyla kaydedilecektir.
Bu bayrak false olarak ayarlandığında kaynak belge hiç değiştirilmeyecektir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


Delete yöntemi kaldırılacak etkilenmiş imza içermediğinde kaynak belgeyi yeniden kaydetmek için bayrağı alır veya ayarlar.
Bu bayrak true (varsayılan) olarak ayarlanırsa, Delete yöntemi kaldırılacak imza içermese bile belge ilgili tarih ve işlem türü geçmiş kaydıyla kaydedilecektir.
Bu bayrak false olarak ayarlandığında kaynak belge hiç değiştirilmeyecektir.


**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


Delete yöntemi kaldırılacak etkilenmiş imza içermediğinde kaynak belgeyi yeniden kaydetmek için bayrağı alır veya ayarlar.
Bu bayrak true (varsayılan) olarak ayarlanırsa, Delete yöntemi kaldırılacak imza içermese bile belge ilgili tarih ve işlem türü geçmiş kaydıyla kaydedilecektir.
Bu bayrak false olarak ayarlandığında kaynak belge hiç değiştirilmeyecektir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


Yazar, Sahip, belge oluşturma tarihi, değiştirilme tarihi vb. gibi gömülü standart belge meta verisi imzalarını Metadata Listesine dahil etmek için bayrağı alır veya ayarlar.
Bu bayrak false (varsayılan) olarak ayarlanırsa GetDocumentInfo bu meta veri imzalarını içermeyecektir.
Bu bayrak true olarak ayarlandığında belge bilgileri bu standart meta veri imzalarını içerecektir.


**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


Yazar, Sahip, belge oluşturma tarihi, değiştirilme tarihi vb. gibi gömülü standart belge meta verisi imzalarını Metadata Listesine dahil etmek için bayrağı alır veya ayarlar.
Bu bayrak false (varsayılan) olarak ayarlanırsa GetDocumentInfo bu meta veri imzalarını içermeyecektir.
Bu bayrak true olarak ayarlandığında belge bilgileri bu standart meta veri imzalarını içerecektir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Günlükleme (Hatalar, Uyarılar, İzler) için kullanılan logger uygulaması. [ILogger](../../com.groupdocs.signature.logging/ilogger).


**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


Logger'a iletilen mesaj türlerini alır veya ayarlar.
Değer, birleştirilebilen [LogLevel](../../com.groupdocs.signature.logging/loglevel) bayraklarından oluşan bir kümedir, örneğin

LogLevel.Error \| LogLevel.Warning
.
LogLevel.None
hiçbir şey kaydetmez.
Varsayılan şudur
LogLevel.All
: hatalar, uyarılar ve izler.


**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


Logger'a iletilen mesaj türlerini alır veya ayarlar.
Değer, birleştirilebilen [LogLevel](../../com.groupdocs.signature.logging/loglevel) bayraklarından oluşan bir kümedir, örneğin

LogLevel.Error \| LogLevel.Warning
.
LogLevel.None
hiçbir şey kaydetmez.
Varsayılan şudur
LogLevel.All
: hatalar, uyarılar ve izler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

