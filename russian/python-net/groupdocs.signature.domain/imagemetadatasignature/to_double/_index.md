---
title: "метод to_double"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Преобразует в float."
type: docs
url: /ru/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/
is_root: false
weight: 1110
---


## to_double

Преобразует в float.

Вызывает исключение, если значение metadata не может быть преобразовано. Если исходное значение является строковым, используется культура по умолчанию из [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_double(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as a float.

## to_double {#provider}

Преобразует значение подписи метаданных в тип float.

Использует указанный провайдер формата данных для выполнения преобразования.

```python
def to_double(self, provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Поставщик формата данных для использования в операциях преобразования данных. |

**Returns:** float: The metadata signature value as a float.

### См. также
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
