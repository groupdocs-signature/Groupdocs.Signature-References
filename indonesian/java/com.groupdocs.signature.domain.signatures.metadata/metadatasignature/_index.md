---
title: "MetadataSignature"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Berisi properti tanda tangan Metadata."
type: docs
weight: 12
url: /id/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class MetadataSignature extends BaseSignature
```

Berisi properti tanda tangan Metadata.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getName()](#getName--) | Menentukan nama metadata unik. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Menentukan nama metadata unik. |
|
|  | [getValue()](#getValue--) | Menentukan objek metadata. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Menentukan objek metadata. |
|
|  | [getType()](#getType--) | Menentukan tipe nilai metadata. |
|
|  | [setType(int value)](#setType-int-) | Menentukan tipe nilai metadata. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengkodekan dan mendekode properti Value tanda tangan. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengkodekan dan mendekode properti Value tanda tangan. |
|
|  | [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | Mendapatkan objek dari Nilai Tanda Tangan Metadata selama deserialisasi. |
|
|  | [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Mendapatkan objek dari Teks Tanda Tangan Metadata selama deserialisasi. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
|
|  | [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
|
|  | [toBoolean()](#toBoolean--) | Mengonversi ke boolean. |
|
|  | [toInteger()](#toInteger--) | Mengonversi ke integer. |
|
|  | [toDouble()](#toDouble--) | Mengonversi ke Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Mengonversi ke Double. |
|
|  | [toSingle()](#toSingle--) | Mengonversi ke float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Mengonversi ke float. |
|
|  | [toDateTime()](#toDateTime--) | Mengonversi ke DateTime. |
|
|  | [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | Mengonversi ke DateTime. |
|
|  | [toString()](#toString--) | Mengonversi ke String dengan metode override ToString() |
|
|  | [toString(String format)](#toString-java.lang.String-) | Mengonversi ke String dengan format yang ditentukan |
|
|  | [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Mengonversi ke String dengan format yang ditentukan |
|
|  | [deepClone()](#deepClone--) | Menggandakan instance Metadata Signature. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Menggandakan instance Metadata Signature dengan nilai yang diberikan. |
|
### getName() {#getName--}
```
public final String getName()
```


Menentukan nama metadata unik.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Menentukan nama metadata unik.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Menentukan objek metadata.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Menentukan objek metadata.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

### getType() {#getType--}
```
public final int getType()
```


Menentukan tipe nilai metadata.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Menentukan tipe nilai metadata.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengkodekan dan mendekode properti Value tanda tangan.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengkodekan dan mendekode properti Value tanda tangan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### <T>getData(Class<T> typeOfT) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> typeOfT)
```


Mendapatkan objek dari Nilai Tanda Tangan Metadata selama deserialisasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
T - Instance objek T


T
: Tipe objek untuk mendeserialisasi dari nilai Metadata

### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


Mendapatkan objek dari Teks Tanda Tangan Metadata selama deserialisasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Atur implementasi enkripsi data khusus. |


T
: Tipe objek untuk mendeserialisasi dari Nilai Metadata
|

**Returns:**
T -
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

### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


Mengonversi ke boolean.


**Returns:**
boolean - Mengembalikan nilai signature Metadata sebagai boolean.

<br />

*** ** * ** ***

Melemparkan pengecualian jika nilai Metadata tidak dapat dikonversi.

<br />


### toInteger() {#toInteger--}
```
public int toInteger()
```


Mengonversi ke integer.


**Returns:**
int - Mengembalikan nilai Signature Metadata sebagai integer.

<br />

*** ** * ** ***

Melemparkan pengecualian jika nilai Metadata tidak dapat dikonversi.

<br />


### toDouble() {#toDouble--}
```
public double toDouble()
```


Mengonversi ke Double.


**Returns:**
double - Mengembalikan nilai Signature Metadata sebagai Double.

<br />

*** ** * ** ***

Melemparkan pengecualian jika nilai Metadata tidak dapat dikonversi. Jika nilai asli berbasis string, informasi properti budaya default akan digunakan dari properti SignatureSettings  SignatureSettings.DefaultCulture

<br />


### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Mengonversi ke Double.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | penyedia | java.util.Locale | Penyedia format data untuk digunakan dengan operasi konversi data. |

<br />

*** ** * ** ***

Melemparkan pengecualian jika nilai Metadata tidak dapat dikonversi

<br />

|

**Returns:**
double - Mengembalikan nilai Signature Metadata sebagai Double.

### toSingle() {#toSingle--}
```
public float toSingle()
```


Mengonversi ke float.


**Returns:**
float - Mengembalikan nilai Signature Metadata sebagai float.

<br />

*** ** * ** ***

Melemparkan pengecualian jika nilai Metadata tidak dapat dikonversi. Jika nilai asli berbasis string, informasi properti budaya default akan digunakan dari properti SignatureSettings  SignatureSettings.DefaultCulture ()

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
```


Mengonversi ke float.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | penyedia | java.util.Locale | Penyedia format data untuk digunakan dengan operasi konversi data. |

<br />

*** ** * ** ***

Melemparkan pengecualian jika nilai Metadata tidak dapat dikonversi

<br />

|

**Returns:**
float - Mengembalikan nilai Signature Metadata sebagai float.

### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


Mengonversi ke DateTime.


**Returns:**
java.util.Date - Mengembalikan nilai Signature Metadata sebagai DateTime.

<br />

*** ** * ** ***

Melemparkan pengecualian jika nilai Metadata tidak dapat dikonversi. Jika nilai asli berbasis string, informasi properti budaya default akan digunakan dari properti SignatureSettings  SignatureSettings.DefaultCulture

<br />


### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


Mengonversi ke DateTime.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | penyedia | java.util.Locale | Penyedia format data untuk digunakan dengan operasi konversi data. |

<br />

*** ** * ** ***

Melemparkan pengecualian jika nilai Metadata tidak dapat dikonversi

<br />

|

**Returns:**
java.util.Date - Mengembalikan nilai Signature Metadata sebagai DateTime.

### toString() {#toString--}
```
public String toString()
```


Mengonversi ke String dengan metode override ToString()


**Returns:**
java.lang.String - Mengembalikan nilai Signature Metadata sebagai String.

<br />

*** ** * ** ***

Mengonversi properti boolean menjadi \"True\" atau \"False\". Untuk tipe data lain, penyedia format data default akan digunakan.

<br />


### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


Mengonversi ke String dengan format yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | format | java.lang.String | String format data. |

<br />

*** ** * ** ***

Mengonversi properti boolean menjadi \"True\" atau \"False\". Informasi properti budaya default akan digunakan dari properti SignatureSettings  SignatureSettings.DefaultCulture

<br />

|

**Returns:**
java.lang.String - Mengembalikan nilai Signature Metadata sebagai String.

### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


Mengonversi ke String dengan format yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | format | java.lang.String | String format data. |
|
|  | penyedia | java.util.Locale | Penyedia format data untuk digunakan dengan operasi konversi data. |

<br />

*** ** * ** ***

Mengonversi properti boolean menjadi \"True\" atau \"False\".

<br />

|

**Returns:**
java.lang.String - Mengembalikan nilai Signature Metadata sebagai String.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Menggandakan instance Metadata Signature.


**Returns:**
java.lang.Object - Mengembalikan instance Metadata Signature yang dikloning

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Menggandakan instance Metadata Signature dengan nilai yang diberikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.Object | Nilai untuk objek yang baru dikloning. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.

