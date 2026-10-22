---
title: "FormFieldSignature"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Berisi properti tanda tangan bidang formulir."
type: docs
weight: 13
url: /id/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/formfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class FormFieldSignature extends BaseSignature
```

Berisi properti tanda tangan bidang formulir.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getName()](#getName--) | Menentukan nama bidang formulir yang unik. |
| [setName(String value)](#setName-java.lang.String-) | Menentukan nama bidang formulir yang unik. |
| [getType()](#getType--) | Menentukan tipe bidang Form. |
| [getValue()](#getValue--) | Menentukan objek data bidang Form. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Menentukan objek data bidang Form. |
| [equals(Object signature)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
| [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
| [deepClone()](#deepClone--) | Menggandakan instance FormField Signature. |
### getName() {#getName--}
```
public final String getName()
```


Menentukan nama bidang formulir yang unik.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Menentukan nama bidang formulir yang unik.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Menentukan tipe bidang Form.

**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


Menentukan objek data bidang Form.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Menentukan objek data bidang Form.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

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
