---
title: "BarcodeSignOptions"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Mewakili opsi Barcode signature."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

Mewakili opsi Barcode signature.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BarcodeSignOptions()](#BarcodeSignOptions--) | Menginisialisasi instance baru dari kelas BarcodeSignOptions dengan nilai default. |
| [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | Menginisialisasi instance baru dari kelas BarcodeSignOptions dengan teks. |
| [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Menginisialisasi instance baru dari kelas BarcodeSignOptions dengan teks. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Mendapatkan atau mengatur tipe Barcode. |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Mendapatkan atau mengatur tipe Barcode. |
| [getForeColor()](#getForeColor--) | Mendapatkan atau mengatur warna depan (Fore) dari batang Barcode. Penggunaan properti ini dapat menyebabkan masalah pada verifikasi. |
| [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Mendapatkan atau mengatur warna depan (Fore) dari batang Barcode. Penggunaan properti ini dapat menyebabkan masalah pada verifikasi. |
| [setForeColor(String value)](#setForeColor-java.lang.String-) | Mendapatkan atau mengatur warna depan (Fore) dari batang Barcode. Penggunaan properti ini dapat menyebabkan masalah pada verifikasi. |
| [getInnerMargins()](#getInnerMargins--) | Mendapatkan atau mengatur jarak antara elemen Barcode dan batas gambar hasil. |
| [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Mendapatkan atau mengatur jarak antara elemen Barcode dan batas gambar hasil. |
| [getCodeTextAlignment()](#getCodeTextAlignment--) | Mendapatkan atau mengatur perataan teks dalam gambar Barcode hasil. |
| [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Mendapatkan atau mengatur perataan teks dalam gambar Barcode hasil. |
| [getReturnContent()](#getReturnContent--) | Mendapatkan atau mengatur flag untuk memperoleh konten gambar Barcode dari tanda tangan yang ditempatkan pada halaman dokumen. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Mendapatkan atau mengatur flag untuk memperoleh konten gambar Barcode dari tanda tangan yang ditempatkan pada halaman dokumen. |
| [getReturnContentType()](#getReturnContentType--) | Menentukan jenis file dari konten gambar yang dikembalikan dari tanda tangan Barcode ketika properti ReturnContent diaktifkan. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Menentukan jenis file dari konten gambar yang dikembalikan dari tanda tangan Barcode ketika properti ReturnContent diaktifkan. |
| [validate()](#validate--) | Metode internal untuk memvalidasi parameter opsi Barcode. |
| [toString()](#toString--) | Timpa konversi string. |
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


Menginisialisasi instance baru dari kelas BarcodeSignOptions dengan nilai default.

### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


Menginisialisasi instance baru dari kelas BarcodeSignOptions dengan teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | Teks Barcode |

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


Menginisialisasi instance baru dari kelas BarcodeSignOptions dengan teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | Teks Barcode |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Tipe enkode Barcode lihat [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Mendapatkan atau mengatur tipe Barcode.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Mendapatkan atau mengatur tipe Barcode.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Mendapatkan atau mengatur warna depan (Fore) dari batang Barcode. Penggunaan properti ini dapat menyebabkan masalah pada verifikasi. Gunakan dengan hati-hati.

**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Mendapatkan atau mengatur warna depan (Fore) dari batang Barcode. Penggunaan properti ini dapat menyebabkan masalah pada verifikasi. Gunakan dengan hati-hati.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Mendapatkan atau mengatur warna depan (Fore) dari batang Barcode. Penggunaan properti ini dapat menyebabkan masalah pada verifikasi. Gunakan dengan hati-hati.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Mendapatkan atau mengatur jarak antara elemen Barcode dan batas gambar hasil.

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Mendapatkan atau mengatur jarak antara elemen Barcode dan batas gambar hasil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Mendapatkan atau mengatur perataan teks dalam gambar Barcode hasil. Nilai default adalah None.

**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Mendapatkan atau mengatur perataan teks dalam gambar Barcode hasil. Nilai default adalah None.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Mendapatkan atau mengatur flag untuk memperoleh konten gambar Barcode dari tanda tangan yang ditempatkan pada halaman dokumen. Jika flag ini diatur ke true, konten gambar tanda tangan Barcode akan mempertahankan data gambar mentah dengan format yang diperlukan ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Secara default opsi ini dinonaktifkan.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Mendapatkan atau mengatur flag untuk memperoleh konten gambar Barcode dari tanda tangan yang ditempatkan pada halaman dokumen. Jika flag ini diatur ke true, konten gambar tanda tangan Barcode akan mempertahankan data gambar mentah dengan format yang diperlukan ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Secara default opsi ini dinonaktifkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Menentukan jenis file dari konten gambar yang dikembalikan dari tanda tangan Barcode ketika properti ReturnContent diaktifkan. Secara default diatur ke Null. Itu berarti mengembalikan konten gambar Barcode dalam format asli. Format gambar ini ditentukan pada BarcodeSignature.Format ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)\}) Nilai yang didukung antara lain: FileType.JPEG, FileType.PNG, FileType.BMP. Jika format yang diberikan tidak didukung, maka konten gambar Barcode dalam format .png akan dikembalikan.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Menentukan jenis file dari konten gambar yang dikembalikan dari tanda tangan Barcode ketika properti ReturnContent diaktifkan. Secara default diatur ke Null. Itu berarti mengembalikan konten gambar Barcode dalam format asli. Format gambar ini ditentukan pada BarcodeSignature.Format ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)) Nilai yang didukung antara lain: FileType.JPEG, FileType.PNG, FileType.BMP. Jika format yang diberikan tidak didukung, maka konten gambar Barcode dalam format .png akan dikembalikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


Metode internal untuk memvalidasi parameter opsi Barcode.

### toString() {#toString--}
```
public String toString()
```


Timpa konversi string.

**Returns:**
java.lang.String -
