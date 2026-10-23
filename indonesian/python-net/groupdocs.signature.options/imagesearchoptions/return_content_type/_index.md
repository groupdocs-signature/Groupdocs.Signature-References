---
title: "return_content_type properti"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Tipe file dari konten gambar yang dikembalikan ketika properti returncontent diaktifkan."
type: docs
url: /id/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

Tipe file dari konten gambar yang dikembalikan ketika properti `return_content` diaktifkan.

Jika tidak disetel (default `None`), konten gambar dikembalikan dalam format aslinya seperti yang didefinisikan oleh [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/). Nilai yang didukung adalah [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), dan [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Jika format yang tidak didukung diberikan, format asli akan dikembalikan.

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
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
