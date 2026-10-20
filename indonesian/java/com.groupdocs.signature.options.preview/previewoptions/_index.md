---
title: "PreviewOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mewakili opsi pratinjau dokumen."
type: docs
weight: 11
url: /id/java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Mewakili opsi pratinjau dokumen.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | Menginisialisasi objek PreviewOptions. |
|
|  | [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | Menginisialisasi objek PreviewOptions. |
|
|  | [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | Menginisialisasi objek PreviewOptions. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWidth()](#getWidth--) | Mendapatkan atau mengatur lebar gambar pratinjau. |
|
|  | [setWidth(int value)](#setWidth-int-) | Mendapatkan atau mengatur lebar gambar pratinjau. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan atau mengatur tinggi gambar pratinjau. |
|
|  | [setHeight(int value)](#setHeight-int-) | Mendapatkan atau mengatur tinggi gambar pratinjau. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Mendapatkan atau mengatur nomor halaman gambar pratinjau. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Mendapatkan atau mengatur nomor halaman gambar pratinjau. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Mendapatkan atau mengatur format gambar pratinjau. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Mendapatkan atau mengatur format gambar pratinjau. |
|
|  | [getHideSignatures()](#getHideSignatures--) | Mendapatkan atau mengatur flag untuk menyembunyikan tanda tangan dari gambar pratinjau halaman. |
|
|  | [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | Mendapatkan atau mengatur flag untuk menyembunyikan tanda tangan dari gambar pratinjau halaman. |
|
|  | [getResolution()](#getResolution--) | Mendapatkan resolusi gambar pratinjau dalam DPI (dot per inci). |
|
|  | [setResolution(int value)](#setResolution-int-) | Mengatur resolusi gambar pratinjau dalam DPI (dot per inci). |
|
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


Menginisialisasi objek PreviewOptions.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | Antarmuka yang mendefinisikan metode untuk membuat aliran pratinjau halaman keluaran. |
|
|  | pageNumbers | int[] | Nomor halaman yang diinginkan |
|

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


Menginisialisasi objek PreviewOptions.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | Antarmuka yang mendefinisikan metode untuk membuat aliran pratinjau halaman keluaran. |
|
| pageNumbers | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


Menginisialisasi objek PreviewOptions.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Jalur ke file output. |
|
|  | pageNumbers | int[] | Nomor halaman yang diinginkan |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Mendapatkan atau mengatur lebar gambar pratinjau.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Mendapatkan atau mengatur lebar gambar pratinjau.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Mendapatkan atau mengatur tinggi gambar pratinjau.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Mendapatkan atau mengatur tinggi gambar pratinjau.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Mendapatkan atau mengatur nomor halaman gambar pratinjau.


**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Mendapatkan atau mengatur nomor halaman gambar pratinjau.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Mendapatkan atau mengatur format gambar pratinjau.


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Mendapatkan atau mengatur format gambar pratinjau.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


Mendapatkan atau mengatur flag untuk menyembunyikan tanda tangan dari gambar pratinjau halaman.
Hanya tanda tangan yang ditandai sebagai IsSignature akan disembunyikan dari gambar halaman dokumen yang dihasilkan.


**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


Mendapatkan atau mengatur flag untuk menyembunyikan tanda tangan dari gambar pratinjau halaman.
Hanya tanda tangan yang ditandai sebagai IsSignature akan disembunyikan dari gambar halaman dokumen yang dihasilkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Mendapatkan resolusi gambar pratinjau dalam DPI (dot per inci).


**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Mengatur resolusi gambar pratinjau dalam DPI (dot per inci).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

