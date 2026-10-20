---
title: "QrCodeSearchOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mewakili opsi pencarian abstrak untuk tanda tangan QR-Code."
type: docs
weight: 16
url: /id/java/com.groupdocs.signature.options.search/qrcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class QrCodeSearchOptions extends SearchOptions
```

Mewakili opsi pencarian abstrak untuk tanda tangan QR-Code.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [QrCodeSearchOptions()](#QrCodeSearchOptions--) | Menginisialisasi instance baru dari kelas QRCodeSearchOptions dengan nilai default. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Menginisialisasi instance baru dari kelas QRCodeSearchOptions dengan nilai tipe enkode. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType, String text)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-) | Menginisialisasi instance baru dari kelas QRCodeSearchOptions dengan nilai tipe enkode dan teks. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Menentukan properti Tipe Enkode untuk mencari QR-Code. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Menentukan properti Tipe Enkode untuk mencari QR-Code. |
|
|  | [getText()](#getText--) | Menentukan Teks Tanda Tangan QR-Code jika harus dicari dan dicocokkan. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Menentukan Teks Tanda Tangan QR-Code jika harus dicari dan dicocokkan. |
|
|  | [getMatchType()](#getMatchType--) | Mendapatkan atau mengatur pencarian Tipe Kecocokan Teks QR-Code. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Mendapatkan atau mengatur pencarian Tipe Kecocokan Teks QR-Code. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi teks atau properti Data tanda tangan QR-Code. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi teks atau properti Data tanda tangan QR-Code. |
|
|  | [getReturnContent()](#getReturnContent--) | Mendapatkan atau mengatur bendera untuk mengambil konten gambar QR-Code dari tanda tangan pada halaman dokumen. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Mendapatkan atau mengatur bendera untuk mengambil konten gambar QR-Code dari tanda tangan pada halaman dokumen. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Menentukan jenis file dari konten gambar yang dikembalikan dari tanda tangan QR-Code ketika properti ReturnContent diaktifkan. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Menentukan jenis file dari konten gambar yang dikembalikan dari tanda tangan QR-Code ketika properti ReturnContent diaktifkan. |
|
### QrCodeSearchOptions() {#QrCodeSearchOptions--}
```
public QrCodeSearchOptions()
```


Menginisialisasi instance baru dari kelas QRCodeSearchOptions dengan nilai default.


### QrCodeSearchOptions(QrCodeType encodeType) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSearchOptions(QrCodeType encodeType)
```


Menginisialisasi instance baru dari kelas QRCodeSearchOptions dengan nilai tipe enkode.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Menentukan tipe enkode QR-Code. |
|

### QrCodeSearchOptions(QrCodeType encodeType, String text) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-}
```
public QrCodeSearchOptions(QrCodeType encodeType, String text)
```


Menginisialisasi instance baru dari kelas QRCodeSearchOptions dengan nilai tipe enkode dan teks.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Menentukan tipe enkode QR-Code. |
|
|  | teks | java.lang.String | Atur Teks dari tanda tangan QR-Code. |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Menentukan properti Tipe Enkode untuk mencari QR-Code.
Jika nilai ini tidak diatur, pencarian diproses untuk semua Tipe QR-Code yang didukung.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Menentukan properti Tipe Enkode untuk mencari QR-Code.
Jika nilai ini tidak diatur, pencarian diproses untuk semua Tipe QR-Code yang didukung.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Menentukan Teks Tanda Tangan QR-Code jika harus dicari dan dicocokkan.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Menentukan Teks Tanda Tangan QR-Code jika harus dicari dan dicocokkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Mendapatkan atau mengatur pencarian Tipe Kecocokan Teks QR-Code. Hanya digunakan ketika properti Text diatur.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Mendapatkan atau mengatur pencarian Tipe Kecocokan Teks QR-Code. Hanya digunakan ketika properti Text diatur.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Mendapatkan atau mengatur bendera untuk mengambil konten gambar QR-Code dari tanda tangan pada halaman dokumen.
Jika flag ini diatur true, konten gambar tanda tangan QR-Code akan mempertahankan data gambar mentah dalam format yang diperlukan.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Secara default opsi ini dinonaktifkan.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Mendapatkan atau mengatur bendera untuk mengambil konten gambar QR-Code dari tanda tangan pada halaman dokumen.
Jika flag ini diatur true, konten gambar tanda tangan QR-Code akan mempertahankan data gambar mentah dalam format yang diperlukan.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Secara default opsi ini dinonaktifkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Menentukan jenis file dari konten gambar yang dikembalikan dari tanda tangan QR-Code ketika properti ReturnContent diaktifkan.
Secara default diatur ke Null. Itu berarti mengembalikan konten gambar QR-Code dalam format asli.
Format gambar ini ditentukan di
QrCodeSignature.Format
()
Nilai yang didukung antara lain: FileType.JPEG, FileType.PNG, FileType.BMP.
Jika format yang diberikan tidak didukung, maka konten gambar QR-Code dalam .png asli akan dikembalikan.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Menentukan jenis file dari konten gambar yang dikembalikan dari tanda tangan QR-Code ketika properti ReturnContent diaktifkan.
Secara default diatur ke Null. Itu berarti mengembalikan konten gambar QR-Code dalam format asli.
Format gambar ini ditentukan di
QrCodeSignature.Format
()
Nilai yang didukung antara lain: FileType.JPEG, FileType.PNG, FileType.BMP.
Jika format yang diberikan tidak didukung, maka konten gambar QR-Code dalam .png asli akan dikembalikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

