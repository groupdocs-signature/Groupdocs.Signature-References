---
title: "метод to_string"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Преобразует значение подписи метаданных в строку, используя переопределённый метод ToString."
type: docs
url: /ru/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Преобразует значение подписи метаданных в строку с помощью переопределённого метода `ToString`.

Преобразует логическое свойство в `True` или `False`. Для других типов данных используется поставщик формата данных по умолчанию.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Преобразует подпись метаданных в строку, используя указанный формат.

Преобразует булево свойство в "True" или "False".

```python
def to_string(self, format, provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| format | `str` | Строка формата данных. |
| provider | `System.IFormatProvider` | Поставщик формата данных для использования в операциях преобразования данных. |

**Returns:** str: The metadata signature value as a string.

### См. также
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
