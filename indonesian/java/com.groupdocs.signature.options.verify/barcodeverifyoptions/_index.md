---
title: "BarcodeVerifyOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mewakili opsi verifikasi Barcode."
type: docs
weight: 10
url: /id/java/com.groupdocs.signature.options.verify/barcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class BarcodeVerifyOptions extends TextVerifyOptions
```

Mewakili opsi verifikasi Barcode.

<br />

*** ** * ** ***

 **Learn more**  **Learn more**

* Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](../https://docs.groupdocs.com/signature/java/verify-barcode-signatures-in-the-document)
* Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](../)

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [BarcodeVerifyOptions()](#BarcodeVerifyOptions--) | Membuat Opsi Verifikasi default untuk Tanda Tangan Barcode. |
|
|  | [BarcodeVerifyOptions(String text)](#BarcodeVerifyOptions-java.lang.String-) | Membuat Opsi Verifikasi default dengan teks verifikasi |
|
|  | [BarcodeVerifyOptions(BarcodeType encodeType)](#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Membuat Opsi Verifikasi default dengan verifikasi Tipe Barcode |
|
|  | [BarcodeVerifyOptions(String text, BarcodeType encodeType)](#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Membuat Opsi Verifikasi default dengan verifikasi Tipe Barcode dan teks |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Mendapatkan atau mengatur verifikasi Barcode Type. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Mendapatkan atau mengatur verifikasi Barcode Type. |
|
|  | [toString()](#toString--) | Menimpa konversi ke string. |
|
### BarcodeVerifyOptions() {#BarcodeVerifyOptions--}
```
public BarcodeVerifyOptions()
```


Membuat Opsi Verifikasi default untuk Tanda Tangan Barcode.


### BarcodeVerifyOptions(String text) {#BarcodeVerifyOptions-java.lang.String-}
```
public BarcodeVerifyOptions(String text)
```


Membuat Opsi Verifikasi default dengan teks verifikasi


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | teks | java.lang.String | Teks Barcode untuk diverifikasi |
|

### BarcodeVerifyOptions(BarcodeType encodeType) {#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(BarcodeType encodeType)
```


Membuat Opsi Verifikasi default dengan verifikasi Tipe Barcode


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Verifikasi Barcode Type |
|

### BarcodeVerifyOptions(String text, BarcodeType encodeType) {#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(String text, BarcodeType encodeType)
```


Membuat Opsi Verifikasi default dengan verifikasi Tipe Barcode dan teks


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | teks | java.lang.String | Teks Barcode untuk diverifikasi |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Verifikasi Barcode Type |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Mendapatkan atau mengatur verifikasi Barcode Type.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Mendapatkan atau mengatur verifikasi Barcode Type.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### toString() {#toString--}
```
public String toString()
```


Menimpa konversi ke string.


**Returns:**
java.lang.String -
