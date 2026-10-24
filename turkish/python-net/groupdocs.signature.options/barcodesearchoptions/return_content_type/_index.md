---
title: "return_content_type özelliği"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "returncontent özelliği etkin olduğunda bir Barcode imzası için döndürülen görüntü içeriğinin dosya türü."
type: docs
url: /tr/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

`return_content` özelliği etkinleştirildiğinde bir Barkod imzası için döndürülen görüntü içeriğinin dosya türü.

Varsayılan olarak None'dur, bu da barcode görüntüsünü [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/) tarafından belirtilen özgün formatta döndürür.

Desteklenen değerler [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), ve [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/) dir. Bu değerlerin dışındaki bir değer sağlanırsa, görüntü PNG formatında döndürülecektir.

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
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
