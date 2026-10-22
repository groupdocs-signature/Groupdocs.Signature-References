---
title: "ComboboxFormFieldSignature"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Berisi properti tanda tangan bidang formulir input kotak kombo."
type: docs
weight: 11
url: /id/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

Berisi properti tanda tangan bidang formulir input kotak kombo.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | Membuat ComboboxFormFieldSignature dengan nama yang telah ditentukan. |
| [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Membuat ComboboxFormFieldSignature dengan nama yang telah ditentukan dan daftar opsi. |
| [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Membuat ComboboxFormFieldSignature dengan nama yang telah ditentukan, daftar opsi, dan nilai terpilih. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSelected()](#getSelected--) | Dapatkan atau atur nilai terpilih. |
| [setSelected(String value)](#setSelected-java.lang.String-) | Dapatkan atau atur nilai terpilih. |
| [getItems()](#getItems--) | Dapatkan atau atur daftar opsi combo-box. |
| [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Dapatkan atau atur daftar opsi combo-box. |
| [equals(Object signature)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
| [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
| [deepClone()](#deepClone--) | Menggandakan instance FormField Signature. |
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


Membuat ComboboxFormFieldSignature dengan nama yang telah ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama objek bidang formulir. |

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


Membuat ComboboxFormFieldSignature dengan nama yang telah ditentukan dan daftar opsi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama objek bidang formulir. |
| items | java.util.List<java.lang.String> | Nilai-nilai dari daftar combo-box. |

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


Membuat ComboboxFormFieldSignature dengan nama yang telah ditentukan, daftar opsi, dan nilai terpilih.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama objek bidang formulir. |
| items | java.util.List<java.lang.String> | Nilai-nilai dari daftar combo-box. |
| selected | java.lang.Object | Nilai terpilih. |

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Dapatkan atau atur nilai terpilih.

**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Dapatkan atau atur nilai terpilih.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Dapatkan atau atur daftar opsi combo-box.

**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Dapatkan atau atur daftar opsi combo-box.

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
