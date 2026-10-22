---
title: "PresentationMetadataSignature"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Berisi properti tanda tangan metadata Presentasi."
type: docs
weight: 16
url: /id/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/presentationmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PresentationMetadataSignature extends MetadataSignature
```

Berisi properti tanda tangan metadata Presentasi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PresentationMetadataSignature(String name)](#PresentationMetadataSignature-java.lang.String-) | Membuat Presentation Metadata Signature dengan nama yang telah ditentukan dan nilai kosong |
| [PresentationMetadataSignature(String name, Object value)](#PresentationMetadataSignature-java.lang.String-java.lang.Object-) | Membuat Presentation Metadata Signature dengan nilai yang telah ditentukan |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone()](#deepClone--) | Menggandakan instance Metadata Signature. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Menggandakan instance Slides Metadata Signature dengan nilai yang diberikan. |
| [toString()](#toString--) | Mengonversi ke String dengan metode ToString() yang ditimpa |
| [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | Mengonversi ke String dengan format yang ditentukan |
### PresentationMetadataSignature(String name) {#PresentationMetadataSignature-java.lang.String-}
```
public PresentationMetadataSignature(String name)
```


Membuat Presentation Metadata Signature dengan nama yang telah ditentukan dan nilai kosong

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama Tanda Tangan Metadata Presentasi |

### PresentationMetadataSignature(String name, Object value) {#PresentationMetadataSignature-java.lang.String-java.lang.Object-}
```
public PresentationMetadataSignature(String name, Object value)
```


Membuat Presentation Metadata Signature dengan nilai yang telah ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama objek Metadata signature |
| nilai | java.lang.Object | Nilai Metadata signature |

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


Menggandakan instance Slides Metadata Signature dengan nilai yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object | Nilai untuk objek yang digandakan baru. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
### toString() {#toString--}
```
public String toString()
```


Mengonversi ke String dengan metode ToString() yang ditimpa

**Returns:**
java.lang.String - Mengembalikan nilai Tanda Tangan Metadata sebagai String.

--------------------

Mengonversi properti boolean menjadi "True" atau "False". Untuk tipe data lain, penyedia format data default akan digunakan.
### toString(String format, System.IFormatProvider provider) {#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-}
```
public String toString(String format, System.IFormatProvider provider)
```


Mengonversi ke String dengan format yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | java.lang.String | String format data. |
|  | penyedia | com.aspose.ms.System.IFormatProvider | Penyedia format data untuk digunakan dengan operasi konversi data. |

--------------------

Mengonversi properti boolean menjadi "True" atau "False". |

**Returns:**
java.lang.String - Mengembalikan nilai Tanda Tangan Metadata sebagai String.
