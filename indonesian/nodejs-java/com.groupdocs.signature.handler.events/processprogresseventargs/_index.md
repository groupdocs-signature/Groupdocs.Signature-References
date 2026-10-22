---
title: "ProcessProgressEventArgs"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Menyediakan data untuk peristiwa OnProgress pada proses verifikasi penandatanganan dan pencarian."
type: docs
weight: 13
url: /id/nodejs-java/com.groupdocs.signature.handler.events/processprogresseventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessProgressEventArgs extends ProcessEventArgs
```

Menyediakan data untuk peristiwa OnProgress pada proses penandatanganan, verifikasi, dan pencarian.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ProcessProgressEventArgs()](#ProcessProgressEventArgs--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getProgress()](#getProgress--) | Mewakili kemajuan dalam persentase. |
| [setProgress(int value)](#setProgress-int-) | Mewakili kemajuan dalam persentase. |
| [getTicks()](#getTicks--) | Mewakili waktu yang dihabiskan dalam milidetik sejak peristiwa Start proses. |
| [setTicks(long value)](#setTicks-long-) | Mewakili waktu yang dihabiskan dalam milidetik sejak peristiwa Start proses. |
| [getProcessedSignatures()](#getProcessedSignatures--) | Mewakili jumlah tanda tangan yang diproses. |
| [setProcessedSignatures(int value)](#setProcessedSignatures-int-) | Mewakili jumlah tanda tangan yang diproses. |
| [getCancel()](#getCancel--) | Menunjukkan apakah proses harus dibatalkan. |
| [setCancel(boolean value)](#setCancel-boolean-) | Menunjukkan apakah proses harus dibatalkan. |
### ProcessProgressEventArgs() {#ProcessProgressEventArgs--}
```
public ProcessProgressEventArgs()
```


### getProgress() {#getProgress--}
```
public final int getProgress()
```


Mewakili kemajuan dalam persentase. Rentang nilai adalah dari 0 hingga 100.

**Returns:**
int
### setProgress(int value) {#setProgress-int-}
```
public final void setProgress(int value)
```


Mewakili kemajuan dalam persentase. Rentang nilai adalah dari 0 hingga 100.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Mewakili waktu yang dihabiskan dalam milidetik sejak peristiwa Start proses.

**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Mewakili waktu yang dihabiskan dalam milidetik sejak peristiwa Start proses.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### getProcessedSignatures() {#getProcessedSignatures--}
```
public final int getProcessedSignatures()
```


Mewakili jumlah tanda tangan yang diproses.

**Returns:**
int
### setProcessedSignatures(int value) {#setProcessedSignatures-int-}
```
public final void setProcessedSignatures(int value)
```


Mewakili jumlah tanda tangan yang diproses.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getCancel() {#getCancel--}
```
public final boolean getCancel()
```


Menunjukkan apakah proses harus dibatalkan.

**Returns:**
boolean
### setCancel(boolean value) {#setCancel-boolean-}
```
public final void setCancel(boolean value)
```


Menunjukkan apakah proses harus dibatalkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

