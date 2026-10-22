---
title: "TextSignOptions"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Mewakili opsi tanda tangan Teks."
type: docs
weight: 18
url: /id/nodejs-java/com.groupdocs.signature.options.sign/textsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class TextSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency
```

Mewakili opsi tanda tangan Teks.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextSignOptions()](#TextSignOptions--) | Menginisialisasi instance baru dari kelas SignTextOptions dengan nilai default. |
| [TextSignOptions(String text)](#TextSignOptions-java.lang.String-) | Menginisialisasi instance baru dari kelas SignTextOptions dengan teks. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [DEFAULT_TRANSPARENCY](#DEFAULT-TRANSPARENCY) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLeft()](#getLeft--) | Posisi X kiri dari Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen, atau milimeter lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) properti LocationMeasureType). |
| [setLeft(int value)](#setLeft-int-) | Posisi X kiri dari Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen, atau milimeter lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) properti LocationMeasureType). |
| [getTop()](#getTop--) | Posisi Y atas dari Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen, atau milimeter lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) properti LocationMeasureType). |
| [setTop(int value)](#setTop-int-) | Posisi Y atas dari Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen, atau milimeter lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) properti LocationMeasureType). |
| [getWidth()](#getWidth--) | Lebar Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen, atau milimeter lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) properti SizeMeasureType). |
| [setWidth(int value)](#setWidth-int-) | Lebar Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen, atau milimeter lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) properti SizeMeasureType). |
| [getHeight()](#getHeight--) | Tinggi Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen, atau milimeter lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) properti SizeMeasureType). |
| [setHeight(int value)](#setHeight-int-) | Tinggi Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen, atau milimeter lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) properti SizeMeasureType). |
| [getLocationMeasureType()](#getLocationMeasureType--) | Tipe ukuran (pixels, percents or millimeters) untuk properti Left dan Top. |
| [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | Tipe ukuran (pixels, percents or millimeters) untuk properti Left dan Top. |
| [getSizeMeasureType()](#getSizeMeasureType--) | Tipe ukuran (pixels, percents or millimeters) untuk properti Width dan Height. |
| [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | Tipe ukuran (pixels, percents or millimeters) untuk properti Width dan Height. |
| [getStretch()](#getStretch--) | Mode peregangan pada Halaman Dokumen. |
| [setStretch(int value)](#setStretch-int-) | Mode peregangan pada Halaman Dokumen. |
| [getRotationAngle()](#getRotationAngle--) | Sudut rotasi tanda tangan pada halaman dokumen (searah jarum jam). |
| [setRotationAngle(int value)](#setRotationAngle-int-) | Sudut rotasi tanda tangan pada halaman dokumen (searah jarum jam). |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Perataan horizontal tanda tangan pada halaman dokumen. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Perataan horizontal tanda tangan pada halaman dokumen. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Perataan vertikal tanda tangan pada halaman dokumen. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Perataan vertikal tanda tangan pada halaman dokumen. |
| [getMargin()](#getMargin--) | Mendapatkan atau mengatur ruang antara Sign dan tepi Dokumen. |
| [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | Mendapatkan atau mengatur ruang antara Sign dan tepi Dokumen. |
| [getMarginMeasureType()](#getMarginMeasureType--) | Mendapatkan atau mengatur jenis ukuran (piksel, persen, atau milimeter) untuk Margin. |
| [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | Mendapatkan atau mengatur jenis ukuran (piksel, persen, atau milimeter) untuk Margin. |
| [getTransparency()](#getTransparency--) | Mendapatkan atau mengatur transparansi tanda tangan (nilai dari 0,0 (opaque) hingga 1,0 (clear)). |
| [setTransparency(double value)](#setTransparency-double-) | Mendapatkan atau mengatur transparansi tanda tangan (nilai dari 0,0 (opaque) hingga 1,0 (clear)). |
| [getText()](#getText--) | Mendapatkan atau mengatur teks tanda tangan. |
| [setText(String value)](#setText-java.lang.String-) | Mendapatkan atau mengatur teks tanda tangan. |
| [getFont()](#getFont--) | Mendapatkan atau mengatur font tanda tangan. |
| [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | Mendapatkan atau mengatur font tanda tangan. |
| [getForeColor()](#getForeColor--) | Mendapatkan atau mengatur warna latar depan tanda tangan. |
| [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Mendapatkan atau mengatur warna latar depan tanda tangan. |
| [getSignatureImplementation()](#getSignatureImplementation--) | Mendapatkan atau mengatur tipe implementasi tanda tangan teks. |
| [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Mendapatkan atau mengatur tipe implementasi tanda tangan teks. |
| [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | Perataan horizontal teks di dalam tanda tangan. |
| [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | Perataan horizontal teks di dalam tanda tangan. |
| [getTextVerticalAlignment()](#getTextVerticalAlignment--) | Penjajaran vertikal teks di dalam tanda tangan. |
| [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | Penjajaran vertikal teks di dalam tanda tangan. |
| [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Mendapatkan atau mengatur judul bidang formulir teks untuk menempatkan tanda tangan teks ke dalamnya. |
| [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Mendapatkan atau mengatur judul bidang formulir teks untuk menempatkan tanda tangan teks ke dalamnya. |
| [getFormTextFieldType()](#getFormTextFieldType--) | Mendapatkan atau mengatur jenis bidang formulir untuk menempatkan tanda tangan teks ke dalamnya. |
| [setFormTextFieldType(int value)](#setFormTextFieldType-int-) | Mendapatkan atau mengatur jenis bidang formulir untuk menempatkan tanda tangan teks ke dalamnya. |
| [getShapeType()](#getShapeType--) | Mendapatkan atau mengatur jenis bentuk untuk menempatkan teks. |
| [setShapeType(int value)](#setShapeType-int-) | Mendapatkan atau mengatur jenis bentuk untuk menempatkan teks. |
| [getSignatureID()](#getSignatureID--) | Mendapatkan atau mengatur ID unik tanda tangan. |
| [setSignatureID(int value)](#setSignatureID-int-) | Mendapatkan atau mengatur ID unik tanda tangan. |
| [getBorder()](#getBorder--) | Tentukan pengaturan batas |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Tentukan pengaturan batas |
| [getBackground()](#getBackground--) | Mendapatkan atau mengatur pengaturan latar belakang tanda tangan. |
| [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Mendapatkan atau mengatur pengaturan latar belakang tanda tangan. |
| [getNative()](#getNative--) | Mendapatkan atau mengatur atribut native. |
| [setNative(boolean value)](#setNative-boolean-) | Mendapatkan atau mengatur atribut native. |
| [getShapePosition()](#getShapePosition--) | Mendefinisikan di mana bentuk harus ditampilkan dalam tata letak dokumen |
| [setShapePosition(int value)](#setShapePosition-int-) | Mendefinisikan di mana bentuk harus ditampilkan dalam tata letak dokumen |
| [validate()](#validate--) | Metode internal untuk memvalidasi parameter opsi. |
| [toString()](#toString--) | Timpa konversi string. |
### TextSignOptions() {#TextSignOptions--}
```
public TextSignOptions()
```


Menginisialisasi instance baru dari kelas SignTextOptions dengan nilai default.

### TextSignOptions(String text) {#TextSignOptions-java.lang.String-}
```
public TextSignOptions(String text)
```


Menginisialisasi instance baru dari kelas SignTextOptions dengan teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | Teks tanda tangan. |

### DEFAULT_TRANSPARENCY {#DEFAULT-TRANSPARENCY}
```
public static final double DEFAULT_TRANSPARENCY
```


### getLeft() {#getLeft--}
```
public final int getLeft()
```


Posisi X kiri dari Tanda Tangan pada Halaman Dokumen dalam nilai Pengukuran (piksel, persen, atau milimeter lihat properti [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (berfungsi jika penjajaran horizontal tidak ditentukan).

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Posisi X kiri dari Tanda Tangan pada Halaman Dokumen dalam nilai Pengukuran (piksel, persen, atau milimeter lihat properti [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (berfungsi jika penjajaran horizontal tidak ditentukan).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Posisi Y atas dari Tanda Tangan pada Halaman Dokumen dalam nilai Pengukuran (piksel, persen, atau milimeter lihat properti [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (berfungsi jika penjajaran vertikal tidak ditentukan).

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Posisi Y atas dari Tanda Tangan pada Halaman Dokumen dalam nilai Pengukuran (piksel, persen, atau milimeter lihat properti [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (berfungsi jika penjajaran vertikal tidak ditentukan).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Lebar Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen, atau milimeter lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) properti SizeMeasureType).

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Lebar Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen, atau milimeter lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) properti SizeMeasureType).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Tinggi Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen, atau milimeter lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) properti SizeMeasureType).

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Tinggi Tanda Tangan pada Halaman Dokumen dalam nilai Ukuran (piksel, persen, atau milimeter lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) properti SizeMeasureType).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


Tipe ukuran (pixels, percents or millimeters) untuk properti Left dan Top.

**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


Tipe ukuran (pixels, percents or millimeters) untuk properti Left dan Top.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


Tipe ukuran (pixels, percents or millimeters) untuk properti Width dan Height.

**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


Tipe ukuran (pixels, percents or millimeters) untuk properti Width dan Height.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


Mode peregangan pada Halaman Dokumen.

**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


Mode peregangan pada Halaman Dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Sudut rotasi tanda tangan pada halaman dokumen (searah jarum jam).

**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Sudut rotasi tanda tangan pada halaman dokumen (searah jarum jam).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Perataan horizontal tanda tangan pada halaman dokumen.

**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Perataan horizontal tanda tangan pada halaman dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Perataan vertikal tanda tangan pada halaman dokumen.

**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Perataan vertikal tanda tangan pada halaman dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


Mendapatkan atau mengatur ruang antara Sign dan tepi Dokumen. (berfungsi HANYA jika perataan horizontal atau vertikal telah ditentukan).

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


Mendapatkan atau mengatur ruang antara Sign dan tepi Dokumen. (berfungsi HANYA jika perataan horizontal atau vertikal telah ditentukan).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


Mendapatkan atau mengatur jenis ukuran (piksel, persen, atau milimeter) untuk Margin.

**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


Mendapatkan atau mengatur jenis ukuran (piksel, persen, atau milimeter) untuk Margin.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Mendapatkan atau mengatur transparansi tanda tangan (nilai dari 0,0 (opaque) hingga 1,0 (clear)). Nilai default adalah 0 (opaque).

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Mendapatkan atau mengatur transparansi tanda tangan (nilai dari 0,0 (opaque) hingga 1,0 (clear)). Nilai default adalah 0 (opaque).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### getText() {#getText--}
```
public final String getText()
```


Mendapatkan atau mengatur teks tanda tangan.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Mendapatkan atau mengatur teks tanda tangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


Mendapatkan atau mengatur font tanda tangan.

**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


Mendapatkan atau mengatur font tanda tangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Mendapatkan atau mengatur warna latar depan tanda tangan.

**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Mendapatkan atau mengatur warna latar depan tanda tangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.awt.Color |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Mendapatkan atau mengatur tipe implementasi tanda tangan teks.

**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Mendapatkan atau mengatur tipe implementasi tanda tangan teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public final int getTextHorizontalAlignment()
```


Penjajaran horizontal teks di dalam tanda tangan. Fitur ini hanya didukung untuk implementasi tanda tangan Gambar dan Anotasi (lihat properti [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation).

**Returns:**
int
### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public final void setTextHorizontalAlignment(int value)
```


Penjajaran horizontal teks di dalam tanda tangan. Fitur ini hanya didukung untuk implementasi tanda tangan Gambar dan Anotasi (lihat properti [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


Penjajaran vertikal teks di dalam tanda tangan. Fitur ini hanya didukung untuk implementasi tanda tangan Gambar (lihat properti [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation).

**Returns:**
int
### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


Penjajaran vertikal teks di dalam tanda tangan. Fitur ini hanya didukung untuk implementasi tanda tangan Gambar (lihat properti [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Mendapatkan atau mengatur judul bidang formulir teks untuk menempatkan tanda tangan teks ke dalamnya. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextToFormField.

**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Mendapatkan atau mengatur judul bidang formulir teks untuk menempatkan tanda tangan teks ke dalamnya. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextToFormField.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final int getFormTextFieldType()
```


Mendapatkan atau mengatur jenis bidang formulir untuk menempatkan tanda tangan teks ke dalamnya. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextToFormField. Nilai default adalah AllTextTypes.

**Returns:**
int
### setFormTextFieldType(int value) {#setFormTextFieldType-int-}
```
public final void setFormTextFieldType(int value)
```


Mendapatkan atau mengatur jenis bidang formulir untuk menempatkan tanda tangan teks ke dalamnya. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextToFormField. Nilai default adalah AllTextTypes.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Mendapatkan atau mengatur jenis bentuk untuk menempatkan teks. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextStamp. Nilai default adalah Rectangle.

**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public final void setShapeType(int value)
```


Mendapatkan atau mengatur jenis bentuk untuk menempatkan teks. Properti ini hanya dapat digunakan dengan SignatureImplementation = TextStamp. Nilai default adalah Rectangle.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Mendapatkan atau mengatur ID unik tanda tangan. Ini dapat digunakan dalam opsi verifikasi tanda tangan. Properti ini hanya didukung untuk dokumen Pdf.

**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Mendapatkan atau mengatur ID unik tanda tangan. Ini dapat digunakan dalam opsi verifikasi tanda tangan. Properti ini hanya didukung untuk dokumen Pdf.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Tentukan pengaturan batas

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Tentukan pengaturan batas

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Mendapatkan atau mengatur pengaturan latar belakang tanda tangan.

**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Mendapatkan atau mengatur pengaturan latar belakang tanda tangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getNative() {#getNative--}
```
public final boolean getNative()
```


Mendapatkan atau mengatur atribut native. Jika diatur, tanda tangan khusus dokumen dapat digunakan. Watermark teks native untuk dokumen WordProcessing berbeda dari yang biasa, misalnya.

**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Mendapatkan atau mengatur atribut native. Jika diatur, tanda tangan khusus dokumen dapat digunakan. Watermark teks native untuk dokumen WordProcessing berbeda dari yang biasa, misalnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


Mendefinisikan di mana bentuk harus ditampilkan dalam tata letak dokumen

**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


Mendefinisikan di mana bentuk harus ditampilkan dalam tata letak dokumen

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### validate() {#validate--}
```
public void validate()
```


Metode internal untuk memvalidasi parameter opsi.

### toString() {#toString--}
```
public String toString()
```


Timpa konversi string.

**Returns:**
java.lang.String -
