---
title: "DigitalSearchOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mewakili opsi dasar untuk pencarian tanda tangan Digital."
type: docs
weight: 12
url: /id/java/com.groupdocs.signature.options.search/digitalsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class DigitalSearchOptions extends SearchOptions
```

Mewakili opsi dasar untuk pencarian tanda tangan Digital.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [DigitalSearchOptions()](#DigitalSearchOptions--) | Menginisialisasi instance baru dari kelas DigitalSearchOptions dengan nilai default. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getComments()](#getComments--) | Komentar tanda tangan Digital untuk dicari. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Komentar tanda tangan Digital untuk dicari. |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Rentang tanggal dan waktu tanda tangan Digital untuk dicari. |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Rentang tanggal dan waktu tanda tangan Digital untuk dicari. |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | Rentang tanggal dan waktu Digital Signature untuk dicari. |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Rentang tanggal dan waktu Digital Signature untuk dicari. |
|
|  | [getSubjectName()](#getSubjectName--) | Untuk nilai yang tidak kosong, menentukan distinguished subject name dari sertifikat yang akan dicari. |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Untuk nilai yang tidak kosong, menentukan distinguished subject name dari sertifikat yang akan dicari. |
|
|  | [getIssuerName()](#getIssuerName--) | Untuk nilai yang tidak kosong, menentukan distinguished name penerbit sertifikat yang akan dicari. |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Untuk nilai yang tidak kosong, menentukan distinguished name penerbit sertifikat yang akan dicari. |
|
### DigitalSearchOptions() {#DigitalSearchOptions--}
```
public DigitalSearchOptions()
```


Menginisialisasi instance baru dari kelas DigitalSearchOptions dengan nilai default.


### getComments() {#getComments--}
```
public final String getComments()
```


Komentar tanda tangan Digital untuk dicari.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Komentar tanda tangan Digital untuk dicari.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public final Date getSignDateTimeFrom()
```


Rentang tanggal dan waktu tanda tangan digital yang akan dicari. Nilai yang dapat null akan diabaikan.


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public final void setSignDateTimeFrom(Date value)
```


Rentang tanggal dan waktu tanda tangan digital yang akan dicari. Nilai yang dapat null akan diabaikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public final Date getSignDateTimeTo()
```


Rentang tanggal dan waktu Digital Signature yang akan dicari. Nilai yang dapat null akan diabaikan.


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public final void setSignDateTimeTo(Date value)
```


Rentang tanggal dan waktu Digital Signature yang akan dicari. Nilai yang dapat null akan diabaikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Date |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Untuk nilai yang tidak kosong, menentukan distinguished subject name dari sertifikat yang akan dicari.


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Untuk nilai yang tidak kosong, menentukan distinguished subject name dari sertifikat yang akan dicari.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Untuk nilai yang tidak kosong, menentukan distinguished name penerbit sertifikat yang akan dicari.


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Untuk nilai yang tidak kosong, menentukan distinguished name penerbit sertifikat yang akan dicari.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

