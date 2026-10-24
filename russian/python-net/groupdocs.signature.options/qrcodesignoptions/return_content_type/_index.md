---
title: "return_content_type свойство"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Тип файла возвращаемого содержимого изображения подписи QR‑кода, когда включено свойство returncontent."
type: docs
url: /ru/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/
is_root: false
weight: 2160
---


## return_content_type property

Тип файла возвращаемого содержимого изображения подписи QR‑Code, когда включено свойство `return_content`.

По умолчанию это `None`, что возвращает содержимое изображения QR‑кода в его исходном формате, указанном в [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/).

Поддерживаемые значения: [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), и [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Если указан неподдерживаемый формат, содержимое возвращается в формате PNG.

### Definition:
```python
@property
def return_content_type(self):
    ...
@return_content_type.setter
def return_content_type(self, value):
    ...
```

### См. также
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
