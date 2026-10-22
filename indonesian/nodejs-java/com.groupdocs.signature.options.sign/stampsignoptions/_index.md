---
title: "StampSignOptions"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Mewakili opsi tanda tangan Stempel."
type: docs
weight: 17
url: /id/nodejs-java/com.groupdocs.signature.options.sign/stampsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class StampSignOptions extends ImageSignOptions
```

Mewakili opsi tanda tangan Stempel.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [StampSignOptions()](#StampSignOptions--) | Menginisialisasi instance baru dari kelas StampSignOptions dengan nilai default. |
| [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | Menginisialisasi instance baru dari kelas StampSignOptions dengan opsi penjajaran. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getStampType()](#getStampType--) | Mendapatkan atau mengatur jenis stempel. |
| [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | Mendapatkan atau mengatur jenis stempel. |
| [getOuterLines()](#getOuterLines--) | Daftar Garis Luar yang dirender sebagai lingkaran konsentris. |
| [getInnerLines()](#getInnerLines--) | Daftar Garis Dalam yang dirender sebagai sekumpulan persegi panjang. |
| [getBackground()](#getBackground--) | Mendapatkan atau mengatur latar belakang Stempel. |
| [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Mendapatkan atau mengatur latar belakang Stempel. |
| [getBackgroundColor()](#getBackgroundColor--) | Mendapatkan atau mengatur warna latar belakang tanda tangan. |
| [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | Mendapatkan atau mengatur warna latar belakang tanda tangan. |
| [getBackgroundBrush()](#getBackgroundBrush--) | Mendapatkan atau mengatur kuas latar belakang tanda tangan. |
| [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | Mendapatkan atau mengatur kuas latar belakang tanda tangan. |
| [getBackgroundColorCropType()](#getBackgroundColorCropType--) | Mendapatkan atau mengatur jenis pemotongan warna latar belakang tanda tangan. |
| [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | Mendapatkan atau mengatur jenis pemotongan warna latar belakang tanda tangan. |
| [getBackgroundImageCropType()](#getBackgroundImageCropType--) | Mendapatkan atau mengatur jenis pemotongan gambar latar belakang tanda tangan. |
| [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | Mendapatkan atau mengatur jenis pemotongan gambar latar belakang tanda tangan. |
| [toString()](#toString--) | Timpa konversi string |
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


Menginisialisasi instance baru dari kelas StampSignOptions dengan nilai default.

### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


Menginisialisasi instance baru dari kelas StampSignOptions dengan opsi penjajaran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kiri | int | Koordinat x dari tepi kiri atas Stempel Tanda Tangan |
| atas | int | Koordinat y dari tepi kiri atas Stempel Tanda Tangan |
| lebar | int | Lebar Stempel Tanda Tangan |
| tinggi | int | Tinggi Stempel Tanda Tangan |

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


Mendapatkan atau mengatur jenis stempel. Nilai default adalah Bulat.

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


Mendapatkan atau mengatur jenis stempel. Nilai default adalah Bulat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


Daftar Garis Luar yang dirender sebagai lingkaran konsentris.

**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


Daftar Garis Dalam yang dirender sebagai sekumpulan persegi panjang.

**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Mendapatkan atau mengatur latar belakang Stempel.

**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Mendapatkan atau mengatur latar belakang Stempel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Mendapatkan atau mengatur warna latar belakang tanda tangan.

**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


Mendapatkan atau mengatur warna latar belakang tanda tangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.awt.Color |  |

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


Mendapatkan atau mengatur kuas latar belakang tanda tangan. Nilai default adalah null.

**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


Mendapatkan atau mengatur kuas latar belakang tanda tangan. Nilai default adalah null.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


Mendapatkan atau mengatur jenis pemotongan warna latar belakang tanda tangan.

**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


Mendapatkan atau mengatur jenis pemotongan warna latar belakang tanda tangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


Mendapatkan atau mengatur jenis pemotongan gambar latar belakang tanda tangan.

**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


Mendapatkan atau mengatur jenis pemotongan gambar latar belakang tanda tangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### toString() {#toString--}
```
public String toString()
```


Timpa konversi string

**Returns:**
java.lang.String -
