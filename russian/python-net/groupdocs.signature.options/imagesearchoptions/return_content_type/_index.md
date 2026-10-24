---
title: "return_content_type свойство"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Тип файла возвращаемого содержимого изображения, когда свойство returncontent включено."
type: docs
url: /ru/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

Тип файла возвращаемого содержимого изображения, когда включено свойство `return_content`.

Если не задано (по умолчанию `None`), содержимое изображения возвращается в его оригинальном формате, определённом в [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/). Поддерживаемые значения: [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), и [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). Если указан неподдерживаемый формат, возвращается оригинальный формат.

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
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
