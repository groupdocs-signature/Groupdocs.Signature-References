---
title: "TextSignature"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Berisi properti Text signature."
type: docs
weight: 18
url: /id/nodejs-java/com.groupdocs.signature.domain.signatures/textsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class TextSignature extends BaseSignature
```

Berisi properti Text signature.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextSignature(String signatureId)](#TextSignature-java.lang.String-) | Inisialisasi objek TextSignature dengan pengidentifikasi tanda tangan yang diperoleh setelah proses pencarian. |
| [TextSignature()](#TextSignature--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getText()](#getText--) | Menentukan teks dalam tanda tangan. |
| [setText(String value)](#setText-java.lang.String-) | Menentukan teks dalam tanda tangan. |
| [getSignatureImplementation()](#getSignatureImplementation--) | Menentukan implementasi tanda tangan teks. |
| [getNative()](#getNative--) | Menentukan atribut native. |
| [setNative(boolean value)](#setNative-boolean-) | Menentukan atribut native. |
| [equals(Object signature)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
| [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
| [deepClone()](#deepClone--) | Kloning instance Text Signature. |
### TextSignature(String signatureId) {#TextSignature-java.lang.String-}
```
public TextSignature(String signatureId)
```


Inisialisasi objek TextSignature dengan pengidentifikasi tanda tangan yang diperoleh setelah proses pencarian. Pengidentifikasi unik ini digunakan untuk menemukan properti tambahan untuk tanda tangan ini dari lapisan informasi tanda tangan dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signatureId | java.lang.String | Pengidentifikasi tanda tangan unik yang diperoleh melalui metode tanda tangan atau pencarian. |

### TextSignature() {#TextSignature--}
```
public TextSignature()
```


### getText() {#getText--}
```
public final String getText()
```


Menentukan teks dalam tanda tangan.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Menentukan teks dalam tanda tangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Menentukan implementasi tanda tangan teks.

**Returns:**
int
### getNative() {#getNative--}
```
public final boolean getNative()
```


Menentukan atribut native. Nilainya true jika tanda tangan bersifat khusus dokumen.

**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Menentukan atribut native. Nilainya true jika tanda tangan bersifat khusus dokumen.

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


Kloning instance Text Signature.

**Returns:**
java.lang.Object - Mengembalikan instance Text Signature yang dikloning.
