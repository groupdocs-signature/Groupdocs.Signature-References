---
title: "properti pixel_aspect_ratio"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Rasio aspek piksel GIF."
type: docs
url: /id/python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio/
is_root: false
weight: 2070
---


## pixel_aspect_ratio property

Rasio aspek piksel GIF.

Pixel Aspect Ratio – faktor yang digunakan untuk menghitung perkiraan rasio aspek piksel dalam gambar asli. Jika nilai bidang tidak 0, perkiraan rasio aspek ini dihitung berdasarkan rumus:

Aspect Ratio = (Pixel Aspect Ratio + 15) / 64

Pixel Aspect Ratio didefinisikan sebagai hasil bagi lebar piksel terhadap tinggi piksel. Rentang nilai dalam bidang ini memungkinkan spesifikasi piksel terlebar 4:1 hingga piksel tertinggi 1:4 dengan kenaikan 1/64.

Nilai:
- 0 – No aspect ratio information is given.
- 1..255 – Value used in the computation.

### Definition:
```python
@property
def pixel_aspect_ratio(self):
    ...
@pixel_aspect_ratio.setter
def pixel_aspect_ratio(self, value):
    ...
```

### Lihat Juga
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
