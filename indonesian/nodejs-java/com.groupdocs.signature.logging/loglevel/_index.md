---
title: "LogLevel"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Menentukan tipe Tingkat Log yang tersedia."
type: docs
weight: 12
url: /id/nodejs-java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

Menentukan tipe Log Level yang tersedia. Enumerasi ini dapat digunakan sebagai flag untuk mengatur beberapa nilai yang mungkin sebagai bit yang diaktifkan. Contoh: LogLevel.Error | LogLevel.Warning atau LogLevel.Error | LogLevel.Trace
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [None](#None) | Tidak ada batasan logging, semua informasi akan dicatat mulai dari jejak, peringatan hingga kesalahan |
| [Error](#Error) | Tidak ada batasan logging, semua informasi akan dicatat mulai dari jejak, peringatan hingga kesalahan |
| [Warning](#Warning) | Sama seperti level All, semua pesan termasuk level Trace akan dicatat |
| [Trace](#Trace) | Level pencatatan untuk menyertakan pesan dari level Warning hingga Error |
| [All](#All) | Semua peristiwa level Log (Error, Warning, Trace) akan dimasukkan ke dalam pencatatan |
### None {#None}
```
public static final int None
```


Tidak ada batasan logging, semua informasi akan dicatat mulai dari jejak, peringatan hingga kesalahan

### Error {#Error}
```
public static final int Error
```


Tidak ada batasan logging, semua informasi akan dicatat mulai dari jejak, peringatan hingga kesalahan

### Warning {#Warning}
```
public static final int Warning
```


Sama seperti level All, semua pesan termasuk level Trace akan dicatat

### Trace {#Trace}
```
public static final int Trace
```


Level pencatatan untuk menyertakan pesan dari level Warning hingga Error

### All {#All}
```
public static final int All
```


Semua peristiwa level Log (Error, Warning, Trace) akan dimasukkan ke dalam pencatatan

