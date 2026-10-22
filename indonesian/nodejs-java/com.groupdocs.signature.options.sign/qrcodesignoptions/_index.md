---
title: "QrCodeSignOptions"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Mewakili opsi tanda tangan QR-Code."
type: docs
weight: 15
url: /id/nodejs-java/com.groupdocs.signature.options.sign/qrcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class QrCodeSignOptions extends TextSignOptions
```

Mewakili opsi tanda tangan QR-Code.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [QrCodeSignOptions()](#QrCodeSignOptions--) | Menginisialisasi instance baru dari kelas QRCodeSignOptions dengan nilai default. |
| [QrCodeSignOptions(String text)](#QrCodeSignOptions-java.lang.String-) | Menginisialisasi instance baru dari kelas QRCodeSignOptions dengan teks. |
| [QrCodeSignOptions(String text, QrCodeType encodeType)](#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Menginisialisasi instance baru dari kelas BarcodeSignOptions dengan teks. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Mendapatkan atau mengatur jenis QRCode. |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Mendapatkan atau mengatur jenis QRCode. |
| [getForeColor()](#getForeColor--) | Mendapatkan atau mengatur warna depan (Fore) dari batang QR-Code. Penggunaan properti ini dapat menyebabkan masalah dengan verifikasi. |
| [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Mendapatkan atau mengatur warna depan (Fore) dari batang QR-Code. Penggunaan properti ini dapat menyebabkan masalah dengan verifikasi. |
| [setForeColor(String value)](#setForeColor-java.lang.String-) | Mendapatkan atau mengatur warna depan (Fore) dari batang QR-Code. Penggunaan properti ini dapat menyebabkan masalah dengan verifikasi. |
| [getInnerMargins()](#getInnerMargins--) | Mendapatkan atau mengatur ruang antara elemen QRCode dan batas gambar hasil. |
| [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Mendapatkan atau mengatur ruang antara elemen QRCode dan batas gambar hasil. |
| [getCodeTextAlignment()](#getCodeTextAlignment--) | Mendapatkan atau mengatur perataan teks dalam gambar QR-code hasil. |
| [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Mendapatkan atau mengatur perataan teks dalam gambar QR-code hasil. |
| [getLogoFilePath()](#getLogoFilePath--) | Mendapatkan atau mengatur nama file gambar logo QR-code. |
| [setLogoFilePath(String value)](#setLogoFilePath-java.lang.String-) | Mendapatkan atau mengatur nama file gambar logo QR-code. |
| [getLogoStream()](#getLogoStream--) | Mendapatkan atau mengatur aliran gambar logo QR-code. |
| [setLogoStream(InputStream value)](#setLogoStream-java.io.InputStream-) | Mendapatkan atau mengatur aliran gambar logo QR-code. |
| [getData()](#getData--) | Mendapatkan atau mengatur objek khusus untuk diserialisasi ke konten QR-Code. |
| [setData(Object value)](#setData-java.lang.Object-) | Mendapatkan atau mengatur objek khusus untuk diserialisasi ke konten QR-Code. |
| [getDataEncryption()](#getDataEncryption--) | Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi properti Teks atau Data Tanda Tangan QR-Code. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi properti Teks atau Data Tanda Tangan QR-Code. |
| [getReturnContent()](#getReturnContent--) | Mendapatkan atau mengatur flag untuk memperoleh konten gambar QR-Code dari tanda tangan yang ditempatkan pada halaman dokumen. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Mendapatkan atau mengatur flag untuk memperoleh konten gambar QR-Code dari tanda tangan yang ditempatkan pada halaman dokumen. |
| [getReturnContentType()](#getReturnContentType--) | Menentukan jenis file dari konten gambar yang dikembalikan dari tanda tangan QR-Code ketika properti ReturnContent diaktifkan. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Menentukan jenis file dari konten gambar yang dikembalikan dari tanda tangan QR-Code ketika properti ReturnContent diaktifkan. |
| [toString()](#toString--) | Timpa konversi string. |
| [signature()](#signature--) |  |
### QrCodeSignOptions() {#QrCodeSignOptions--}
```
public QrCodeSignOptions()
```


Menginisialisasi instance baru dari kelas QRCodeSignOptions dengan nilai default.

### QrCodeSignOptions(String text) {#QrCodeSignOptions-java.lang.String-}
```
public QrCodeSignOptions(String text)
```


Menginisialisasi instance baru dari kelas QRCodeSignOptions dengan teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | Teks tanda tangan. |

### QrCodeSignOptions(String text, QrCodeType encodeType) {#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSignOptions(String text, QrCodeType encodeType)
```


Menginisialisasi instance baru dari kelas BarcodeSignOptions dengan teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | Teks QRCode |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Tipe enkode QRCode lihat [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Mendapatkan atau mengatur jenis QRCode.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Mendapatkan atau mengatur jenis QRCode.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Mendapatkan atau mengatur warna depan (Fore) dari batang QR-Code. Penggunaan properti ini dapat menyebabkan masalah pada verifikasi. Gunakan dengan hati-hati.

**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Mendapatkan atau mengatur warna depan (Fore) dari batang QR-Code. Penggunaan properti ini dapat menyebabkan masalah pada verifikasi. Gunakan dengan hati-hati.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Mendapatkan atau mengatur warna depan (Fore) dari batang QR-Code. Penggunaan properti ini dapat menyebabkan masalah pada verifikasi. Gunakan dengan hati-hati.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Mendapatkan atau mengatur ruang antara elemen QRCode dan batas gambar hasil.

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Mendapatkan atau mengatur ruang antara elemen QRCode dan batas gambar hasil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Mendapatkan atau mengatur perataan teks dalam gambar QR-code hasil. Nilai default adalah None.

**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Mendapatkan atau mengatur perataan teks dalam gambar QR-code hasil. Nilai default adalah None.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getLogoFilePath() {#getLogoFilePath--}
```
public final String getLogoFilePath()
```


Mendapatkan atau mengatur nama file gambar logo QR-code. Properti ini hanya digunakan jika LogoStream tidak ditentukan. Penggunaan properti ini dapat menyebabkan masalah pada verifikasi. Gunakan dengan hati-hati.

**Returns:**
java.lang.String
### setLogoFilePath(String value) {#setLogoFilePath-java.lang.String-}
```
public final void setLogoFilePath(String value)
```


Mendapatkan atau mengatur nama file gambar logo QR-code. Properti ini hanya digunakan jika LogoStream tidak ditentukan. Penggunaan properti ini dapat menyebabkan masalah pada verifikasi. Gunakan dengan hati-hati.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getLogoStream() {#getLogoStream--}
```
public final InputStream getLogoStream()
```


Mendapatkan atau mengatur aliran gambar logo QR-code. Jika properti ini ditentukan, selalu digunakan menggantikan LogoGuid. Penggunaan properti ini dapat menyebabkan masalah pada verifikasi. Gunakan dengan hati-hati.

**Returns:**
java.io.InputStream
### setLogoStream(InputStream value) {#setLogoStream-java.io.InputStream-}
```
public final void setLogoStream(InputStream value)
```


Mendapatkan atau mengatur aliran gambar logo QR-code. Jika properti ini ditentukan, selalu digunakan menggantikan LogoGuid. Penggunaan properti ini dapat menyebabkan masalah pada verifikasi. Gunakan dengan hati-hati.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.io.InputStream |  |

### getData() {#getData--}
```
public final Object getData()
```


Mendapatkan atau mengatur objek khusus untuk diserialisasi ke konten QR-Code.

**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public final void setData(Object value)
```


Mendapatkan atau mengatur objek khusus untuk diserialisasi ke konten QR-Code.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi properti Teks atau Data Tanda Tangan QR-Code.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Mendapatkan atau mengatur implementasi antarmuka [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) untuk mengenkripsi dan mendekripsi properti Teks atau Data Tanda Tangan QR-Code.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Mendapatkan atau mengatur flag untuk memperoleh konten gambar QR-Code dari tanda tangan yang ditempatkan pada halaman dokumen. Jika flag ini disetel ke true, konten gambar tanda tangan QR-Code akan mempertahankan data gambar mentah dengan format yang diperlukan ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Secara default opsi ini dinonaktifkan.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Mendapatkan atau mengatur flag untuk memperoleh konten gambar QR-Code dari tanda tangan yang ditempatkan pada halaman dokumen. Jika flag ini disetel ke true, konten gambar tanda tangan QR-Code akan mempertahankan data gambar mentah dengan format yang diperlukan ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Secara default opsi ini dinonaktifkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Menentukan jenis file dari konten gambar yang dikembalikan dari tanda tangan QR-Code ketika properti ReturnContent diaktifkan. Secara default disetel ke Null. Artinya mengembalikan konten gambar QR-Code dalam format asli. Format gambar ini ditentukan pada QrCodeSignature.Format ([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature\#getFormat)/\{@link QrCodeSignature\#(FileType)\}) Nilai yang didukung antara lain: FileType.JPEG, FileType.PNG, FileType.BMP. Jika format yang diberikan tidak didukung, maka konten gambar QR-Code dalam format .png akan dikembalikan.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Menentukan jenis file dari konten gambar yang dikembalikan dari tanda tangan QR-Code ketika properti ReturnContent diaktifkan. Secara default disetel ke Null. Artinya mengembalikan konten gambar QR-Code dalam format asli. Format gambar ini ditentukan pada QrCodeSignature.Format ([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature\#getFormat)/\{@link QrCodeSignature\#(FileType)\}) Nilai yang didukung antara lain: FileType.JPEG, FileType.PNG, FileType.BMP. Jika format yang diberikan tidak didukung, maka konten gambar QR-Code dalam format .png akan dikembalikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### toString() {#toString--}
```
public String toString()
```


Timpa konversi string.

**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
