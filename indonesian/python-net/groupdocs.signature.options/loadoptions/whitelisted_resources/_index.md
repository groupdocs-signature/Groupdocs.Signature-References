---
title: "properti whitelisted_resources"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Daftar fragmen alamat sumber daya eksternal yang dimuat bahkan ketika LoadOptions.SkipExternalResources bernilai true."
type: docs
url: /id/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/
is_root: false
weight: 2060
---


## whitelisted_resources property

Daftar fragmen alamat sumber daya eksternal yang dimuat bahkan ketika [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) bernilai true. Nilai default adalah daftar kosong.

Sebuah sumber daya dimuat ketika alamat lengkapnya mengandung salah satu fragmen. Perbandingan mengabaikan huruf besar/kecil, dan fragmen kosong diabaikan. Lebih pilih fragmen panjang seperti `\"https://cdn.example.com/images/\"`: fragmen pendek juga akan cocok dengan alamat lain yang kebetulan mengandungnya.

Mengatur properti ini ke `None` akan mengosongkan daftar. Daftar tidak berpengaruh ketika [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) bernilai false, karena pada saat itu setiap sumber daya eksternal dimuat.

### Definition:
```python
@property
def whitelisted_resources(self):
    ...
@whitelisted_resources.setter
def whitelisted_resources(self, value):
    ...
```

### Lihat Juga
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
