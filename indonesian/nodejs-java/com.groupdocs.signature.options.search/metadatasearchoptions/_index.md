---
title: "MetadataSearchOptions"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Mewakili Opsi pencarian abstrak untuk tanda tangan Metadata."
type: docs
weight: 15
url: /id/nodejs-java/com.groupdocs.signature.options.search/metadatasearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class MetadataSearchOptions extends SearchOptions
```

Mewakili Opsi pencarian abstrak untuk tanda tangan Metadata.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MetadataSearchOptions()](#MetadataSearchOptions--) | Menginisialisasi instance baru dari kelas SearchMetadataOptions dengan nilai default. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getName()](#getName--) | Menentukan nama Tanda Tangan Metadata jika harus dicari dan dicocokkan. |
| [setName(String value)](#setName-java.lang.String-) | Menentukan nama Tanda Tangan Metadata jika harus dicari dan dicocokkan. |
| [getNameMatchType()](#getNameMatchType--) | Mendapatkan atau mengatur tipe pencocokan nama Metadata. |
| [setNameMatchType(int value)](#setNameMatchType-int-) | Mendapatkan atau mengatur tipe pencocokan nama Metadata. |
| [getIncludeBuiltinProperties()](#getIncludeBuiltinProperties--) | Menunjukkan apakah properti dokumen bawaan seperti statistik Dokumen, informasi, dll harus disertakan dalam hasil Pencarian. |
| [setIncludeBuiltinProperties(boolean value)](#setIncludeBuiltinProperties-boolean-) | Menunjukkan apakah properti dokumen bawaan seperti statistik Dokumen, informasi, dll harus disertakan dalam hasil Pencarian. |
| [getDataEncryption()](#getDataEncryption--) | Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi properti Teks atau Data Tanda Tangan QR-Code. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi properti Teks atau Data Tanda Tangan QR-Code. |
### MetadataSearchOptions() {#MetadataSearchOptions--}
```
public MetadataSearchOptions()
```


Menginisialisasi instance baru dari kelas SearchMetadataOptions dengan nilai default.

### getName() {#getName--}
```
public final String getName()
```


Menentukan nama Tanda Tangan Metadata jika harus dicari dan dicocokkan.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Menentukan nama Tanda Tangan Metadata jika harus dicari dan dicocokkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getNameMatchType() {#getNameMatchType--}
```
public final int getNameMatchType()
```


Mendapatkan atau mengatur tipe pencocokan nama Metadata. Hanya digunakan ketika properti Name diatur.

**Returns:**
int
### setNameMatchType(int value) {#setNameMatchType-int-}
```
public final void setNameMatchType(int value)
```


Mendapatkan atau mengatur tipe pencocokan nama Metadata. Hanya digunakan ketika properti Name diatur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getIncludeBuiltinProperties() {#getIncludeBuiltinProperties--}
```
public final boolean getIncludeBuiltinProperties()
```


Menunjukkan apakah properti dokumen bawaan seperti statistik Dokumen, informasi, dll harus disertakan dalam hasil Pencarian. Bendera ini relevan untuk tipe file dokumen Presentasi, Spreadsheet, dan Pengolahan Kata.

**Returns:**
boolean
### setIncludeBuiltinProperties(boolean value) {#setIncludeBuiltinProperties-boolean-}
```
public final void setIncludeBuiltinProperties(boolean value)
```


Menunjukkan apakah properti dokumen bawaan seperti statistik Dokumen, informasi, dll harus disertakan dalam hasil Pencarian. Bendera ini relevan untuk tipe file dokumen Presentasi, Spreadsheet, dan Pengolahan Kata.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi properti Teks atau Data Tanda Tangan QR-Code.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi properti Teks atau Data Tanda Tangan QR-Code.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

