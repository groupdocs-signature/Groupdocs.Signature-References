---
title: "MetadataSignOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mewakili opsi tanda tangan Metadata."
type: docs
weight: 14
url: /id/java/com.groupdocs.signature.options.sign/metadatasignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
```
public class MetadataSignOptions extends SignOptions
```

Mewakili opsi tanda tangan Metadata.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [MetadataSignOptions()](#MetadataSignOptions--) | Menginisialisasi instance baru dari kelas SignMetadataOptions dengan nilai default. |
|
|  | [MetadataSignOptions(ArrayList<MetadataSignature> signatures)](#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--) | Menginisialisasi instance baru dari kelas SignMetadataOptions dengan Metadata. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getSignatures()](#getSignatures--) | Mendapatkan atau mengatur Metadata tanda tangan. |
|
|  | [setSignatures(MetadataSignatureCollection value)](#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-) | Mendapatkan atau mengatur Metadata tanda tangan. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi teks atau properti Data tanda tangan QR-Code. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi teks atau properti Data tanda tangan QR-Code. |
|
|  | [addPdfSignature(String name, Object value, String tag)](#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-) | Membuat PdfMetadataSignature baru dengan argumen yang diberikan dan menambahkannya ke koleksi. |
|
|  | [addImageSignature(int id, Object value)](#addImageSignature-int-java.lang.Object-) | Membuat ImageMetadataSignature baru dengan argumen yang diberikan dan menambahkannya ke koleksi. |
|
|  | [add(MetadataSignature metadataSignature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Tambahkan instance MetadataSignature yang ada ke koleksi. |
|
|  | [validate()](#validate--) | Metode internal untuk memvalidasi parameter opsi. |
|
|  | [toString()](#toString--) | Timpa konversi string. |
|
| [signature()](#signature--) |  |
### MetadataSignOptions() {#MetadataSignOptions--}
```
public MetadataSignOptions()
```


Menginisialisasi instance baru dari kelas SignMetadataOptions dengan nilai default.


### MetadataSignOptions(ArrayList<MetadataSignature> signatures) {#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--}
```
public MetadataSignOptions(ArrayList<MetadataSignature> signatures)
```


Menginisialisasi instance baru dari kelas SignMetadataOptions dengan Metadata.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | signatures | java.util.ArrayList<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature> | Koleksi Tanda Tangan Metadata [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature). |
|

### getSignatures() {#getSignatures--}
```
public final MetadataSignatureCollection getSignatures()
```


Mendapatkan atau mengatur Metadata tanda tangan.


**Returns:**
[MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection)
### setSignatures(MetadataSignatureCollection value) {#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-}
```
public final void setSignatures(MetadataSignatureCollection value)
```


Mendapatkan atau mengatur Metadata tanda tangan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi teks atau properti Data tanda tangan QR-Code.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi teks atau properti Data tanda tangan QR-Code.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### addPdfSignature(String name, Object value, String tag) {#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public final PdfMetadataSignature addPdfSignature(String name, Object value, String tag)
```


Membuat PdfMetadataSignature baru dengan argumen yang diberikan dan menambahkannya ke koleksi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama objek tanda tangan Metadata |
|
|  | nilai | java.lang.Object | Nilai tanda tangan Metadata |
|
|  | tag | java.lang.String | Tag awalan tanda tangan Metadata |
|

**Returns:**
[PdfMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### addImageSignature(int id, Object value) {#addImageSignature-int-java.lang.Object-}
```
public final ImageMetadataSignature addImageSignature(int id, Object value)
```


Membuat ImageMetadataSignature baru dengan argumen yang diberikan dan menambahkannya ke koleksi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | id | int | Pengidentifikasi unik nama Tanda Tangan Metadata Gambar. Lihat referensi untuk spesifikasi tag Exif untuk nilai id yang mungkin |
|
|  | nilai | java.lang.Object | Nilai Metadata |
|

**Returns:**
[ImageMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### add(MetadataSignature metadataSignature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final MetadataSignOptions add(MetadataSignature metadataSignature)
```


Tambahkan instance MetadataSignature yang ada ke koleksi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | metadataSignature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Instansi MetadataSignature yang ada untuk ditambahkan |
|

**Returns:**
[MetadataSignOptions](../../com.groupdocs.signature.options.sign/metadatasignoptions) - Instance itself

### validate() {#validate--}
```
public void validate()
```


Metode internal untuk memvalidasi parameter opsi.


### toString() {#toString--}
```
public String toString()
```


Timpa konversi string.


**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
