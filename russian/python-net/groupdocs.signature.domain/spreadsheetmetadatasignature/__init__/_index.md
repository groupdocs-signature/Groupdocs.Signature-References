---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует подпись метаданных таблицы с предопределённым именем и пустым значением."
type: docs
url: /ru/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Инициализирует подпись метаданных таблицы с предопределённым именем и пустым значением.

```python
def __init__(self, name):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| name | `str` | Имя Spreadsheet Metadata Signature. |

## __init__ {#name-value}

Инициализирует подпись метаданных таблицы с предопределёнными значениями.

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
from groupdocs.signature.domain import SpreadsheetMetadataSignature

# Создать подписи метаданных для электронной таблицы
author_sig = SpreadsheetMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = SpreadsheetMetadataSignature("DateCreated", datetime.now())
id_sig = SpreadsheetMetadataSignature("DocumentId", 123456)
float_sig = SpreadsheetMetadataSignature("SignatureId", 123.456)
```

### См. также
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
