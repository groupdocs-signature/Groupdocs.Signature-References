---
title: "return_content_type özelliği"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "returncontent özelliği etkinleştirildiğinde QR‑Kod imzasının döndürülen görüntü içeriğinin dosya türü."
type: docs
url: /tr/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/
is_root: false
weight: 2050
---


## return_content_type property

`return_content` özelliği etkin olduğunda QR-Code imzasının döndürülen görüntü içeriğinin dosya türü.

Varsayılan olarak `None` olarak ayarlanır ve QR‑Kod görüntü içeriğini orijinal formatında döndürür. Görüntü formatı [`QrCodeSignature.Format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/) adresinde belirtilir. Desteklenen değerler [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), ve [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/) adresleridir. Desteklenmeyen bir format sağlanırsa, QR‑Kod görüntü içeriği PNG olarak döndürülür.

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
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
