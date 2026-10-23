---
title: "properti do_palette_correction"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Bendera yang menunjukkan apakah koreksi palet diterapkan."
type: docs
url: /id/python-net/groupdocs.signature.options/gifsaveoptions/do_palette_correction/
is_root: false
weight: 2030
---


## do_palette_correction property

Bendera yang menunjukkan apakah koreksi palet diterapkan.

Palette correction berarti bahwa setiap kali sebuah gambar diekspor ke GIF, warna gambar sumber akan dianalisis untuk membangun palet yang paling cocok (jika palet gambar tidak ada atau tidak ditentukan dalam opsi). Proses analisis memerlukan waktu; namun, gambar output akan memiliki palet warna yang paling cocok dan hasilnya secara visual lebih baik.

### Definition:
```python
@property
def do_palette_correction(self):
    ...
@do_palette_correction.setter
def do_palette_correction(self, value):
    ...
```

### Lihat Juga
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
