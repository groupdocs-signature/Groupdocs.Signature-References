---
title: "PdfMetadataSignature"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Berisi properti tanda tangan Metadata Pdf."
type: docs
weight: 14
url: /id/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

Berisi properti tanda tangan Metadata Pdf.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | Membuat tanda tangan Metadata Pdf dengan nama yang telah ditentukan dan nilai kosong |
| [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | Membuat tanda tangan Metadata Pdf dengan nilai yang telah ditentukan |
| [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | Membuat tanda tangan Metadata Pdf dengan nilai yang telah ditentukan |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTagPrefix()](#getTagPrefix--) | Tag awalan nama tanda tangan Metadata Pdf. |
| [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | Tag awalan nama tanda tangan Metadata Pdf. |
| [equals(Object signature)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
| [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
| [deepClone()](#deepClone--) | Menggandakan instance Metadata Signature. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Menggandakan instance Metadata Signature Pdf dengan nilai yang diberikan. |
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


Membuat tanda tangan Metadata Pdf dengan nama yang telah ditentukan dan nilai kosong

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama Metadata Signature Pdf |

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


Membuat tanda tangan Metadata Pdf dengan nilai yang telah ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama objek Metadata signature |
| nilai | java.lang.Object | Nilai Metadata signature |

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


Membuat tanda tangan Metadata Pdf dengan nilai yang telah ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama objek Metadata signature |
| nilai | java.lang.Object | Nilai Metadata signature |
| tag | java.lang.String | Tag awalan Metadata signature |

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


Tag awalan nama tanda tangan Metadata Pdf. Secara default properti ini diatur ke "xmp". Nilai yang mungkin adalah

**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


Tag awalan nama tanda tangan Metadata Pdf. Secara default properti ini diatur ke "xmp". Nilai yang mungkin adalah

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Menimpa metode Equals untuk membandingkan properti tanda tangan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tanda tangan | java.lang.Object | Objek tanda tangan untuk dibandingkan. |

**Returns:**
boolean - Mengembalikan true jika objek tanda tangan yang diberikan memiliki tipe yang sama dan semua propertinya sama dengan properti instance ini.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Menimpa metode GetHashCode

**Returns:**
int - Kode hash tanda tangan
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Menggandakan instance Metadata Signature.

**Returns:**
java.lang.Object - Mengembalikan instance Metadata Signature yang digandakan
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Menggandakan instance Metadata Signature Pdf dengan nilai yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object | Nilai untuk objek yang digandakan baru. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
