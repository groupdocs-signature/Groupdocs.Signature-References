---
title: "ProcessLog"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mewakili detail proses dokumen."
type: docs
weight: 15
url: /id/java/com.groupdocs.signature.domain/processlog/
---
**Inheritance:**
java.lang.Object
```
public final class ProcessLog
```

Mewakili detail proses dokumen.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getDate()](#getDate--) | Dapatkan tanggal dan waktu proses. |
|
|  | [getType()](#getType--) | Dapatkan tipe proses. |
|
|  | [getMessage()](#getMessage--) | Dapatkan deskripsi proses. |
|
|  | [getSucceeded()](#getSucceeded--) | Jumlah tanda tangan yang berhasil diproses. |
|
|  | [getFailed()](#getFailed--) | Jumlah tanda tangan yang gagal selama pemrosesan. |
|
|  | [getSignatures()](#getSignatures--) | Daftar tanda tangan yang berhasil diproses. |
|
### getDate() {#getDate--}
```
public final Date getDate()
```


Dapatkan tanggal dan waktu proses.


**Returns:**
java.util.Date
### getType() {#getType--}
```
public final int getType()
```


Dapatkan tipe proses.


**Returns:**
int
### getMessage() {#getMessage--}
```
public final String getMessage()
```


Dapatkan deskripsi proses.


**Returns:**
java.lang.String
### getSucceeded() {#getSucceeded--}
```
public final int getSucceeded()
```


Jumlah tanda tangan yang berhasil diproses.


**Returns:**
int
### getFailed() {#getFailed--}
```
public final int getFailed()
```


Jumlah tanda tangan yang gagal selama pemrosesan.


**Returns:**
int
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Daftar tanda tangan yang berhasil diproses.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
