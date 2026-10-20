---
title: "ImageMetadataSignature"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Berisi properti tanda tangan Metadata Gambar."
type: docs
weight: 11
url: /id/java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

Berisi properti tanda tangan Metadata Gambar.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | Membuat Tanda Tangan Metadata Gambar dengan Id dan nilai |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getId()](#getId--) | Pengidentifikasi tanda tangan Metadata Gambar. |
|
|  | [setId(int value)](#setId-int-) | Pengidentifikasi tanda tangan Metadata Gambar. |
|
|  | [getSize()](#getSize--) | Nilai hanya-baca untuk mendapatkan ukuran nilai Metadata |
|
|  | [setSize(int value)](#setSize-int-) | Nilai hanya-baca untuk mendapatkan ukuran nilai Metadata |
|
|  | [getDescription()](#getDescription--) | Nilai hanya-baca untuk mendapatkan deskripsi tanda tangan Metadata Gambar standar |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Menimpa metode Equals untuk membandingkan properti tanda tangan |
|
|  | [hashCode()](#hashCode--) | Menimpa metode GetHashCode |
|
|  | [deepClone()](#deepClone--) | Menggandakan instance Metadata Signature. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Menggandakan instance Tanda Tangan Metadata Gambar dengan nilai yang diberikan. |
|
|  | [toBoolean()](#toBoolean--) | Mengonversi ke boolean. |
|
|  | [toInteger()](#toInteger--) | Mengonversi ke integer. |
|
|  | [toLong()](#toLong--) | Mengonversi ke long. |
|
|  | [toSingle()](#toSingle--) | Mengonversi ke float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Mengonversi ke float. |
|
|  | [toDouble()](#toDouble--) | Mengonversi ke Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Mengonversi ke Double. |
|
|  | [toDecimal()](#toDecimal--) | Mengonversi ke Decimal. |
|
|  | [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | Mengonversi ke Decimal. |
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
| [setAsBool(Object value)](#setAsBool-java.lang.Object-) |  |
| [setAsByte(Object value)](#setAsByte-java.lang.Object-) |  |
| [setAsShrt(Object value)](#setAsShrt-java.lang.Object-) |  |
| [setAsWord(Object value)](#setAsWord-java.lang.Object-) |  |
| [setAsSInt(Object value)](#setAsSInt-java.lang.Object-) |  |
| [setAsUInt(Object value)](#setAsUInt-java.lang.Object-) |  |
| [setAsSLng(Object value)](#setAsSLng-java.lang.Object-) |  |
| [setAsULng(Object value)](#setAsULng-java.lang.Object-) |  |
| [setAsSngl(Object value)](#setAsSngl-java.lang.Object-) |  |
| [setAsDbls(Object value)](#setAsDbls-java.lang.Object-) |  |
| [setAsDcml(Object value)](#setAsDcml-java.lang.Object-) |  |
| [setAsDate(Object value)](#setAsDate-java.lang.Object-) |  |
| [setAsStrn(Object value)](#setAsStrn-java.lang.Object-) |  |
| [setAsObjc(Object value)](#setAsObjc-java.lang.Object-) |  |
| [setString(Object value)](#setString-java.lang.Object-) |  |
### ImageMetadataSignature(int id, Object value) {#ImageMetadataSignature-int-java.lang.Object-}
```
public ImageMetadataSignature(int id, Object value)
```


Membuat Tanda Tangan Metadata Gambar dengan Id dan nilai


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | id | int | Pengidentifikasi unik nama Tanda Tangan Metadata Gambar. Lihat referensi untuk spesifikasi tag Exif untuk nilai id yang mungkin |
|
|  | nilai | java.lang.Object | Nilai Metadata |
|

### getId() {#getId--}
```
public final int getId()
```


Pengidentifikasi tanda tangan Metadata Gambar.
Lihat kelas [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) yang berisi Tanda Tangan standar dengan nilai Id yang telah ditentukan.


**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Pengidentifikasi tanda tangan Metadata Gambar.
Lihat kelas [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) yang berisi Tanda Tangan standar dengan nilai Id yang telah ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


Nilai hanya-baca untuk mendapatkan ukuran nilai Metadata


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Nilai hanya-baca untuk mendapatkan ukuran nilai Metadata


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Nilai hanya-baca untuk mendapatkan deskripsi tanda tangan Metadata Gambar standar


**Returns:**
java.lang.String
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


Menggandakan instance Metadata Signature.


**Returns:**
java.lang.Object - Mengembalikan instance Metadata Signature yang dikloning

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Menggandakan instance Tanda Tangan Metadata Gambar dengan nilai yang diberikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.Object | Nilai untuk objek yang baru dikloning. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

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


### toLong() {#toLong--}
```
public final long toLong()
```


Mengonversi ke long.


**Returns:**
long - Mengembalikan nilai Tanda Tangan Metadata sebagai long.

<br />

*** ** * ** ***

Melemparkan pengecualian jika nilai Metadata tidak dapat dikonversi.

<br />


### toSingle() {#toSingle--}
```
public final float toSingle()
```


Mengonversi ke float.


**Returns:**
float - Mengembalikan nilai Tanda Tangan Metadata Gambar sebagai float.

<br />

*** ** * ** ***

Melemparkan pengecualian jika nilai Metadata tidak dapat dikonversi. Jika nilai asli berbasis string, informasi properti budaya default akan digunakan dari properti SignatureSettings  SignatureSettings.DefaultCulture

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
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

### toDouble() {#toDouble--}
```
public double toDouble()
```


Mengonversi ke Double.


**Returns:**
double - Mengembalikan nilai Tanda Tangan Metadata Gambar sebagai Double.

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

### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


Mengonversi ke Decimal.


**Returns:**
java.math.BigDecimal - Mengembalikan nilai Tanda Tangan Metadata Gambar sebagai Decimal.

<br />

*** ** * ** ***

Melemparkan pengecualian jika nilai Metadata tidak dapat dikonversi. Jika nilai asli berbasis string, informasi properti budaya default akan digunakan dari properti SignatureSettings  SignatureSettings.DefaultCulture

<br />


### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


Mengonversi ke Decimal.


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
java.math.BigDecimal - Mengembalikan nilai Tanda Tangan Metadata sebagai Decimal.

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

### setAsBool(Object value) {#setAsBool-java.lang.Object-}
```
public final boolean setAsBool(Object value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

**Returns:**
boolean
### setAsByte(Object value) {#setAsByte-java.lang.Object-}
```
public final boolean setAsByte(Object value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

**Returns:**
boolean
### setAsShrt(Object value) {#setAsShrt-java.lang.Object-}
```
public final boolean setAsShrt(Object value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

**Returns:**
boolean
### setAsWord(Object value) {#setAsWord-java.lang.Object-}
```
public final boolean setAsWord(Object value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

**Returns:**
boolean
### setAsSInt(Object value) {#setAsSInt-java.lang.Object-}
```
public final boolean setAsSInt(Object value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

**Returns:**
boolean
### setAsUInt(Object value) {#setAsUInt-java.lang.Object-}
```
public final boolean setAsUInt(Object value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

**Returns:**
boolean
### setAsSLng(Object value) {#setAsSLng-java.lang.Object-}
```
public final boolean setAsSLng(Object value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

**Returns:**
boolean
### setAsULng(Object value) {#setAsULng-java.lang.Object-}
```
public final boolean setAsULng(Object value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

**Returns:**
boolean
### setAsSngl(Object value) {#setAsSngl-java.lang.Object-}
```
public final boolean setAsSngl(Object value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

**Returns:**
boolean
### setAsDbls(Object value) {#setAsDbls-java.lang.Object-}
```
public final boolean setAsDbls(Object value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

**Returns:**
boolean
### setAsDcml(Object value) {#setAsDcml-java.lang.Object-}
```
public final boolean setAsDcml(Object value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

**Returns:**
boolean
### setAsDate(Object value) {#setAsDate-java.lang.Object-}
```
public final boolean setAsDate(Object value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

**Returns:**
boolean
### setAsStrn(Object value) {#setAsStrn-java.lang.Object-}
```
public final boolean setAsStrn(Object value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

**Returns:**
boolean
### setAsObjc(Object value) {#setAsObjc-java.lang.Object-}
```
public final boolean setAsObjc(Object value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

**Returns:**
boolean
### setString(Object value) {#setString-java.lang.Object-}
```
public final void setString(Object value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

