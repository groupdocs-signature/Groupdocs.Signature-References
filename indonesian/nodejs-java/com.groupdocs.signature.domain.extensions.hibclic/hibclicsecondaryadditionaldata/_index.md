---
title: "HIBCLICSecondaryAdditionalData"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Kelas untuk menyimpan data sekunder dan tambahan HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code."
type: docs
weight: 13
url: /id/nodejs-java/com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICSecondaryAdditionalData implements IComplexData
```

Kelas untuk menyimpan data sekunder dan tambahan HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code).
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [HIBCLICSecondaryAdditionalData()](#HIBCLICSecondaryAdditionalData--) | Konstruktor default() |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | Mengidentifikasi format tanggal kedaluwarsa. |
| [setExpiryDateFormat(int value)](#setExpiryDateFormat-int-) | Mengidentifikasi format tanggal kedaluwarsa. |
| [getExpiryDate()](#getExpiryDate--) | Mengidentifikasi tanggal kedaluwarsa. |
| [setExpiryDate(Date value)](#setExpiryDate-java.util.Date-) | Mengidentifikasi tanggal kedaluwarsa. |
| [getLotNumber()](#getLotNumber--) | Mengidentifikasi nomor lot atau batch. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Mengidentifikasi nomor lot atau batch. |
| [getSerialNumber()](#getSerialNumber--) | Mengidentifikasi nomor seri. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Mengidentifikasi nomor seri. |
| [getDateOfManufacture()](#getDateOfManufacture--) | Mengidentifikasi tanggal pembuatan. |
| [setDateOfManufacture(Date value)](#setDateOfManufacture-java.util.Date-) | Mengidentifikasi tanggal pembuatan. |
| [getQuantity()](#getQuantity--) | Mengidentifikasi kuantitas, harus berupa nilai integer dari 0 hingga 500. |
| [setQuantity(int value)](#setQuantity-int-) | Mengidentifikasi kuantitas, harus berupa nilai integer dari 0 hingga 500. |
| [getLinkCharacter()](#getLinkCharacter--) | Mengidentifikasi karakter tautan dalam string output. |
| [setLinkCharacter(char value)](#setLinkCharacter-char-) | Mengidentifikasi karakter tautan dalam string output. |
| [deepClone()](#deepClone--) | Mendapatkan salinan objek ini. |
### HIBCLICSecondaryAdditionalData() {#HIBCLICSecondaryAdditionalData--}
```
public HIBCLICSecondaryAdditionalData()
```


Konstruktor default()

### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public final int getExpiryDateFormat()
```


Mengidentifikasi format tanggal kedaluwarsa.

**Returns:**
int
### setExpiryDateFormat(int value) {#setExpiryDateFormat-int-}
```
public final void setExpiryDateFormat(int value)
```


Mengidentifikasi format tanggal kedaluwarsa.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getExpiryDate() {#getExpiryDate--}
```
public final Date getExpiryDate()
```


Mengidentifikasi tanggal kedaluwarsa. Akan digunakan jika ExpiryDateFormat tidak diatur ke None.

**Returns:**
java.util.Date
### setExpiryDate(Date value) {#setExpiryDate-java.util.Date-}
```
public final void setExpiryDate(Date value)
```


Mengidentifikasi tanggal kedaluwarsa. Akan digunakan jika ExpiryDateFormat tidak diatur ke None.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Date |  |

### getLotNumber() {#getLotNumber--}
```
public final String getLotNumber()
```


Mengidentifikasi nomor lot atau batch. Nomor lot/batch harus berupa string alfanumerik dengan panjang hingga 18 simbol.

**Returns:**
java.lang.String
### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public final void setLotNumber(String value)
```


Mengidentifikasi nomor lot atau batch. Nomor lot/batch harus berupa string alfanumerik dengan panjang hingga 18 simbol.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Mengidentifikasi nomor seri. Nomor seri harus berupa string alfanumerik dengan panjang hingga 18 simbol.

**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Mengidentifikasi nomor seri. Nomor seri harus berupa string alfanumerik dengan panjang hingga 18 simbol.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getDateOfManufacture() {#getDateOfManufacture--}
```
public final Date getDateOfManufacture()
```


Mengidentifikasi tanggal pembuatan. Tanggal pembuatan dapat diatur ke DateTime.MinValue agar tidak menggunakan bidang ini. Nilai default: DateTime.MinValue

**Returns:**
java.util.Date
### setDateOfManufacture(Date value) {#setDateOfManufacture-java.util.Date-}
```
public final void setDateOfManufacture(Date value)
```


Mengidentifikasi tanggal pembuatan. Tanggal pembuatan dapat diatur ke DateTime.MinValue agar tidak menggunakan bidang ini. Nilai default: DateTime.MinValue

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Date |  |

### getQuantity() {#getQuantity--}
```
public final int getQuantity()
```


Mengidentifikasi kuantitas, harus berupa nilai integer dari 0 hingga 500. Kuantitas dapat diatur ke -1 agar tidak menggunakan bidang ini. Nilai default: -1

**Returns:**
int
### setQuantity(int value) {#setQuantity-int-}
```
public final void setQuantity(int value)
```


Mengidentifikasi kuantitas, harus berupa nilai integer dari 0 hingga 500. Kuantitas dapat diatur ke -1 agar tidak menggunakan bidang ini. Nilai default: -1

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getLinkCharacter() {#getLinkCharacter--}
```
public final char getLinkCharacter()
```


Mengidentifikasi karakter tautan dalam string output.

**Returns:**
char
### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public final void setLinkCharacter(char value)
```


Mengidentifikasi karakter tautan dalam string output.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | char |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Mendapatkan salinan objek ini.

**Returns:**
java.lang.Object
