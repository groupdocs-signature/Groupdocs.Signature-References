---
title: "метод to_string"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Преобразует значение подписи метаданных в строку."
type: docs
url: /ru/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/
is_root: false
weight: 1170
---


## to_string

Преобразует значение подписи метаданных в строку.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value.

## to_string {#format}

Преобразует значение подписи метаданных в строку, используя указанный формат.

Преобразует булево свойство в "True" или "False". Используется информация о культуре по умолчанию из [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_string(self, format):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| format | `str` | Строка формата данных. |

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

**Returns:** str: The metadata signature value as a string.

### См. также
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
