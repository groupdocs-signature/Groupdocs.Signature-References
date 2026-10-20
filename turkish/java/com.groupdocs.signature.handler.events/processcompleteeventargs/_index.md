---
title: "ProcessCompleteEventArgs"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "İmza doğrulama ve arama süreçlerinin tamamlanma (complete) olayı için veri sağlar"
type: docs
weight: 10
url: /tr/java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

İmzalama, doğrulama ve arama süreçlerinin tamamlanma olayıyla ilgili verileri sağlar.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getCompleted()](#getCompleted--) | Sürecin tamamlanma zaman işaretini temsil eder |
|
|  | [setCompleted(Date value)](#setCompleted-java.util.Date-) | Sürecin tamamlanma zaman işaretini temsil eder |
|
|  | [getTicks()](#getTicks--) | Süreç Başlat olayı sonrası milisaniye cinsinden harcanan zamanı temsil eder |
|
|  | [setTicks(long value)](#setTicks-long-) | Süreç Başlat olayı sonrası milisaniye cinsinden harcanan zamanı temsil eder |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | İşlenen imzaların toplam miktarını temsil eder. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | İşlenen imzaların toplam miktarını temsil eder. |
|
|  | [getCanceled()](#getCanceled--) | İşlemin iptal edilip edilmediğini gösterir. |
|
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


Sürecin tamamlanma zaman işaretini temsil eder


**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


Sürecin tamamlanma zaman işaretini temsil eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

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

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


İşlenen imzaların toplam miktarını temsil eder.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


İşlenen imzaların toplam miktarını temsil eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCanceled() {#getCanceled--}
```
public final boolean getCanceled()
```


İşlemin iptal edilip edilmediğini gösterir.


**Returns:**
boolean
