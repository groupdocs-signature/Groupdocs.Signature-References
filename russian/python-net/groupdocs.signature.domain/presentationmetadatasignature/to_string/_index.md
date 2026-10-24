---
title: "метод to_string"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Преобразует подпись метаданных в строку."
type: docs
url: /ru/python-net/groupdocs.signature.domain/presentationmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Преобразует подпись метаданных в строку.

Преобразует булево свойство в "True" или "False". Для других типов данных используется провайдер формата данных по умолчанию.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Преобразует в строку с указанным форматом.

Преобразует булево свойство в "True" или "False".

```python
def to_string(self, format, provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| format | `str` | Строка формата данных. |
| provider | `System.IFormatProvider` | Поставщик формата данных для использования в операциях преобразования данных. |

**Returns:** str: The metadata signature value as string.

### См. также
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
