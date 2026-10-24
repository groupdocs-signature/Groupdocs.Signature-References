---
title: "метод to_string"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Преобразует подпись метаданных в строку."
type: docs
url: /ru/python-net/groupdocs.signature.domain/metadatasignature/to_string/
is_root: false
weight: 1180
---


## to_string

Преобразует подпись метаданных в строку.

Преобразует булево свойство в "True" или "False". Для других типов данных будет использован поставщик формата данных по умолчанию.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format}

Преобразует подпись метаданных в строку, используя указанный формат.

Преобразует булево свойство в "True" или "False". Информация о культуре по умолчанию будет получена из свойств SignatureSettings [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

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

**Returns:** The metadata signature value as a string.

### См. также
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
