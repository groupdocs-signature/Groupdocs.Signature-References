---
title: "GifSaveOptions"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Opsi penyimpanan format Gif untuk Dokumen Gambar."
type: docs
weight: 15
url: /id/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class GifSaveOptions extends ImageSaveOptions
```

Opsi penyimpanan format Gif untuk Dokumen Gambar.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GifSaveOptions()](#GifSaveOptions--) | Membuat GifSaveOptions dengan nilai default. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Mendapatkan atau mengatur indeks warna latar belakang GIF. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Mendapatkan atau mengatur indeks warna latar belakang GIF. |
| [getColorResolution()](#getColorResolution--) | Mendapatkan atau mengatur resolusi warna GIF. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Mendapatkan atau mengatur resolusi warna GIF. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah koreksi palet diterapkan. |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah koreksi palet diterapkan. |
| [hasTrailer()](#hasTrailer--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah GIF memiliki trailer. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah GIF memiliki trailer. |
| [getInterlaced()](#getInterlaced--) | Benar jika gambar harus diinterlaced. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Benar jika gambar harus diinterlaced. |
| [isPaletteSorted()](#isPaletteSorted--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah entri palet diurutkan. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah entri palet diurutkan. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Mendapatkan atau mengatur rasio aspek piksel GIF. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Mendapatkan atau mengatur rasio aspek piksel GIF. |
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


Membuat GifSaveOptions dengan nilai default.

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Mendapatkan atau mengatur indeks warna latar belakang GIF.

**Returns:**
byte
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Mendapatkan atau mengatur indeks warna latar belakang GIF.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Mendapatkan atau mengatur resolusi warna GIF.

--------------------

Color Resolution - Jumlah bit per warna primer yang tersedia untuk gambar asli, dikurangi 1. Nilai ini mewakili ukuran seluruh palet dari mana warna dalam grafik dipilih, bukan jumlah warna yang sebenarnya digunakan dalam grafik. Misalnya, jika nilai pada bidang ini adalah 3, maka palet gambar asli memiliki 4 bit per warna primer yang tersedia untuk membuat gambar. Nilai ini harus diatur untuk menunjukkan kekayaan palet asli, meskipun tidak setiap warna dari seluruh palet tersedia pada mesin sumber.

**Returns:**
byte
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Mendapatkan atau mengatur resolusi warna GIF.

--------------------

Color Resolution - Jumlah bit per warna primer yang tersedia untuk gambar asli, dikurangi 1. Nilai ini mewakili ukuran seluruh palet dari mana warna dalam grafik dipilih, bukan jumlah warna yang sebenarnya digunakan dalam grafik. Misalnya, jika nilai pada bidang ini adalah 3, maka palet gambar asli memiliki 4 bit per warna primer yang tersedia untuk membuat gambar. Nilai ini harus diatur untuk menunjukkan kekayaan palet asli, meskipun tidak setiap warna dari seluruh palet tersedia pada mesin sumber.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah koreksi palet diterapkan.

--------------------

Koreksi palet berarti bahwa setiap kali gambar diekspor ke GIF, warna gambar sumber akan dianalisis untuk membangun palet yang paling cocok (jika Palet gambar tidak ada atau tidak ditentukan dalam opsi). Proses analisis memerlukan waktu, namun gambar output akan memiliki palet warna yang paling cocok dan hasilnya secara visual lebih baik.

**Returns:**
boolean
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah koreksi palet diterapkan.

--------------------

Koreksi palet berarti bahwa setiap kali gambar diekspor ke GIF, warna gambar sumber akan dianalisis untuk membangun palet yang paling cocok (jika Palet gambar tidak ada atau tidak ditentukan dalam opsi). Proses analisis memerlukan waktu, namun gambar output akan memiliki palet warna yang paling cocok dan hasilnya secara visual lebih baik.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah GIF memiliki trailer.

**Returns:**
boolean
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah GIF memiliki trailer.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Benar jika gambar harus diinterlaced.

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Benar jika gambar harus diinterlaced.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah entri palet diurutkan.

**Returns:**
boolean
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah entri palet diurutkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Mendapatkan atau mengatur rasio aspek piksel GIF.

--------------------

Pixel Aspect Ratio - Faktor yang digunakan untuk menghitung perkiraan rasio aspek piksel dalam gambar asli. Jika nilai bidang ini tidak 0, perkiraan rasio aspek ini dihitung berdasarkan rumus: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Pixel Aspect Ratio didefinisikan sebagai hasil bagi lebar piksel terhadap tinggi piksel. Rentang nilai dalam bidang ini memungkinkan spesifikasi piksel terlebar 4:1 hingga piksel tertinggi 1:4 dengan kenaikan 1/64. Nilai: 0 - Tidak ada informasi rasio aspek yang diberikan. 1..255 - Nilai yang digunakan dalam perhitungan.

**Returns:**
byte
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Mendapatkan atau mengatur rasio aspek piksel GIF.

--------------------

Pixel Aspect Ratio - Faktor yang digunakan untuk menghitung perkiraan rasio aspek piksel dalam gambar asli. Jika nilai bidang ini tidak 0, perkiraan rasio aspek ini dihitung berdasarkan rumus: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Pixel Aspect Ratio didefinisikan sebagai hasil bagi lebar piksel terhadap tinggi piksel. Rentang nilai dalam bidang ini memungkinkan spesifikasi piksel terlebar 4:1 hingga piksel tertinggi 1:4 dengan kenaikan 1/64. Nilai: 0 - Tidak ada informasi rasio aspek yang diberikan. 1..255 - Nilai yang digunakan dalam perhitungan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

