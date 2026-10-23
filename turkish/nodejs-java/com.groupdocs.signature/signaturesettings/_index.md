---
title: "SignatureSettings"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Davranışı özelleştirmek için ayarları tanımlar."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

Davranışı özelleştirmek için [Signature](../../com.groupdocs.signature/signature) ayarlarını tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SignatureSettings()](#SignatureSettings--) | Varsayılan değerlerle varsayılan SignatureSettings örneğini oluşturur. |
| [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | Logger uygulamasıyla varsayılan SignatureSettings örneğini oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDefaultCulture()](#getDefaultCulture--) | Belge işleme sırasında kullanılacak varsayılan kültürü alır veya ayarlar. |
| [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | Belge işleme sırasında kullanılacak varsayılan kültürü alır veya ayarlar. |
| [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | Silinen imzaları Document Info sonucuna dahil eden bayrağı alır veya ayarlar. |
| [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | Silinen imzaları Document Info sonucuna dahil eden bayrağı alır veya ayarlar. |
| [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | Update yöntemi güncellenecek imza olmadığında kaynak belgeyi yeniden kaydetme bayrağını alır veya ayarlar. |
| [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | Update yöntemi güncellenecek imza olmadığında kaynak belgeyi yeniden kaydetme bayrağını alır veya ayarlar. |
| [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | Delete yöntemi kaldırılacak etkilenmiş imza olmadığında kaynak belgeyi yeniden kaydetme bayrağını alır veya ayarlar. |
| [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | Delete yöntemi kaldırılacak etkilenmiş imza olmadığında kaynak belgeyi yeniden kaydetme bayrağını alır veya ayarlar. |
| [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | Yazar, Sahip, belge oluşturma tarihi, değiştirilme tarihi vb. gibi gömülü standart belge meta verisi imzalarını Metadata Listesine dahil etme bayrağını alır veya ayarlar. |
| [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | Yazar, Sahip, belge oluşturma tarihi, değiştirilme tarihi vb. gibi gömülü standart belge meta verisi imzalarını Metadata Listesine dahil etme bayrağını alır veya ayarlar. |
| [getLogger()](#getLogger--) | Günlükleme (Hatalar, Uyarılar, İzlemeler) için kullanılan logger uygulaması. |
| [getLogLevel()](#getLogLevel--) | Mesajları sınırlamak için günlükleme seviyesi (Tümü, İzlemeler, Uyarılar, Hatalar). |
| [setLogLevel(int value)](#setLogLevel-int-) | Mesajları sınırlamak için günlükleme seviyesi (Tümü, İzlemeler, Uyarılar, Hatalar). |
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


Silinmiş imzaları Document Info sonucuna dahil eden bayrağı alır veya ayarlar. Her Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) içinde Deleted bayrağı vardır  BaseSignature.Deleted ([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature\#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setDeleted-boolean-)) silinip silinmediğini tespit etmek için.

**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


Silinmiş imzaları Document Info sonucuna dahil eden bayrağı alır veya ayarlar. Her Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) içinde Deleted bayrağı vardır  BaseSignature.Deleted ([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature\#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setDeleted-boolean-)) silinip silinmediğini tespit etmek için.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


Update yöntemi güncellenecek imza içermediğinde kaynak belgeyi yeniden kaydetme bayrağını alır veya ayarlar. Bu bayrak true (varsayılan) olarak ayarlanırsa, Update yöntemi güncellenecek imza olmasa bile belge ilgili tarih ve işlem türü bilgisiyle tarihçe işlem günlüğüyle kaydedilir. Bu bayrak false olarak ayarlanırsa kaynak belge hiç değiştirilmeyecek.

**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


Update yöntemi güncellenecek imza içermediğinde kaynak belgeyi yeniden kaydetme bayrağını alır veya ayarlar. Bu bayrak true (varsayılan) olarak ayarlanırsa, Update yöntemi güncellenecek imza olmasa bile belge ilgili tarih ve işlem türü bilgisiyle tarihçe işlem günlüğüyle kaydedilir. Bu bayrak false olarak ayarlanırsa kaynak belge hiç değiştirilmeyecek.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


Delete yöntemi kaldırılacak etkilenen imza içermediğinde kaynak belgeyi yeniden kaydetme bayrağını alır veya ayarlar. Bu bayrak true (varsayılan) olarak ayarlanırsa, Delete yöntemi kaldırılacak imza olmasa bile belge ilgili tarih ve işlem türü bilgisiyle tarihçe işlem günlüğüyle kaydedilir. Bu bayrak false olarak ayarlanırsa kaynak belge hiç değiştirilmeyecek.

**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


Delete yöntemi kaldırılacak etkilenen imza içermediğinde kaynak belgeyi yeniden kaydetme bayrağını alır veya ayarlar. Bu bayrak true (varsayılan) olarak ayarlanırsa, Delete yöntemi kaldırılacak imza olmasa bile belge ilgili tarih ve işlem türü bilgisiyle tarihçe işlem günlüğüyle kaydedilir. Bu bayrak false olarak ayarlanırsa kaynak belge hiç değiştirilmeyecek.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


Yazar, Sahip, belge oluşturma tarihi, değiştirilme tarihi vb. gibi gömülü standart belge meta verisi imzalarını Metadata Listesine dahil etme bayrağını alır veya ayarlar. Bu bayrak false (varsayılan) olarak ayarlanırsa GetDocumentInfo bu meta veri imzalarını dahil etmeyecek. Bu bayrak true olarak ayarlanırsa belge bilgileri bu standart meta veri imzalarını içerecek.

**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


Yazar, Sahip, belge oluşturma tarihi, değiştirilme tarihi vb. gibi gömülü standart belge meta verisi imzalarını Metadata Listesine dahil etme bayrağını alır veya ayarlar. Bu bayrak false (varsayılan) olarak ayarlanırsa GetDocumentInfo bu meta veri imzalarını dahil etmeyecek. Bu bayrak true olarak ayarlanırsa belge bilgileri bu standart meta veri imzalarını içerecek.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Günlükleme (Hatalar, Uyarılar, İzlemeler) için kullanılan logger uygulaması. [ILogger](../../com.groupdocs.signature.logging/ilogger).

**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


Mesajları sınırlamak için günlükleme seviyesi (All, Traces, Warnings, Errors). LogLevel. Varsayılan olarak All seviyesi ayarlanmıştır.

**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


Mesajları sınırlamak için günlükleme seviyesi (All, Traces, Warnings, Errors). LogLevel. Varsayılan olarak All seviyesi ayarlanmıştır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

