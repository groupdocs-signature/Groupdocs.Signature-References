---
title: "метод to_single"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Преобразует в тип float."
type: docs
url: /ru/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/
is_root: false
weight: 1150
---


## to_single

Преобразует в тип float.

Выбрасывает исключение, если значение метаданных не может быть преобразовано. Если исходное значение основано на строке, информация о свойстве культуры по умолчанию будет использована из [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_single(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as float.

## to_single {#provider}

Преобразует значение подписи метаданных в тип float.

Вызывает исключение, если значение метаданных не может быть преобразовано.

```python
def to_single(self, provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Поставщик формата данных для использования в операциях преобразования данных. |

**Returns:** float: The metadata signature value as a float.

### См. также
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
