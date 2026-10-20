---
title: "JpegSaveOptions"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Opsi penyimpanan JPEG untuk Dokumen Gambar."
type: docs
weight: 19
url: /id/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class JpegSaveOptions extends ImageSaveOptions
```

Opsi penyimpanan JPEG untuk Dokumen Gambar.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [JpegSaveOptions()](#JpegSaveOptions--) | Membuat JpegSaveOptions dengan nilai default. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getBitsPerChannel()](#getBitsPerChannel--) | Mendapatkan atau mengatur bit per kanal untuk gambar jpeg lossless. |
|
|  | [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Mendapatkan atau mengatur bit per kanal untuk gambar jpeg lossless. |
|
|  | [getColorType()](#getColorType--) | Mendapatkan atau mengatur tipe warna untuk gambar jpeg. |
|
|  | [setColorType(int value)](#setColorType-int-) | Mendapatkan atau mengatur tipe warna untuk gambar jpeg. |
|
|  | [getComment()](#getComment--) | Mendapatkan atau mengatur komentar file jpeg. |
|
|  | [setComment(String value)](#setComment-java.lang.String-) | Mendapatkan atau mengatur komentar file jpeg. |
|
|  | [getCompressionType()](#getCompressionType--) | Mendapatkan atau mengatur tipe kompresi. |
|
|  | [setCompressionType(int value)](#setCompressionType-int-) | Mendapatkan atau mengatur tipe kompresi. |
|
|  | [getQuality()](#getQuality--) | Mendapatkan atau mengatur kualitas gambar. |
|
|  | [setQuality(int value)](#setQuality-int-) | Mendapatkan atau mengatur kualitas gambar. |
|
|  | [getSampleRoundingMode()](#getSampleRoundingMode--) | Mendapatkan atau mengatur mode pembulatan sampel untuk menyesuaikan nilai 8-bit ke nilai n-bit |
JpegOptions.BitsPerChannel.
|
|  | [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Mendapatkan atau mengatur mode pembulatan sampel untuk menyesuaikan nilai 8-bit ke nilai n-bit |
JpegOptions.BitsPerChannel.
|
|  | [getFileFormat()](#getFileFormat--) | Mendapatkan atau mengatur format file dokumen yang ditandatangani. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Mendapatkan atau mengatur format file dokumen yang ditandatangani. |
|
### JpegSaveOptions() {#JpegSaveOptions--}
```
public JpegSaveOptions()
```


Membuat JpegSaveOptions dengan nilai default.


### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Mendapatkan atau mengatur bit per kanal untuk gambar jpeg lossless.
Sekarang kami mendukung dari 2 hingga 8 bit per saluran.


**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Mendapatkan atau mengatur bit per kanal untuk gambar jpeg lossless.
Sekarang kami mendukung dari 2 hingga 8 bit per saluran.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Mendapatkan atau mengatur tipe warna untuk gambar jpeg.


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Mendapatkan atau mengatur tipe warna untuk gambar jpeg.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getComment() {#getComment--}
```
public String getComment()
```


Mendapatkan atau mengatur komentar file jpeg.


**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Mendapatkan atau mengatur komentar file jpeg.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Mendapatkan atau mengatur tipe kompresi.


**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Mendapatkan atau mengatur tipe kompresi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getQuality() {#getQuality--}
```
public int getQuality()
```


Mendapatkan atau mengatur kualitas gambar.


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Mendapatkan atau mengatur kualitas gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Mendapatkan atau mengatur mode pembulatan sampel untuk menyesuaikan nilai 8-bit ke nilai n-bit
JpegOptions.BitsPerChannel.


**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Mendapatkan atau mengatur mode pembulatan sampel untuk menyesuaikan nilai 8-bit ke nilai n-bit
JpegOptions.BitsPerChannel.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Mendapatkan atau mengatur format file dokumen yang ditandatangani. Disembunyikan karena tidak digunakan untuk kelas opsi ini.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Mendapatkan atau mengatur format file dokumen yang ditandatangani. Disembunyikan karena tidak digunakan untuk kelas opsi ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

