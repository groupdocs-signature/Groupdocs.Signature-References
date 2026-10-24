---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует WordProcessingMetadataSignature с указанным именем и пустым значением."
type: docs
url: /ru/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Инициализирует WordProcessingMetadataSignature с указанным именем и пустым значением.

```python
def __init__(self, name):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| name | `str` | Имя подписи метаданных WordProcessing. |

### Пример

```python
from datetime import datetime
from groupdocs.signature.domain import WordProcessingMetadataSignature

# Создайте подписи метаданных с именем и значением
author_sig = WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = WordProcessingMetadataSignature("DateCreated", datetime.now())
id_sig = WordProcessingMetadataSignature("DocumentId", 123456)
float_sig = WordProcessingMetadataSignature("SignatureId", 123.456)
```

## __init__ {#name-value}

Инициализирует метаданные подписи WordProcessing с предопределёнными значениями.

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
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### См. также
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
