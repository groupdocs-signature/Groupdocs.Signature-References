---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует PresentationMetadataSignature с указанным именем и пустым значением."
type: docs
url: /ru/python-net/groupdocs.signature.domain/presentationmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Инициализирует PresentationMetadataSignature с указанным именем и пустым значением.

```python
def __init__(self, name):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| name | `str` | Имя подписи Presentation Metadata. |

## __init__ {#name-value}

Инициализирует PresentationMetadataSignature с предопределёнными значениями.

```python
def __init__(self, name, value):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| name | `str` | Имя объекта подписи метаданных. |
| value | `Any` | Значение подписи метаданных. |

### Пример

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PresentationMetadataSignature

with Signature("sample.ppsx") as signature:
    options = MetadataSignOptions()
    signatures = [
        PresentationMetadataSignature("Author", "Mr. Sherlock Holmes"),
        PresentationMetadataSignature("DateCreated", datetime.now()),
        PresentationMetadataSignature("DocumentId", 123456),
        PresentationMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.ppsx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### См. также
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
