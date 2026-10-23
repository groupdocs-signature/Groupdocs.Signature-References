---
title: "ProcessCompleteEventArgs"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "İmza doğrulama ve arama işlemlerinin tamamlama olayı için veri sağlar."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

İmzalama, doğrulama ve arama süreçlerinin tam olayına ilişkin verileri sağlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCompleted()](#getCompleted--) | İşlem tamamlanma zaman işaretini temsil eder. |
| [setCompleted(Date value)](#setCompleted-java.util.Date-) | İşlem tamamlanma zaman işaretini temsil eder. |
| [getTicks()](#getTicks--) | İşlem Başlat olayı itibarıyla harcanan zamanı milisaniye cinsinden temsil eder. |
| [setTicks(long value)](#setTicks-long-) | İşlem Başlat olayı itibarıyla harcanan zamanı milisaniye cinsinden temsil eder. |
| [getTotalSignatures()](#getTotalSignatures--) | İşlenen imzaların toplam miktarını temsil eder. |
| [setTotalSignatures(int value)](#setTotalSignatures-int-) | İşlenen imzaların toplam miktarını temsil eder. |
| [getCanceled()](#getCanceled--) | İşlemin iptal edilip edilmediğini gösterir. |
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


İşlem tamamlanma zaman işaretini temsil eder.

**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


İşlem tamamlanma zaman işaretini temsil eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


İşlem Başlat olayı itibarıyla harcanan zamanı milisaniye cinsinden temsil eder.

**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


İşlem Başlat olayı itibarıyla harcanan zamanı milisaniye cinsinden temsil eder.

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
