---
title: "TextSignatureImplementation"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Menentukan tipe implementasi untuk tanda tangan teks PDF."
type: docs
weight: 32
url: /id/nodejs-java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
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
| [Native](#Native) | Text Signature sebagai objek teks asli pada halaman dokumen. |
| [Image](#Image) | Text Signature sebagai objek Gambar pada halaman dokumen. |
| [Annotation](#Annotation) | Text Signature sebagai objek Anotasi Teks pada halaman PDF. |
| [Sticker](#Sticker) | Text Signature sebagai objek Stiker pada halaman PDF. |
| [FormField](#FormField) | Text Signature sebagai teks dalam bidang formulir yang ditentukan. |
| [Watermark](#Watermark) | Text Signature sebagai watermark pada halaman dokumen. |
### Native {#Native}
```
public static final int Native
```


Text Signature sebagai objek teks asli pada halaman dokumen.

### Image {#Image}
```
public static final int Image
```


Text Signature sebagai objek Gambar pada halaman dokumen.

### Annotation {#Annotation}
```
public static final int Annotation
```


Text Signature sebagai objek Anotasi Teks pada halaman PDF. Anotasi hanya terlihat pada versi Berlisensi.

### Sticker {#Sticker}
```
public static final int Sticker
```


Text Signature sebagai objek Stiker pada halaman PDF.

### FormField {#FormField}
```
public static final int FormField
```


Text Signature sebagai teks dalam bidang formulir yang ditentukan. Dengan tipe implementasi ini hanya dapat menggunakan opsi TextSignOptions.Text, TextSignOptions.FormTextFieldType, dan TextSignOptions.FormTextFieldTitle.

### Watermark {#Watermark}
```
public static final int Watermark
```


Text Signature sebagai watermark pada halaman dokumen.

