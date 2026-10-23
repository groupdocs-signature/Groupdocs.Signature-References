---
title: "ProcessStartEventArgs"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "İmza doğrulama ve arama için Start olayı veri sağlar."
type: docs
weight: 15
url: /tr/nodejs-java/com.groupdocs.signature.handler.events/processstarteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessStartEventArgs extends ProcessEventArgs
```

İmzalama, doğrulama ve arama sürecinin Start olayı için veri sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ProcessStartEventArgs()](#ProcessStartEventArgs--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getStarted()](#getStarted--) | Sürecin başlangıç zaman işaretini temsil eder. |
| [setStarted(Date value)](#setStarted-java.util.Date-) | Sürecin başlangıç zaman işaretini temsil eder. |
| [getTotalSignatures()](#getTotalSignatures--) | İşlenecek imzaların toplam miktarını temsil eder. |
| [setTotalSignatures(int value)](#setTotalSignatures-int-) | İşlenecek imzaların toplam miktarını temsil eder. |
### ProcessStartEventArgs() {#ProcessStartEventArgs--}
```
public ProcessStartEventArgs()
```


### getStarted() {#getStarted--}
```
public final Date getStarted()
```


Sürecin başlangıç zaman işaretini temsil eder.

**Returns:**
java.util.Date
### setStarted(Date value) {#setStarted-java.util.Date-}
```
public final void setStarted(Date value)
```


Sürecin başlangıç zaman işaretini temsil eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


İşlenecek imzaların toplam miktarını temsil eder.

**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


İşlenecek imzaların toplam miktarını temsil eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

