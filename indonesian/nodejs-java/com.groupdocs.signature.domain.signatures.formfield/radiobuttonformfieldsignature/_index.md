---
title: "RadioButtonFormFieldSignature"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Berisi properti tanda tangan bidang formulir input tombol radio."
type: docs
weight: 14
url: /id/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/radiobuttonformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class RadioButtonFormFieldSignature extends FormFieldSignature
```

Berisi properti tanda tangan bidang formulir input tombol radio.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RadioButtonFormFieldSignature(String name)](#RadioButtonFormFieldSignature-java.lang.String-) | Membuat RadioButtonFieldSignature dengan nama yang telah ditentukan. |
| [RadioButtonFormFieldSignature(String name, List<String> items)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Membuat RadioButtonFieldSignature dengan nama yang telah ditentukan dan daftar item. |
| [RadioButtonFormFieldSignature(String name, List<String> items, Object selected)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Membuat RadioButtonFieldSignature dengan nama yang telah ditentukan, daftar item, dan nilai terpilih. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSelected()](#getSelected--) | Berisi nilai terpilih. |
| [setSelected(String value)](#setSelected-java.lang.String-) | Berisi nilai terpilih. |
| [getItems()](#getItems--) | Dapatkan atau atur daftar opsi tombol Radio. |
| [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Dapatkan atau atur daftar opsi tombol Radio. |
| [equals(Object signature)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
| [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
| [deepClone()](#deepClone--) | Menggandakan instance FormField Signature. |
### RadioButtonFormFieldSignature(String name) {#RadioButtonFormFieldSignature-java.lang.String-}
```
public RadioButtonFormFieldSignature(String name)
```


Membuat RadioButtonFieldSignature dengan nama yang telah ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama objek bidang formulir. |

### RadioButtonFormFieldSignature(String name, List<String> items) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public RadioButtonFormFieldSignature(String name, List<String> items)
```


Membuat RadioButtonFieldSignature dengan nama yang telah ditentukan dan daftar item.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama objek bidang formulir. |
| items | java.util.List<java.lang.String> | Nilai-nilai dari daftar radio-button. |

### RadioButtonFormFieldSignature(String name, List<String> items, Object selected) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public RadioButtonFormFieldSignature(String name, List<String> items, Object selected)
```


Membuat RadioButtonFieldSignature dengan nama yang telah ditentukan, daftar item, dan nilai terpilih.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama objek bidang formulir. |
| items | java.util.List<java.lang.String> | Nilai-nilai dari daftar radio-button. |
| selected | java.lang.Object | Nilai terpilih. |

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Berisi nilai terpilih.

**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Berisi nilai terpilih.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Dapatkan atau atur daftar opsi tombol Radio.

**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Dapatkan atau atur daftar opsi tombol Radio.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.List<java.lang.String> |  |

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
