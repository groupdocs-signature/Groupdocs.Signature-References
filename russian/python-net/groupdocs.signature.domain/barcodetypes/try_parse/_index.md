---
title: "try_parse метод"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Возвращает тип Barcode, соответствующий указанному имени типа разбора."
type: docs
url: /ru/python-net/groupdocs.signature.domain/barcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

Возвращает тип Barcode, соответствующий указанному имени типа разбора.

Если имя неизвестно, метод возвращает None вместо возбуждения исключения.

```python
def try_parse(cls, parsing_type):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| parsing_type | `str` | Исходная строка названия типа штрихкода. |

**Returns:** BarcodeType: The matching BarcodeType instance, or None if not found.

### См. также
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
