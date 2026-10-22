---
title: "DigitalFormFieldSignature"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Berisi properti bidang formulir input tanda tangan digital untuk Dokumen Pdf."
type: docs
weight: 12
url: /id/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/digitalformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class DigitalFormFieldSignature extends FormFieldSignature
```

Berisi properti bidang formulir input tanda tangan digital untuk Dokumen Pdf.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DigitalFormFieldSignature(String name)](#DigitalFormFieldSignature-java.lang.String-) | Membuat PdfDigitalFormFieldSignature dengan nama yang telah ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSigned()](#getSigned--) | Properti read-only yang menunjukkan apakah Form-field Signature telah ditandatangani dengan sertifikat digital. |
| [equals(Object signature)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
| [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
| [deepClone()](#deepClone--) | Menggandakan instance FormField Signature. |
### DigitalFormFieldSignature(String name) {#DigitalFormFieldSignature-java.lang.String-}
```
public DigitalFormFieldSignature(String name)
```


Membuat PdfDigitalFormFieldSignature dengan nama yang telah ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama objek bidang formulir. |

### getSigned() {#getSigned--}
```
public final boolean getSigned()
```


Properti read-only yang menunjukkan apakah Form-field Signature telah ditandatangani dengan sertifikat digital.

**Returns:**
boolean
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Menimpa metode Equals untuk membandingkan properti tanda tangan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tanda tangan | java.lang.Object | Objek tanda tangan untuk dibandingkan. |

**Returns:**
boolean - Mengembalikan true jika objek tanda tangan yang diberikan memiliki tipe yang sama dan semua propertinya sama dengan properti instance ini.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Menimpa metode GetHashCode

**Returns:**
int - Kode hash tanda tangan
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Menggandakan instance FormField Signature.

**Returns:**
java.lang.Object - Mengembalikan instance FormField Signature yang dikloning.
