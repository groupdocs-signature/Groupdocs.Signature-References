---
title: "SymmetricEncryption"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Menerapkan algoritma simetris standar untuk enkripsi data dengan satu kunci dan garam passphrase."
type: docs
weight: 11
url: /id/nodejs-java/com.groupdocs.signature.domain.extensions.encryption/symmetricencryption/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.encryption.IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
```
public final class SymmetricEncryption implements IDataEncryption
```

Mengimplementasikan algoritma simetris standar untuk enkripsi data dengan kunci tunggal dan kata sandi (garam).
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SymmetricEncryption(int algorithmType, String key, String salt)](#SymmetricEncryption-int-java.lang.String-java.lang.String-) | Membuat algoritma enkripsi simetris dengan parameter. |
| [SymmetricEncryption(int algorithmType, String key)](#SymmetricEncryption-int-java.lang.String-) | Membuat algoritma enkripsi simetris dengan passphrase default |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAlgorithmType()](#getAlgorithmType--) | Mendapatkan atau mengatur tipe algoritma simetris. |
| [setAlgorithmType(int value)](#setAlgorithmType-int-) | Mendapatkan atau mengatur tipe algoritma simetris. |
| [getKey()](#getKey--) | Mendapatkan atau mengatur kunci algoritma enkripsi. |
| [setKey(String value)](#setKey-java.lang.String-) | Mendapatkan atau mengatur kunci algoritma enkripsi. |
| [getSalt()](#getSalt--) | Mendapatkan atau mengatur passphrase algoritma enkripsi. |
| [setSalt(String value)](#setSalt-java.lang.String-) | Mendapatkan atau mengatur passphrase algoritma enkripsi. |
| [encode(String source)](#encode-java.lang.String-) | Mengenkripsi string berdasarkan tipe algoritma, kunci, dan parameter garam yang diberikan. |
| [decode(String source)](#decode-java.lang.String-) | Mendekripsi string berdasarkan tipe algoritma, kunci, dan parameter garam yang diberikan. |
### SymmetricEncryption(int algorithmType, String key, String salt) {#SymmetricEncryption-int-java.lang.String-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key, String salt)
```


Membuat algoritma enkripsi simetris dengan parameter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| algorithmType | int | Tentukan tipe algoritma simetris |
| kunci | java.lang.String | Kunci enkripsi |
| garam | java.lang.String | Passphrase untuk enkripsi |

### SymmetricEncryption(int algorithmType, String key) {#SymmetricEncryption-int-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key)
```


Membuat algoritma enkripsi simetris dengan passphrase default

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| algorithmType | int | Tentukan tipe algoritma simetris |
| kunci | java.lang.String | Kunci enkripsi |

### getAlgorithmType() {#getAlgorithmType--}
```
public final int getAlgorithmType()
```


Mendapatkan atau mengatur tipe algoritma simetris.

**Returns:**
int
### setAlgorithmType(int value) {#setAlgorithmType-int-}
```
public final void setAlgorithmType(int value)
```


Mendapatkan atau mengatur tipe algoritma simetris.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getKey() {#getKey--}
```
public final String getKey()
```


Mendapatkan atau mengatur kunci algoritma enkripsi.

**Returns:**
java.lang.String
### setKey(String value) {#setKey-java.lang.String-}
```
public final void setKey(String value)
```


Mendapatkan atau mengatur kunci algoritma enkripsi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getSalt() {#getSalt--}
```
public final String getSalt()
```


Mendapatkan atau mengatur passphrase algoritma enkripsi.

**Returns:**
java.lang.String
### setSalt(String value) {#setSalt-java.lang.String-}
```
public final void setSalt(String value)
```


Mendapatkan atau mengatur passphrase algoritma enkripsi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### encode(String source) {#encode-java.lang.String-}
```
public final String encode(String source)
```


Mengenkripsi string berdasarkan tipe algoritma, kunci, dan parameter garam yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sumber | java.lang.String | String sumber untuk dienkode. |

**Returns:**
java.lang.String - Mengembalikan string terenkripsi.
### decode(String source) {#decode-java.lang.String-}
```
public final String decode(String source)
```


Mendekripsi string berdasarkan tipe algoritma, kunci, dan parameter garam yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sumber | java.lang.String | String terenkripsi untuk didekode. |

**Returns:**
java.lang.String - Mengembalikan string terdekripsi.
