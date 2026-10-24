---
title: "parse метод"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Возвращает экземпляр BarcodeType для указанного имени типа разбора."
type: docs
url: /ru/python-net/groupdocs.signature.domain/barcodetypes/parse/
is_root: false
weight: 1010
---


## parse {#parsing_type}

Возвращает экземпляр BarcodeType для указанного имени типа разбора.

Если имя штрих‑кода неизвестно, генерируется исключение.

```python
def parse(cls, parsing_type):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| parsing_type | `str` | Исходная строка названия типа штрихкода. |

**Returns:** BarcodeType: BarcodeType instance.

### См. также
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
