---
title: "метод to_string"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Преобразует метаданные подписи в строку, используя переопределённый метод ToString."
type: docs
url: /ru/python-net/groupdocs.signature.domain/certificatemetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Преобразует метаданные подписи в строку, используя переопределённый метод ToString.

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

**Returns:** The metadata signature value as a string.

### См. также
* class [`CertificateMetadataSignature`](/signature/python-net/groupdocs.signature.domain/certificatemetadatasignature/)
