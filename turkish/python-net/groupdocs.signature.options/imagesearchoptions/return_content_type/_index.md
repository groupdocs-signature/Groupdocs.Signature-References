---
title: "return_content_type özelliği"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "returncontent özelliği etkinleştirildiğinde döndürülen görüntü içeriğinin dosya türü."
type: docs
url: /tr/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

`return_content` özelliği etkinleştirildiğinde döndürülen görüntü içeriğinin dosya türü.

Ayarlanmamışsa (varsayılan `None`), görüntü içeriği, [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) tarafından tanımlanan orijinal formatında döndürülür. Desteklenen değerler [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), ve [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/) şeklindedir. Desteklenmeyen bir format sağlanırsa, orijinal format döndürülür.

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
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
