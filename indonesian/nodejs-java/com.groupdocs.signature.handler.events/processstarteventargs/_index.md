---
title: "ProcessStartEventArgs"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Menyediakan data untuk peristiwa Start pada proses verifikasi penandatanganan dan pencarian."
type: docs
weight: 15
url: /id/nodejs-java/com.groupdocs.signature.handler.events/processstarteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessStartEventArgs extends ProcessEventArgs
```

Menyediakan data untuk peristiwa Start pada proses penandatanganan, verifikasi, dan pencarian.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ProcessStartEventArgs()](#ProcessStartEventArgs--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getStarted()](#getStarted--) | Mewakili penanda waktu saat proses dimulai. |
| [setStarted(Date value)](#setStarted-java.util.Date-) | Mewakili penanda waktu saat proses dimulai. |
| [getTotalSignatures()](#getTotalSignatures--) | Mewakili jumlah total tanda tangan yang akan diproses. |
| [setTotalSignatures(int value)](#setTotalSignatures-int-) | Mewakili jumlah total tanda tangan yang akan diproses. |
### ProcessStartEventArgs() {#ProcessStartEventArgs--}
```
public ProcessStartEventArgs()
```


### getStarted() {#getStarted--}
```
public final Date getStarted()
```


Mewakili penanda waktu saat proses dimulai.

**Returns:**
java.util.Date
### setStarted(Date value) {#setStarted-java.util.Date-}
```
public final void setStarted(Date value)
```


Mewakili penanda waktu saat proses dimulai.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Date |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Mewakili jumlah total tanda tangan yang akan diproses.

**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Mewakili jumlah total tanda tangan yang akan diproses.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

