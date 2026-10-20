---
title: "FormFieldSignature"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Berisi properti tanda tangan bidang formulir."
type: docs
weight: 13
url: /id/java/com.groupdocs.signature.domain.signatures.formfield/formfieldsignature/
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
|  | [getName()](#getName--) | Menentukan nama bidang formulir yang unik. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Menentukan nama bidang formulir yang unik. |
|
|  | [getType()](#getType--) | Menentukan tipe bidang formulir. |
|
|  | [getValue()](#getValue--) | Menentukan objek data bidang formulir. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Menentukan objek data bidang formulir. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
|
|  | [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
|
|  | [deepClone()](#deepClone--) | Gandakan instance FormField Signature. |
|
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


Menentukan tipe bidang formulir.


**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


Menentukan objek data bidang formulir.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Menentukan objek data bidang formulir.


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

