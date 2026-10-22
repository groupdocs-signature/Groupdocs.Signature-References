---
title: "SearchResult"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Hasil pencarian tanda tangan dalam dokumen yang ditentukan."
type: docs
weight: 16
url: /id/nodejs-java/com.groupdocs.signature.domain/searchresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class SearchResult implements Iterable<BaseSignature>
```

Hasil pencarian tanda tangan dalam dokumen yang ditentukan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | Mengembalikan waktu eksekusi proses pencarian dalam milidetik. |
| [getTotalSignatures()](#getTotalSignatures--) | Mengembalikan total tanda tangan yang diproses oleh proses pencarian |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Mengembalikan ukuran dokumen sumber |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Mengembalikan ukuran dokumen tujuan. |
| [getSucceeded()](#getSucceeded--) | Daftar tanda tangan yang ditemukan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | Daftar tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang gagal proses Pencarian berdasarkan kriteria pencarian. |
| [getSignatures()](#getSignatures--) | Daftar tanda tangan yang terdeteksi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | Menyediakan konversi ke daftar tanda tangan dengan tipe kuat. |
| [updateContextData(SearchContext context, int documentType)](#updateContextData-com.groupdocs.signature.provider.SearchContext-int-) |  |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Mengembalikan waktu eksekusi proses pencarian dalam milidetik.

**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Mengembalikan total tanda tangan yang diproses oleh proses pencarian

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


Mengembalikan ukuran dokumen tujuan. Untuk metode Search selalu mengembalikan 0.

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Daftar tanda tangan yang ditemukan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). Daftar ini akan selalu sama dengan properti Signatures (\#getSignatures.getSignatures/\#setSignatures(List).setSignatures(List)).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Daftar tanda tangan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) yang gagal proses Pencarian berdasarkan kriteria pencarian. Tidak didukung pada versi saat ini.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Daftar tanda tangan yang terdeteksi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### <T>toList(Class<T> typeOfT) {#-T-toList-java.lang.Class-T--}
```
public final List<T> <T>toList(Class<T> typeOfT)
```


Menyediakan konversi ke daftar tanda tangan dengan tipe kuat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Mengembalikan daftar tipe tanda tangan yang diberikan.

T : Tipe tanda tangan dalam daftar.
### updateContextData(SearchContext context, int documentType) {#updateContextData-com.groupdocs.signature.provider.SearchContext-int-}
```
public final void updateContextData(SearchContext context, int documentType)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| context | [SearchContext](../../com.groupdocs.signature.provider/searchcontext) |  |
| documentType | int |  |

