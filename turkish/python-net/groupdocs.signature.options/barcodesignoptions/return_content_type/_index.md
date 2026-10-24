---
title: "return_content_type özelliği"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "returncontent özelliği etkin olduğunda Barcode imzasının döndürülen görüntü içeriğinin dosya türü."
type: docs
url: /tr/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/
is_root: false
weight: 2120
---


## return_content_type property

`return_content` özelliği etkin olduğunda Barcode imzasının döndürülen görüntü içeriğinin dosya türü.

Varsayılan olarak `None` olarak ayarlanmıştır, bu da Barcode görüntü içeriğinin orijinal formatında döndürüleceği anlamına gelir. Görüntü formatı [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/) tarafından belirtilir. Desteklenen değerler [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), ve [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/) dir. Desteklenmeyen bir format sağlanırsa, Barcode görüntü içeriği PNG formatında döndürülecektir.

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
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
