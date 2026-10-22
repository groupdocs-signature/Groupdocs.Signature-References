---
title: "BarcodeSearchOptions"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Mewakili Opsi pencarian abstrak untuk tanda tangan Barcode."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.signature.options.search/barcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class BarcodeSearchOptions extends SearchOptions
```

Mewakili Opsi pencarian abstrak untuk tanda tangan Barcode.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BarcodeSearchOptions()](#BarcodeSearchOptions--) | Menginisialisasi instance baru dari kelas SearchBarcodeOptions dengan nilai default. |
| [BarcodeSearchOptions(BarcodeType encodeType)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Menginisialisasi instance baru dari kelas SearchBarcodeOptions dengan nilai tipe enkode. |
| [BarcodeSearchOptions(BarcodeType encodeType, String text)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-) | Menginisialisasi instance baru dari kelas SearchBarcodeOptions dengan nilai tipe enkode dan teks. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Menentukan properti Encode Type untuk mencari Barcode. |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Menentukan properti Encode Type untuk mencari Barcode. |
| [getText()](#getText--) | Menentukan teks Barcode Signature jika harus dicari dan dicocokkan. |
| [setText(String value)](#setText-java.lang.String-) | Menentukan teks Barcode Signature jika harus dicari dan dicocokkan. |
| [getMatchType()](#getMatchType--) | Mendapatkan atau mengatur pencarian Match Type teks Barcode. |
| [setMatchType(int value)](#setMatchType-int-) | Mendapatkan atau mengatur pencarian Match Type teks Barcode. |
| [getReturnContent()](#getReturnContent--) | Mendapatkan atau mengatur flag untuk mengambil konten gambar Barcode dari tanda tangan pada halaman dokumen. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Mendapatkan atau mengatur flag untuk mengambil konten gambar Barcode dari tanda tangan pada halaman dokumen. |
| [getReturnContentType()](#getReturnContentType--) | Menentukan jenis file dari konten gambar yang dikembalikan dari tanda tangan Barcode ketika properti ReturnContent diaktifkan. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Menentukan jenis file dari konten gambar yang dikembalikan dari tanda tangan Barcode ketika properti ReturnContent diaktifkan. |
### BarcodeSearchOptions() {#BarcodeSearchOptions--}
```
public BarcodeSearchOptions()
```


Menginisialisasi instance baru dari kelas SearchBarcodeOptions dengan nilai default.

### BarcodeSearchOptions(BarcodeType encodeType) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSearchOptions(BarcodeType encodeType)
```


Menginisialisasi instance baru dari kelas SearchBarcodeOptions dengan nilai tipe enkode.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Menentukan tipe enkode Barcode. |

### BarcodeSearchOptions(BarcodeType encodeType, String text) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-}
```
public BarcodeSearchOptions(BarcodeType encodeType, String text)
```


Menginisialisasi instance baru dari kelas SearchBarcodeOptions dengan nilai tipe enkode dan teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Menentukan tipe enkode Barcode. |
| teks | java.lang.String | Atur Teks dari tanda tangan Barcode. |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Menentukan properti Encode Type untuk mencari Barcode. Jika nilai ini tidak diatur, pencarian diproses untuk semua Tipe Barcode yang didukung.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Menentukan properti Encode Type untuk mencari Barcode. Jika nilai ini tidak diatur, pencarian diproses untuk semua Tipe Barcode yang didukung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Menentukan teks Barcode Signature jika harus dicari dan dicocokkan.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Menentukan teks Barcode Signature jika harus dicari dan dicocokkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Mendapatkan atau mengatur pencarian Match Type teks Barcode. Ini hanya digunakan ketika properti Text diatur.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Mendapatkan atau mengatur pencarian Match Type teks Barcode. Ini hanya digunakan ketika properti Text diatur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Mendapatkan atau mengatur flag untuk mengambil konten gambar Barcode dari tanda tangan pada halaman dokumen. Jika flag ini diset true, konten gambar tanda tangan Barcode akan mempertahankan data gambar mentah dengan format yang diperlukan ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Secara default opsi ini dinonaktifkan.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Mendapatkan atau mengatur flag untuk mengambil konten gambar Barcode dari tanda tangan pada halaman dokumen. Jika flag ini diset true, konten gambar tanda tangan Barcode akan mempertahankan data gambar mentah dengan format yang diperlukan ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Secara default opsi ini dinonaktifkan.

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


Menentukan jenis file dari konten gambar yang dikembalikan dari tanda tangan Barcode ketika properti ReturnContent diaktifkan. Secara default diatur ke Null. Itu berarti mengembalikan konten gambar Barcode dalam format asli. Format gambar ini ditentukan pada BarcodeSignature.Format ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)\}) Nilai yang didukung antara lain: FileType.JPEG, FileType.PNG, FileType.BMP. Jika format yang diberikan tidak didukung, maka konten gambar Barcode dalam format .png akan dikembalikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

