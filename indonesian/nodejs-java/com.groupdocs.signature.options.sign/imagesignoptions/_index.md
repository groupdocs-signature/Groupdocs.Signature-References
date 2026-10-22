---
title: "ImageSignOptions"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Mewakili opsi tanda tangan Gambar."
type: docs
weight: 13
url: /id/nodejs-java/com.groupdocs.signature.options.sign/imagesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency), com.aspose.ms.System.IDisposable
```
public class ImageSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency, System.IDisposable
```

Mewakili opsi tanda tangan Gambar.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ImageSignOptions()](#ImageSignOptions--) | Menginisialisasi instance baru dari kelas ImageSignOptions dengan nilai default. |
| [ImageSignOptions(String imageFilePath)](#ImageSignOptions-java.lang.String-) | Menginisialisasi instance baru dari kelas ImageSignOptions dengan file gambar. |
| [ImageSignOptions(InputStream imageStream)](#ImageSignOptions-java.io.InputStream-) | Menginisialisasi instance baru dari kelas ImageSignOptions dengan aliran gambar. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getImageFilePath()](#getImageFilePath--) | Mendapatkan atau mengatur jalur file gambar tanda tangan. |
| [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Mendapatkan atau mengatur jalur file gambar tanda tangan. |
| [getImageStream()](#getImageStream--) | Mendapatkan atau mengatur aliran gambar tanda tangan. |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Mendapatkan atau mengatur aliran gambar tanda tangan. |
| [getLeft()](#getLeft--) | Posisi X kiri dari Signature pada Halaman Dokumen dalam nilai Measure (pixels, percents or millimeters lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [setLeft(int value)](#setLeft-int-) | Posisi X kiri dari Signature pada Halaman Dokumen dalam nilai Measure (pixels, percents or millimeters lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [getTop()](#getTop--) | Posisi Y atas dari Signature pada Halaman Dokumen dalam nilai Measure (pixels, percents or millimeters lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [setTop(int value)](#setTop-int-) | Posisi Y atas dari Signature pada Halaman Dokumen dalam nilai Measure (pixels, percents or millimeters lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [getWidth()](#getWidth--) | Lebar Signature pada Halaman Dokumen dalam nilai Measure (pixels, percents or millimeters [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [setWidth(int value)](#setWidth-int-) | Lebar Signature pada Halaman Dokumen dalam nilai Measure (pixels, percents or millimeters [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [getHeight()](#getHeight--) | Tinggi Signature pada Halaman Dokumen dalam nilai Measure (pixels, percents or millimeters lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [setHeight(int value)](#setHeight-int-) | Tinggi Signature pada Halaman Dokumen dalam nilai Measure (pixels, percents or millimeters lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
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
| [getShapePosition()](#getShapePosition--) | Mendefinisikan di mana bentuk harus ditampilkan dalam tata letak dokumen |
| [setShapePosition(int value)](#setShapePosition-int-) | Mendefinisikan di mana bentuk harus ditampilkan dalam tata letak dokumen |
| [getRectangle()](#getRectangle--) | Persegi panjang area untuk menempatkan gambar pada dokumen. |
| [getBorder()](#getBorder--) | Tentukan pengaturan batas |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Tentukan pengaturan batas |
| [toString()](#toString--) | Timpa konversi string. |
| [fromBase64(String base64Content)](#fromBase64-java.lang.String-) | Membuat instance baru dari kelas **ImageSignOptions** dengan Gambar yang telah ditentukan dari Base64. |
| [dispose()](#dispose--) | Membersihkan sumber daya internal |
### ImageSignOptions() {#ImageSignOptions--}
```
public ImageSignOptions()
```


Menginisialisasi instance baru dari kelas ImageSignOptions dengan nilai default.

### ImageSignOptions(String imageFilePath) {#ImageSignOptions-java.lang.String-}
```
public ImageSignOptions(String imageFilePath)
```


Menginisialisasi instance baru dari kelas ImageSignOptions dengan file gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageFilePath | java.lang.String | Jalur file gambar |

### ImageSignOptions(InputStream imageStream) {#ImageSignOptions-java.io.InputStream-}
```
public ImageSignOptions(InputStream imageStream)
```


Menginisialisasi instance baru dari kelas ImageSignOptions dengan aliran gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageStream | java.io.InputStream | Aliran gambar |

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Mendapatkan atau mengatur jalur file gambar tanda tangan. Properti ini hanya digunakan jika ImageStream tidak ditentukan.

**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Mendapatkan atau mengatur jalur file gambar tanda tangan. Properti ini hanya digunakan jika ImageStream tidak ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Mendapatkan atau mengatur aliran gambar tanda tangan. Jika properti ini ditentukan, selalu digunakan menggantikan ImageGuid.

**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Mendapatkan atau mengatur aliran gambar tanda tangan. Jika properti ini ditentukan, selalu digunakan menggantikan ImageGuid.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.io.InputStream |  |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Posisi X kiri dari Signature pada Halaman Dokumen dalam nilai Measure (piksel, persen, atau milimeter lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (berfungsi jika perataan horizontal tidak ditentukan).

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Posisi X kiri dari Signature pada Halaman Dokumen dalam nilai Measure (piksel, persen, atau milimeter lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (berfungsi jika perataan horizontal tidak ditentukan).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Posisi Y atas dari Signature pada Halaman Dokumen dalam nilai Measure (piksel, persen, atau milimeter lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (berfungsi jika perataan vertikal tidak ditentukan).

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Posisi Y atas dari Signature pada Halaman Dokumen dalam nilai Measure (piksel, persen, atau milimeter lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (berfungsi jika perataan vertikal tidak ditentukan).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Lebar Signature pada Halaman Dokumen dalam nilai Measure (pixels, percents or millimeters [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Lebar Signature pada Halaman Dokumen dalam nilai Measure (pixels, percents or millimeters [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Tinggi Signature pada Halaman Dokumen dalam nilai Measure (pixels, percents or millimeters lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Tinggi Signature pada Halaman Dokumen dalam nilai Measure (pixels, percents or millimeters lihat [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

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

### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


Persegi panjang area untuk menempatkan gambar pada dokumen.

**Returns:**
java.awt.Rectangle
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

### toString() {#toString--}
```
public String toString()
```


Timpa konversi string.

**Returns:**
java.lang.String -
### fromBase64(String base64Content) {#fromBase64-java.lang.String-}
```
public static ImageSignOptions fromBase64(String base64Content)
```


Membuat instance baru dari kelas **ImageSignOptions** dengan Gambar yang telah ditentukan dari Base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| base64Content | java.lang.String | Konten gambar dalam format string Base64 |

**Returns:**
[ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions) - 
### dispose() {#dispose--}
```
public final void dispose()
```


Membersihkan sumber daya internal

