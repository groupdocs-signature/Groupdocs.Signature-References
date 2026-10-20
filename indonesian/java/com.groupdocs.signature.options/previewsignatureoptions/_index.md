---
title: "PreviewSignatureOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mewakili opsi pratinjau tanda tangan."
type: docs
weight: 12
url: /id/java/com.groupdocs.signature.options/previewsignatureoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewSignatureOptions
```

Mewakili opsi pratinjau tanda tangan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)](#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-) | Menginisialisasi objek PreviewSignatureOptions. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getSignatureId()](#getSignatureId--) | Nilai unik untuk membedakan tanda tangan. |
|
|  | [setSignatureId(String value)](#setSignatureId-java.lang.String-) | Nilai unik untuk membedakan tanda tangan. |
|
|  | [getSignOptions()](#getSignOptions--) | Opsi Tanda Tangan untuk menghasilkan pratinjau. |
|
|  | [setSignOptions(SignOptions value)](#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-) | Opsi Tanda Tangan untuk menghasilkan pratinjau. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Mendapatkan atau mengatur format gambar pratinjau. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Mendapatkan atau mengatur format gambar pratinjau. |
|
### PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory) {#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-}
```
public PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)
```


Menginisialisasi objek PreviewSignatureOptions.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Opsi tanda tangan untuk menghasilkan pratinjau. |
|
|  | pageStreamFactory | [PageSignatureStreamFactory](../../com.groupdocs.signature.options/pagesignaturestreamfactory) | Antarmuka yang mendefinisikan metode untuk membuat aliran pratinjau halaman keluaran. |
|

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Nilai unik untuk membedakan tanda tangan.
Gunakan SignatureId untuk mengidentifikasi opsi pratinjau.


**Returns:**
java.lang.String
### setSignatureId(String value) {#setSignatureId-java.lang.String-}
```
public final void setSignatureId(String value)
```


Nilai unik untuk membedakan tanda tangan.
Gunakan SignatureId untuk mengidentifikasi opsi pratinjau.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getSignOptions() {#getSignOptions--}
```
public final SignOptions getSignOptions()
```


Opsi Tanda Tangan untuk menghasilkan pratinjau.


**Returns:**
[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
### setSignOptions(SignOptions value) {#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-}
```
public final void setSignOptions(SignOptions value)
```


Opsi Tanda Tangan untuk menghasilkan pratinjau.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Mendapatkan atau mengatur format gambar pratinjau.
Nilai default adalah PNG


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Mendapatkan atau mengatur format gambar pratinjau.
Nilai default adalah PNG


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

