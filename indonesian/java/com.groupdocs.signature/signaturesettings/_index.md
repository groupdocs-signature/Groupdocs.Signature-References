---
title: "SignatureSettings"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mendefinisikan pengaturan untuk menyesuaikan perilaku."
type: docs
weight: 11
url: /id/java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

Mendefinisikan pengaturan untuk menyesuaikan perilaku [Signature](../../com.groupdocs.signature/signature).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [SignatureSettings()](#SignatureSettings--) | Membuat instance SignatureSettings default dengan nilai default. |
|
|  | [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | Membuat instance SignatureSettings default dengan implementasi Logger. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getDefaultCulture()](#getDefaultCulture--) | Mendapatkan atau mengatur budaya default yang akan digunakan selama pemrosesan dokumen. |
|
|  | [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | Mendapatkan atau mengatur budaya default yang akan digunakan selama pemrosesan dokumen. |
|
|  | [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | Mendapatkan atau mengatur flag yang menyertakan tanda tangan yang dihapus ke dalam hasil Informasi Dokumen. |
|
|  | [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | Mendapatkan atau mengatur flag yang menyertakan tanda tangan yang dihapus ke dalam hasil Informasi Dokumen. |
|
|  | [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | Mendapatkan atau mengatur flag untuk menyimpan ulang dokumen sumber ketika metode Update tidak memiliki tanda tangan untuk diperbarui. |
|
|  | [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | Mendapatkan atau mengatur flag untuk menyimpan ulang dokumen sumber ketika metode Update tidak memiliki tanda tangan untuk diperbarui. |
|
|  | [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | Mendapatkan atau mengatur flag untuk menyimpan ulang dokumen sumber ketika metode Delete tidak memiliki tanda tangan yang terpengaruh untuk dihapus. |
|
|  | [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | Mendapatkan atau mengatur flag untuk menyimpan ulang dokumen sumber ketika metode Delete tidak memiliki tanda tangan yang terpengaruh untuk dihapus. |
|
|  | [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | Mendapatkan atau mengatur flag untuk menyertakan ke dalam Daftar Metadata tanda tangan metadata dokumen standar yang tersemat seperti Author, Owner, tanggal pembuatan dokumen, tanggal modifikasi, dll. |
|
|  | [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | Mendapatkan atau mengatur flag untuk menyertakan ke dalam Daftar Metadata tanda tangan metadata dokumen standar yang tersemat seperti Author, Owner, tanggal pembuatan dokumen, tanggal modifikasi, dll. |
|
|  | [getLogger()](#getLogger--) | Implementasi logger yang digunakan untuk pencatatan (Kesalahan, Peringatan, Jejak). |
|
|  | [getLogLevel()](#getLogLevel--) | Tingkat pencatatan untuk membatasi pesan (Semua, Jejak, Peringatan, Kesalahan). |
|
|  | [setLogLevel(int value)](#setLogLevel-int-) | Tingkat pencatatan untuk membatasi pesan (Semua, Jejak, Peringatan, Kesalahan). |
|
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


Membuat instance SignatureSettings default dengan nilai default.


### SignatureSettings(ILogger logger) {#SignatureSettings-com.groupdocs.signature.logging.ILogger-}
```
public SignatureSettings(ILogger logger)
```


Membuat instance SignatureSettings default dengan implementasi Logger.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.signature.logging/ilogger) |  |

### getDefaultCulture() {#getDefaultCulture--}
```
public static Locale getDefaultCulture()
```


Mendapatkan atau mengatur budaya default yang akan digunakan selama pemrosesan dokumen. Nilai default adalah "en-US".


**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


Mendapatkan atau mengatur budaya default yang akan digunakan selama pemrosesan dokumen. Nilai default adalah "en-US".


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


Mendapatkan atau mengatur flag yang menyertakan tanda tangan yang dihapus ke dalam hasil Informasi Dokumen.
Setiap Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) memiliki flag Deleted
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) untuk mendeteksi apakah telah dihapus.


**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


Mendapatkan atau mengatur flag yang menyertakan tanda tangan yang dihapus ke dalam hasil Informasi Dokumen.
Setiap Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) memiliki flag Deleted
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) untuk mendeteksi apakah telah dihapus.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


Mendapatkan atau mengatur flag untuk menyimpan ulang dokumen sumber ketika metode Update tidak memiliki tanda tangan untuk diperbarui.
Jika flag ini diatur ke true (secara default) dokumen akan disimpan dengan log proses riwayat yang sesuai (tanggal dan jenis operasi) bahkan jika metode Update tidak memiliki tanda tangan untuk diperbarui.
Ketika flag ini diatur ke false dokumen sumber tidak akan dimodifikasi sama sekali.


**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


Mendapatkan atau mengatur flag untuk menyimpan ulang dokumen sumber ketika metode Update tidak memiliki tanda tangan untuk diperbarui.
Jika flag ini diatur ke true (secara default) dokumen akan disimpan dengan log proses riwayat yang sesuai (tanggal dan jenis operasi) bahkan jika metode Update tidak memiliki tanda tangan untuk diperbarui.
Ketika flag ini diatur ke false dokumen sumber tidak akan dimodifikasi sama sekali.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


Mendapatkan atau mengatur flag untuk menyimpan ulang dokumen sumber ketika metode Delete tidak memiliki tanda tangan yang terpengaruh untuk dihapus.
Jika flag ini diatur ke true (secara default) dokumen akan disimpan dengan log proses riwayat yang sesuai (tanggal dan jenis operasi) bahkan jika metode Delete tidak memiliki tanda tangan untuk dihapus.
Ketika flag ini diatur ke false dokumen sumber tidak akan dimodifikasi sama sekali.


**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


Mendapatkan atau mengatur flag untuk menyimpan ulang dokumen sumber ketika metode Delete tidak memiliki tanda tangan yang terpengaruh untuk dihapus.
Jika flag ini diatur ke true (secara default) dokumen akan disimpan dengan log proses riwayat yang sesuai (tanggal dan jenis operasi) bahkan jika metode Delete tidak memiliki tanda tangan untuk dihapus.
Ketika flag ini diatur ke false dokumen sumber tidak akan dimodifikasi sama sekali.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


Mendapatkan atau mengatur flag untuk menyertakan ke dalam Daftar Metadata tanda tangan metadata dokumen standar yang tersemat seperti Author, Owner, tanggal pembuatan dokumen, tanggal modifikasi, dll.
Jika flag ini diatur ke false (secara default) GetDocumentInfo tidak akan menyertakan tanda tangan metadata ini.
Ketika flag ini diatur ke true informasi dokumen akan menyertakan tanda tangan metadata standar ini.


**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


Mendapatkan atau mengatur flag untuk menyertakan ke dalam Daftar Metadata tanda tangan metadata dokumen standar yang tersemat seperti Author, Owner, tanggal pembuatan dokumen, tanggal modifikasi, dll.
Jika flag ini diatur ke false (secara default) GetDocumentInfo tidak akan menyertakan tanda tangan metadata ini.
Ketika flag ini diatur ke true informasi dokumen akan menyertakan tanda tangan metadata standar ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Implementasi logger yang digunakan untuk pencatatan (Kesalahan, Peringatan, Jejak). [ILogger](../../com.groupdocs.signature.logging/ilogger).


**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


Tingkat pencatatan untuk membatasi pesan (Semua, Jejak, Peringatan, Kesalahan).
LogLevel
.
Secara default tipe level All diatur.


**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


Tingkat pencatatan untuk membatasi pesan (Semua, Jejak, Peringatan, Kesalahan).
LogLevel
.
Secara default tipe level All diatur.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

