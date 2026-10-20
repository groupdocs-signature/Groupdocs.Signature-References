---
title: "WordProcessingTextSignatureImplementation"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Menentukan tipe implementasi tanda tangan teks untuk dokumen WordProcessing."
type: docs
weight: 36
url: /id/java/com.groupdocs.signature.domain.enums/wordprocessingtextsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingTextSignatureImplementation
```

Menentukan tipe implementasi tanda tangan teks untuk dokumen WordProcessing.

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [TextStamp](#TextStamp) | Tanda Tangan Teks sebagai objek Label pada halaman Words. |
|
|  | [TextAsImage](#TextAsImage) | Tanda Tangan Teks sebagai objek Gambar pada halaman Words. |
|
|  | [TextToFormField](#TextToFormField) | Tanda Tangan Teks sebagai teks dalam bidang formulir yang ditentukan. |
|
|  | [Watermark](#Watermark) | Tanda Tangan Teks sebagai watermark pada halaman Words. |
|
### TextStamp {#TextStamp}
```
public static final int TextStamp
```


Tanda Tangan Teks sebagai objek Label pada halaman Words.


### TextAsImage {#TextAsImage}
```
public static final int TextAsImage
```


Tanda Tangan Teks sebagai objek Gambar pada halaman Words.


### TextToFormField {#TextToFormField}
```
public static final int TextToFormField
```


Tanda Tangan Teks sebagai teks dalam bidang formulir yang ditentukan.
Dengan tipe implementasi ini hanya dapat menggunakan TextSignOptions.Text,
Opsi TextSignOptions.FormTextFieldTitle dan TextSignOptions.FormTextFieldType.


### Watermark {#Watermark}
```
public static final int Watermark
```


Tanda Tangan Teks sebagai watermark pada halaman Words.


