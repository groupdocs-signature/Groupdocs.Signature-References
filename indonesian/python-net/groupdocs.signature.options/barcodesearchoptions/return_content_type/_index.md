---
title: "return_content_type properti"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Tipe file dari konten gambar yang dikembalikan untuk tanda tangan Barcode ketika properti returncontent diaktifkan."
type: docs
url: /id/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

Tipe file dari konten gambar yang dikembalikan untuk tanda tangan Barcode ketika properti `return_content` diaktifkan.

Secara default nilainya None, yang mengembalikan gambar barcode dalam format aslinya seperti yang ditentukan oleh [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/).

Nilai yang didukung adalah [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), dan [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Jika nilai selain ini diberikan, gambar akan dikembalikan dalam format PNG.

### Definition:
```python
@property
def return_content_type(self):
    ...
@return_content_type.setter
def return_content_type(self, value):
    ...
```

### Lihat Juga
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
