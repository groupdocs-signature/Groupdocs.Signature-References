---
title: "DocumentResultSignature"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Hasil pemrosesan proses penandatanganan dokumen arsip untuk dokumen dengan tanda tangan yang baru dibuat."
type: docs
weight: 13
url: /id/java/com.groupdocs.signature.domain.signatures/documentresultsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DocumentResultSignature extends BaseSignature
```

Hasil pemrosesan proses penandatanganan dokumen arsip untuk dokumen dengan tanda tangan yang baru dibuat.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFileName()](#getFileName--) | Nama file dokumen |
|
|  | [getProcessingTime()](#getProcessingTime--) | Mengembalikan waktu eksekusi proses dalam milidetik |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Mengembalikan total tanda tangan yang diproses |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Mengembalikan ukuran dokumen sumber |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Mengembalikan ukuran dokumen tujuan |
|
|  | [getSucceeded()](#getSucceeded--) | Daftar tanda tangan yang berhasil diproses [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Daftar tanda tangan yang gagal selama proses [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getErrorMessage()](#getErrorMessage--) | Jika dokumen diproses dengan kesalahan, properti ini akan berisi pesan error |
|
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Nama file dokumen


**Returns:**
java.lang.String
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Mengembalikan waktu eksekusi proses dalam milidetik


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


Mengembalikan ukuran dokumen sumber


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Mengembalikan ukuran dokumen tujuan


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Daftar tanda tangan yang berhasil diproses [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Daftar tanda tangan yang gagal selama proses [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getErrorMessage() {#getErrorMessage--}
```
public final String getErrorMessage()
```


Jika dokumen diproses dengan kesalahan, properti ini akan berisi pesan error


**Returns:**
java.lang.String
