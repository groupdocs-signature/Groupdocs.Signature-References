---
title: "return_content_type properti"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Tipe file dari konten gambar QR-Code yang dikembalikan ketika properti returncontent diaktifkan."
type: docs
url: /id/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/
is_root: false
weight: 2050
---


## return_content_type property

Tipe file dari konten gambar yang dikembalikan dari tanda tangan QR-Code ketika properti `return_content` diaktifkan.

Secara default diatur ke `None`, yang mengembalikan konten gambar QR-Code dalam format aslinya. Format gambar ditentukan di [`QrCodeSignature.Format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/). Nilai yang didukung adalah [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), dan [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Jika format yang tidak didukung diberikan, konten gambar QR-Code dikembalikan sebagai PNG.

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
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
