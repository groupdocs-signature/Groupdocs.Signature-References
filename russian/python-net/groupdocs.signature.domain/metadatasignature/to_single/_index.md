---
title: "метод to_single"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Преобразует значение подписи метаданных в тип float."
type: docs
url: /ru/python-net/groupdocs.signature.domain/metadatasignature/to_single/
is_root: false
weight: 1160
---


## to_single

Преобразует значение подписи метаданных в тип float.

Вызывает исключение, если значение metadata не может быть преобразовано. Если исходное значение является строковым, используется культура по умолчанию из [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_single(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_single {#provider}

Преобразует в тип float.

```python
def to_single(self, provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Поставщик формата данных для использования в операциях преобразования данных. |

**Returns:** float: The Metadata Signature value as float.

### См. также
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
