---
title: "TextFormFieldSignature"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Berisi properti tanda tangan bidang formulir input teks untuk Dokumen Pdf"
type: docs
weight: 15
url: /id/java/com.groupdocs.signature.domain.signatures.formfield/textformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class TextFormFieldSignature extends FormFieldSignature
```

Berisi properti tanda tangan bidang formulir input teks untuk Dokumen Pdf

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [TextFormFieldSignature(String name)](#TextFormFieldSignature-java.lang.String-) | Membuat PdfTextFormFieldSignature dengan nama yang telah ditentukan. |
|
|  | [TextFormFieldSignature(String name, String text)](#TextFormFieldSignature-java.lang.String-java.lang.String-) | Membuat PdfTextFormFieldSignature dengan nama yang telah ditentukan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getText()](#getText--) | Mendapatkan atau mengatur teks input bidang formulir. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Mendapatkan atau mengatur teks input bidang formulir. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
|
|  | [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
|
|  | [deepClone()](#deepClone--) | Gandakan instance FormField Signature. |
|
### TextFormFieldSignature(String name) {#TextFormFieldSignature-java.lang.String-}
```
public TextFormFieldSignature(String name)
```


Membuat PdfTextFormFieldSignature dengan nama yang telah ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama objek bidang formulir. |
|

### TextFormFieldSignature(String name, String text) {#TextFormFieldSignature-java.lang.String-java.lang.String-}
```
public TextFormFieldSignature(String name, String text)
```


Membuat PdfTextFormFieldSignature dengan nama yang telah ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama objek bidang formulir. |
|
|  | teks | java.lang.String | Teks objek bidang formulir. |
|

### getText() {#getText--}
```
public final String getText()
```


Mendapatkan atau mengatur teks input bidang formulir.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Mendapatkan atau mengatur teks input bidang formulir.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Menimpa metode Equals untuk membandingkan properti tanda tangan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | signature | java.lang.Object | Objek Signature untuk dibandingkan. |
|

**Returns:**
boolean - Mengembalikan true jika objek signature yang diberikan memiliki tipe yang sama dan semua propertinya sama dengan properti instance ini.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Menimpa metode GetHashCode


**Returns:**
int - Kode hash Signature

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Gandakan instance FormField Signature.


**Returns:**
java.lang.Object - Mengembalikan instance FormField Signature yang digandakan.

