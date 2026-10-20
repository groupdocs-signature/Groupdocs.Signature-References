---
title: "LogLevel"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Menentukan jenis Tingkat Log yang tersedia."
type: docs
weight: 12
url: /id/java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

Menentukan jenis Tingkat Log yang tersedia.
Enum ini dapat digunakan sebagai flag untuk mengatur beberapa nilai yang memungkinkan sebagai bit yang diaktifkan
Contoh: LogLevel.Error \| LogLevel.Warning atau LogLevel.Error \| LogLevel.Trace

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [None](#None) | Tidak ada batasan logging, semua informasi akan dicatat dari jejak, peringatan hingga error |
|
|  | [Error](#Error) | Tidak ada batasan logging, semua informasi akan dicatat dari jejak, peringatan hingga error |
|
|  | [Warning](#Warning) | Sama seperti level All, semua pesan termasuk level Jejak akan dicatat |
|
|  | [Trace](#Trace) | Level logging untuk menyertakan pesan dari level Peringatan hingga Error |
|
|  | [All](#All) | Semua peristiwa level Log (Error, Warning, Trace) akan dimasukkan ke dalam logging |
|
### None {#None}
```
public static final int None
```


Tidak ada batasan logging, semua informasi akan dicatat dari jejak, peringatan hingga error


### Error {#Error}
```
public static final int Error
```


Tidak ada batasan logging, semua informasi akan dicatat dari jejak, peringatan hingga error


### Warning {#Warning}
```
public static final int Warning
```


Sama seperti level All, semua pesan termasuk level Jejak akan dicatat


### Trace {#Trace}
```
public static final int Trace
```


Level logging untuk menyertakan pesan dari level Peringatan hingga Error


### All {#All}
```
public static final int All
```


Semua peristiwa level Log (Error, Warning, Trace) akan dimasukkan ke dalam logging


