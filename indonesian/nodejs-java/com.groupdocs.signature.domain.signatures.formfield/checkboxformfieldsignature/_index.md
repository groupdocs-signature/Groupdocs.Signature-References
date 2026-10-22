---
title: "CheckboxFormFieldSignature"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Berisi properti tanda tangan bidang formulir input kotak centang."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/checkboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class CheckboxFormFieldSignature extends FormFieldSignature
```

Berisi properti tanda tangan bidang formulir input kotak centang.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CheckboxFormFieldSignature(String name)](#CheckboxFormFieldSignature-java.lang.String-) | Membuat PdfCheckboxFormFieldSignature dengan nama yang telah ditentukan. |
| [CheckboxFormFieldSignature(String name, boolean isChecked)](#CheckboxFormFieldSignature-java.lang.String-boolean-) | Membuat PdfCheckboxFormFieldSignature dengan nama dan nilai yang telah ditentukan |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getChecked()](#getChecked--) | Mendapatkan atau mengatur nilai tercentang dari input kotak centang bidang formulir. |
| [setChecked(boolean value)](#setChecked-boolean-) | Mendapatkan atau mengatur nilai tercentang dari input kotak centang bidang formulir. |
| [equals(Object signature)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
| [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
| [deepClone()](#deepClone--) | Menggandakan instance FormField Signature. |
### CheckboxFormFieldSignature(String name) {#CheckboxFormFieldSignature-java.lang.String-}
```
public CheckboxFormFieldSignature(String name)
```


Membuat PdfCheckboxFormFieldSignature dengan nama yang telah ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama objek bidang formulir. |

### CheckboxFormFieldSignature(String name, boolean isChecked) {#CheckboxFormFieldSignature-java.lang.String-boolean-}
```
public CheckboxFormFieldSignature(String name, boolean isChecked)
```


Membuat PdfCheckboxFormFieldSignature dengan nama dan nilai yang telah ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama objek bidang formulir. |
| isChecked | boolean | Nilai jika kotak centang tercentang |

### getChecked() {#getChecked--}
```
public final boolean getChecked()
```


Mendapatkan atau mengatur nilai tercentang dari input kotak centang bidang formulir.

**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public final void setChecked(boolean value)
```


Mendapatkan atau mengatur nilai tercentang dari input kotak centang bidang formulir.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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
