---
title: "ProcessCompleteEventArgs"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Menyediakan data pada peristiwa selesai verifikasi penandatanganan dan proses pencarian."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

Menyediakan data pada peristiwa selesai proses penandatanganan, verifikasi, dan pencarian.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCompleted()](#getCompleted--) | Mewakili penanda waktu penyelesaian proses. |
| [setCompleted(Date value)](#setCompleted-java.util.Date-) | Mewakili penanda waktu penyelesaian proses. |
| [getTicks()](#getTicks--) | Mewakili waktu dalam milidetik yang dihabiskan sejak peristiwa Mulai proses. |
| [setTicks(long value)](#setTicks-long-) | Mewakili waktu dalam milidetik yang dihabiskan sejak peristiwa Mulai proses. |
| [getTotalSignatures()](#getTotalSignatures--) | Mewakili jumlah total tanda tangan yang diproses. |
| [setTotalSignatures(int value)](#setTotalSignatures-int-) | Mewakili jumlah total tanda tangan yang diproses. |
| [getCanceled()](#getCanceled--) | Menunjukkan apakah proses dibatalkan. |
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


Mewakili penanda waktu penyelesaian proses.

**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


Mewakili penanda waktu penyelesaian proses.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Date |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Mewakili waktu dalam milidetik yang dihabiskan sejak peristiwa Mulai proses.

**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Mewakili waktu dalam milidetik yang dihabiskan sejak peristiwa Mulai proses.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Mewakili jumlah total tanda tangan yang diproses.

**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Mewakili jumlah total tanda tangan yang diproses.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getCanceled() {#getCanceled--}
```
public final boolean getCanceled()
```


Menunjukkan apakah proses dibatalkan.

**Returns:**
boolean
