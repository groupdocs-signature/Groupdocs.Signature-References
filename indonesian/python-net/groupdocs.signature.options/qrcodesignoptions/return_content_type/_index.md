---
title: "return_content_type properti"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Jenis berkas dari konten gambar yang dikembalikan untuk tanda tangan QR‑Code ketika properti returncontent diaktifkan."
type: docs
url: /id/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/
is_root: false
weight: 2160
---


## return_content_type property

Tipe file dari konten gambar yang dikembalikan dari tanda tangan QR‑Code ketika properti `return_content` diaktifkan.

Secara default nilainya `None`, yang mengembalikan konten gambar QR‑Code dalam format aslinya seperti yang ditentukan oleh [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/).

Nilai yang didukung adalah [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), dan [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Jika format yang tidak didukung diberikan, konten akan dikembalikan dalam format PNG.

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
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
