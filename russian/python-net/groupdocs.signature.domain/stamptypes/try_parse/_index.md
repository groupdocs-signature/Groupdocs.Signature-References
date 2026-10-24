---
title: "try_parse метод"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Возвращает тип штампа для указанного имени типа разбора."
type: docs
url: /ru/python-net/groupdocs.signature.domain/stamptypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

Возвращает тип штампа для заданного имени типа разбора. Если имя штампа неизвестно, исключение не выбрасывается, и метод возвращает None.

```python
def try_parse(cls, parsing_type):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| parsing_type | `str` | Исходная строка имени типа штампа. |

**Returns:** StampType: StampType instance.

### См. также
* class [`StampTypes`](/signature/python-net/groupdocs.signature.domain/stamptypes/)
