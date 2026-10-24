---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует подпись метаданных PDF с предопределённым именем и пустым значением."
type: docs
url: /ru/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Инициализирует подпись метаданных PDF с предопределённым именем и пустым значением.

```python
def __init__(self, name):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| name | `str` | Имя подписи метаданных PDF. |

## __init__ {#name-value}

Инициализирует подпись метаданных PDF с предопределёнными значениями.

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
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr. Sherlock Holmes"))
    options.add(PdfMetadataSignature("CreatedOn", datetime.now()))
    options.add(PdfMetadataSignature("DocumentId", 123456))
    options.add(PdfMetadataSignature("SignatureId", 123.456))
    result = signature.sign("signed.pdf", options)
```

## __init__ {#name-value-tag}

Инициализирует подпись метаданных PDF с предопределёнными значениями.

```python
def __init__(self, name, value, tag):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| name | `str` | Имя объекта подписи метаданных. |
| value | `Any` | Значение подписи метаданных. |
| tag | `str` | Тег префикса подписи метаданных. |

### Пример

```python
from groupdocs.signature.domain import PdfMetadataSignature

# Создать подпись метаданных для автора PDF
author_sig = PdfMetadataSignature("Author", "Mr. Sherlock Holmes")

# Создать подпись метаданных для даты создания
from datetime import datetime
created_sig = PdfMetadataSignature("CreatedOn", datetime.now())

# Создать подпись метаданных для числового идентификатора
id_sig = PdfMetadataSignature("DocumentId", 123456)

# Создать подпись метаданных для значения с плавающей точкой
float_sig = PdfMetadataSignature("SignatureId", 123.456)
```

### См. также
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
