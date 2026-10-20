---
title: "SwissQR"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode SwissQR."
type: docs
weight: 11
url: /id/java/com.groupdocs.signature.domain.extensions.swissqr/swissqr/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class SwissQR implements IComplexData
```

Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode SwissQR.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [SwissQR()](#SwissQR--) | Membuat instance SwissQR. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getAmount()](#getAmount--) | Mendapatkan atau mengatur jumlah pembayaran. |
|
|  | [setAmount(double value)](#setAmount-double-) | Mendapatkan atau mengatur jumlah pembayaran. |
|
|  | [getCurrency()](#getCurrency--) | Mendapatkan atau mengatur mata uang pembayaran. |
|
|  | [setCurrency(String value)](#setCurrency-java.lang.String-) | Mendapatkan atau mengatur mata uang pembayaran. |
|
|  | [getAccount()](#getAccount--) | Mendapatkan atau mengatur nomor rekening kreditur. |
|
|  | [setAccount(String value)](#setAccount-java.lang.String-) | Mendapatkan atau mengatur nomor rekening kreditur. |
|
|  | [getCreditor()](#getCreditor--) | Mendapatkan atau mengatur alamat kreditur. |
|
|  | [setCreditor(SwissAddress value)](#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Mendapatkan atau mengatur alamat kreditur. |
|
|  | [getReference()](#getReference--) | Mendapatkan atau mengatur referensi pembayaran kreditur. |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | Mendapatkan atau mengatur referensi pembayaran kreditur. |
|
|  | [getDebtor()](#getDebtor--) | Mendapatkan atau mengatur alamat debitur. |
|
|  | [setDebtor(SwissAddress value)](#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Mendapatkan atau mengatur alamat debitur. |
|
|  | [getUnstructuredMessage()](#getUnstructuredMessage--) | Mendapatkan atau mengatur pesan tidak terstruktur tambahan. |
|
|  | [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Mendapatkan atau mengatur pesan tidak terstruktur tambahan. |
|
|  | [getBillInformation()](#getBillInformation--) | Mendapatkan atau mengatur informasi tagihan terstruktur tambahan. |
|
|  | [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Mendapatkan atau mengatur informasi tagihan terstruktur tambahan. |
|
### SwissQR() {#SwissQR--}
```
public SwissQR()
```


Membuat instance SwissQR.


### getAmount() {#getAmount--}
```
public final double getAmount()
```


Mendapatkan atau mengatur jumlah pembayaran.
Nilai yang valid berada di antara 0.01 dan 999,999,999.99.
Nilai: Jumlah pembayaran.


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Mendapatkan atau mengatur jumlah pembayaran.
Nilai yang valid berada di antara 0.01 dan 999,999,999.99.
Nilai: Jumlah pembayaran.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### getCurrency() {#getCurrency--}
```
public final String getCurrency()
```


Mendapatkan atau mengatur mata uang pembayaran.
Nilai yang valid adalah "CHF" dan "EUR".
Nilai: Mata uang pembayaran.


**Returns:**
java.lang.String
### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public final void setCurrency(String value)
```


Mendapatkan atau mengatur mata uang pembayaran.
Nilai yang valid adalah "CHF" dan "EUR".
Nilai: Mata uang pembayaran.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getAccount() {#getAccount--}
```
public final String getAccount()
```


Mendapatkan atau mengatur nomor rekening kreditur.
Nomor rekening harus berupa IBAN yang valid dari bank di Swiss atau Liechtenstein.
Spasi diizinkan dalam nomor rekening.
Nilai: Nomor rekening kreditur.


**Returns:**
java.lang.String
### setAccount(String value) {#setAccount-java.lang.String-}
```
public final void setAccount(String value)
```


Mendapatkan atau mengatur nomor rekening kreditur.
Nomor rekening harus berupa IBAN yang valid dari bank di Swiss atau Liechtenstein.
Spasi diizinkan dalam nomor rekening.
Nilai: Nomor rekening kreditur.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getCreditor() {#getCreditor--}
```
public final SwissAddress getCreditor()
```


Mendapatkan atau mengatur alamat kreditur.
Nilai: Alamat kreditur.


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setCreditor(SwissAddress value) {#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setCreditor(SwissAddress value)
```


Mendapatkan atau mengatur alamat kreditur.
Nilai: Alamat kreditur.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Mendapatkan atau mengatur referensi pembayaran kreditur.
Referensi wajib untuk IBAN SwissQR, yaitu IBAN dalam rentang CHxx30000xxxxxx
hingga CHxx31999xxxxx.
Jika ditentukan, referensi harus berupa referensi SwissQR yang valid (sesuai
dengan format referensi ISR) atau referensi kreditur yang valid menurut ISO 11649 ("RFxxxx").
Keduanya dapat berisi spasi untuk pemformatan.
Nilai: Referensi pembayaran kreditur.


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Mendapatkan atau mengatur referensi pembayaran kreditur.
Referensi wajib untuk IBAN SwissQR, yaitu IBAN dalam rentang CHxx30000xxxxxx
hingga CHxx31999xxxxx.
Jika ditentukan, referensi harus berupa referensi SwissQR yang valid (sesuai
dengan format referensi ISR) atau referensi kreditur yang valid menurut ISO 11649 ("RFxxxx").
Keduanya dapat berisi spasi untuk pemformatan.
Nilai: Referensi pembayaran kreditur.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getDebtor() {#getDebtor--}
```
public final SwissAddress getDebtor()
```


Mendapatkan atau mengatur alamat debitur.
Debitur bersifat opsional. Jika diabaikan, baik mengatur bidang ini menjadi null atau
mengatur alamat dengan semua nilai null atau kosong juga diperbolehkan.
Nilai: Alamat debitur.


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setDebtor(SwissAddress value) {#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setDebtor(SwissAddress value)
```


Mendapatkan atau mengatur alamat debitur.
Debitur bersifat opsional. Jika diabaikan, baik mengatur bidang ini menjadi null atau
mengatur alamat dengan semua nilai null atau kosong juga diperbolehkan.
Nilai: Alamat debitur.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public final String getUnstructuredMessage()
```


Mendapatkan atau mengatur pesan tidak terstruktur tambahan.
Nilai: Pesan tidak terstruktur.


**Returns:**
java.lang.String
### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public final void setUnstructuredMessage(String value)
```


Mendapatkan atau mengatur pesan tidak terstruktur tambahan.
Nilai: Pesan tidak terstruktur.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getBillInformation() {#getBillInformation--}
```
public final String getBillInformation()
```


Mendapatkan atau mengatur informasi tagihan terstruktur tambahan.
Nilai: Informasi tagihan terstruktur.


**Returns:**
java.lang.String
### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public final void setBillInformation(String value)
```


Mendapatkan atau mengatur informasi tagihan terstruktur tambahan.
Nilai: Informasi tagihan terstruktur.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

