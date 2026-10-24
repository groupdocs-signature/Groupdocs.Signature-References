---
title: "return_content_type свойство"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Тип файла возвращаемого содержимого изображения для подписи штрих‑кода, когда включено свойство returncontent."
type: docs
url: /ru/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

Тип файла возвращаемого содержимого изображения для подписи штрихкода, когда включено свойство `return_content`.

По умолчанию это None, что возвращает изображение штрих‑кода в его исходном формате, как указано в [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/).

Поддерживаемые значения: [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), и [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Если указано значение, отличное от перечисленных, изображение будет возвращено в формате PNG.

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
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
