---
title: "TextSignatureImplementation"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Menentukan tipe implementasi untuk tanda tangan teks PDF."
type: docs
weight: 32
url: /id/java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class TextSignatureImplementation
```

Menentukan tipe implementasi untuk tanda tangan teks PDF.

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Native](#Native) | Tanda Tangan Teks sebagai objek teks asli pada halaman dokumen. |
|
|  | [Image](#Image) | Tanda Tangan Teks sebagai objek Gambar pada halaman dokumen. |
|
|  | [Annotation](#Annotation) | Tanda Tangan Teks sebagai objek Anotasi Teks pada halaman PDF. |
|
|  | [Sticker](#Sticker) | Tanda Tangan Teks sebagai objek Stiker pada halaman PDF. |
|
|  | [FormField](#FormField) | Tanda Tangan Teks sebagai teks dalam bidang formulir yang ditentukan. |
|
|  | [Watermark](#Watermark) | Tanda Tangan Teks sebagai watermark pada halaman dokumen. |
|
### Native {#Native}
```
public static final int Native
```


Tanda Tangan Teks sebagai objek teks asli pada halaman dokumen.


### Image {#Image}
```
public static final int Image
```


Tanda Tangan Teks sebagai objek Gambar pada halaman dokumen.


### Annotation {#Annotation}
```
public static final int Annotation
```


Tanda Tangan Teks sebagai objek Anotasi Teks pada halaman PDF.
Anotasi hanya terlihat pada versi Berlisensi.


### Sticker {#Sticker}
```
public static final int Sticker
```


Tanda Tangan Teks sebagai objek Stiker pada halaman PDF.


### FormField {#FormField}
```
public static final int FormField
```


Tanda Tangan Teks sebagai teks dalam bidang formulir yang ditentukan.
Dengan tipe implementasi ini hanya dapat menggunakan TextSignOptions.Text,
Opsi TextSignOptions.FormTextFieldType dan TextSignOptions.FormTextFieldTitle.


### Watermark {#Watermark}
```
public static final int Watermark
```


Tanda Tangan Teks sebagai watermark pada halaman dokumen.


