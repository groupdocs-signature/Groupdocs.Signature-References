---
title: "properti color_resolution"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Resolusi warna GIF."
type: docs
url: /id/python-net/groupdocs.signature.options/gifsaveoptions/color_resolution/
is_root: false
weight: 2020
---


## color_resolution property

Resolusi warna GIF.

Color Resolution - Jumlah bit per warna utama yang tersedia pada gambar asli, dikurangi 1. Nilai ini mewakili ukuran seluruh palet dari mana warna dalam grafik dipilih, bukan jumlah warna yang sebenarnya digunakan dalam grafik. Misalnya, jika nilai pada bidang ini adalah 3, maka palet gambar asli memiliki 4 bit per warna utama yang tersedia untuk membuat gambar. Nilai ini harus diatur untuk menunjukkan kekayaan palet asli, bahkan jika tidak semua warna dari seluruh palet tersedia pada mesin sumber.

### Definition:
```python
@property
def color_resolution(self):
    ...
@color_resolution.setter
def color_resolution(self, value):
    ...
```

### Lihat Juga
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
