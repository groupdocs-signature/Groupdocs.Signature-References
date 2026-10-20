---
title: "SignResult"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Hasil proses penandatanganan dokumen dengan tanda tangan yang baru dibuat."
type: docs
weight: 17
url: /id/java/com.groupdocs.signature.domain/signresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class SignResult implements IResult
```

Hasil proses penandatanganan dokumen dengan tanda tangan yang baru dibuat.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Mengembalikan waktu eksekusi proses dalam milidetik |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Mengembalikan total tanda tangan yang diproses |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Mengembalikan ukuran dokumen sumber |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Mengembalikan ukuran dokumen tujuan |
|
|  | [getSucceeded()](#getSucceeded--) | Daftar tanda tangan yang baru dibuat [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Daftar tanda tangan yang gagal dibuat. |
|
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


Daftar tanda tangan yang baru dibuat [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Daftar tanda tangan yang gagal dibuat.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
