---
title: "return_content_type özelliği"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "returncontent özelliği etkin olduğunda QR‑Code imzasının döndürülen görüntü içeriğinin dosya türü."
type: docs
url: /tr/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/
is_root: false
weight: 2160
---


## return_content_type property

`return_content` özelliği etkin olduğunda QR‑Code imzasının döndürülen görüntü içeriğinin dosya türü.

Varsayılan olarak `None` değerindedir ve bu, [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/) tarafından belirtilen orijinal formatta QR‑Code görüntü içeriğini döndürür.

Desteklenen değerler [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), ve [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/) şeklindedir. Desteklenmeyen bir format sağlanırsa, içerik PNG formatında döndürülür.

### Definition:
```python
@property
def return_content_type(self):
    ...
@return_content_type.setter
def return_content_type(self, value):
    ...
```

### Ayrıca Bakınız
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
