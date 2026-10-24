---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует подпись метаданных изображения с указанным идентификатором и значением."
type: docs
url: /ru/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#id-value}

Инициализирует подпись метаданных изображения с указанным идентификатором и значением.

```python
def __init__(self, id, value):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| id | `System.UInt16` | Уникальный идентификатор подписи метаданных изображения. См. ссылки для спецификаций тегов EXIF, чтобы узнать возможные значения идентификатора. |
| value | `Any` | Значение метаданных. |

### Пример

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import ImageMetadataSignature

with Signature("sample.png") as signature:
    options = MetadataSignOptions()
    metadata_id = 41996
    options.add(ImageMetadataSignature(metadata_id, "Mr. Sherlock Holmes"))  # text
    options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
    options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # integer
    options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # float
    result = signature.sign("signed.png", options)
```

### См. также
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
