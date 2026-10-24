---
title: "return_content_type свойство"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Тип файла возвращаемого содержимого изображения подписи штрих‑кода, когда свойство returncontent включено."
type: docs
url: /ru/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/
is_root: false
weight: 2120
---


## return_content_type property

Тип файла возвращаемого содержимого изображения подписи Barcode, когда включено свойство `return_content`.

По умолчанию установлено `None`, что означает, что содержимое изображения штрих‑кода возвращается в исходном формате. Формат изображения указывается параметром [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/). Поддерживаемые значения: [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), и [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Если указан неподдерживаемый формат, содержимое изображения штрих‑кода будет возвращено в формате PNG.

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
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
