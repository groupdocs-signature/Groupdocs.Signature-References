---
title: "VerificationResult"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Instansi untuk menyimpan hasil proses verifikasi."
type: docs
weight: 20
url: /id/nodejs-java/com.groupdocs.signature.domain/verificationresult/
---
**Inheritance:**
java.lang.Object
```
public class VerificationResult
```

Instansi untuk menyimpan hasil proses verifikasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | Mengembalikan waktu eksekusi proses dalam milidetik. |
| [getTotalSignatures()](#getTotalSignatures--) | Mengembalikan total tanda tangan yang diproses |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Mengembalikan ukuran dokumen sumber dalam byte |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Mengembalikan ukuran dokumen tujuan. |
| [getSucceeded()](#getSucceeded--) | Daftar tanda tangan yang berhasil diverifikasi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [isValid()](#isValid--) | Mengembalikan true jika proses Verifikasi berhasil, jika tidak false. |
| [setValid(boolean value)](#setValid-boolean-) | Mengembalikan true jika proses Verifikasi berhasil, jika tidak false. |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Mengembalikan waktu eksekusi proses dalam milidetik.

**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Mengembalikan total tanda tangan yang diproses

**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Mengembalikan ukuran dokumen sumber dalam byte

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Mengembalikan ukuran dokumen tujuan. Untuk verifikasi variabel ini selalu berisi nol.

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Daftar tanda tangan yang berhasil diverifikasi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). Saat ini properti ini tidak didukung.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### isValid() {#isValid--}
```
public final boolean isValid()
```


Mengembalikan true jika proses Verifikasi berhasil, jika tidak false.

**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Mengembalikan true jika proses Verifikasi berhasil, jika tidak false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

