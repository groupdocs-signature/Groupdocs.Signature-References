---
title: "ProcessProgressEventArgs"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "İmza doğrulama ve arama süreçlerinin OnProgress olayı için veri sağlar"
type: docs
weight: 13
url: /tr/java/com.groupdocs.signature.handler.events/processprogresseventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessProgressEventArgs extends ProcessEventArgs
```

İmzalama, doğrulama ve arama süreçlerinin OnProgress olayı için veri sağlar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ProcessProgressEventArgs()](#ProcessProgressEventArgs--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getProgress()](#getProgress--) | İlerlemeyi yüzde olarak temsil eder. |
|
|  | [setProgress(int value)](#setProgress-int-) | İlerlemeyi yüzde olarak temsil eder. |
|
|  | [getTicks()](#getTicks--) | Süreç Başlat olayı sonrası milisaniye cinsinden harcanan zamanı temsil eder |
|
|  | [setTicks(long value)](#setTicks-long-) | Süreç Başlat olayı sonrası milisaniye cinsinden harcanan zamanı temsil eder |
|
|  | [getProcessedSignatures()](#getProcessedSignatures--) | İşlenen imzaların miktarını temsil eder |
|
|  | [setProcessedSignatures(int value)](#setProcessedSignatures-int-) | İşlenen imzaların miktarını temsil eder |
|
|  | [getCancel()](#getCancel--) | Sürecin iptal edilip edilmemesi gerektiğini gösterir |
|
|  | [setCancel(boolean value)](#setCancel-boolean-) | Sürecin iptal edilip edilmemesi gerektiğini gösterir |
|
### ProcessProgressEventArgs() {#ProcessProgressEventArgs--}
```
public ProcessProgressEventArgs()
```


### getProgress() {#getProgress--}
```
public final int getProgress()
```


İlerlemeyi yüzde olarak temsil eder. Değer aralığı 0 ile 100 arasındadır.


**Returns:**
int
### setProgress(int value) {#setProgress-int-}
```
public final void setProgress(int value)
```


İlerlemeyi yüzde olarak temsil eder. Değer aralığı 0 ile 100 arasındadır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Süreç Başlat olayı sonrası milisaniye cinsinden harcanan zamanı temsil eder


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Süreç Başlat olayı sonrası milisaniye cinsinden harcanan zamanı temsil eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getProcessedSignatures() {#getProcessedSignatures--}
```
public final int getProcessedSignatures()
```


İşlenen imzaların miktarını temsil eder


**Returns:**
int
### setProcessedSignatures(int value) {#setProcessedSignatures-int-}
```
public final void setProcessedSignatures(int value)
```


İşlenen imzaların miktarını temsil eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCancel() {#getCancel--}
```
public final boolean getCancel()
```


Sürecin iptal edilip edilmemesi gerektiğini gösterir


**Returns:**
boolean
### setCancel(boolean value) {#setCancel-boolean-}
```
public final void setCancel(boolean value)
```


Sürecin iptal edilip edilmemesi gerektiğini gösterir


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

