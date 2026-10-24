---
title: "метод to_date_time"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Преобразует значение подписи метаданных в datetime.datetime."
type: docs
url: /ru/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/
is_root: false
weight: 1070
---


## to_date_time

Преобразует значение подписи метаданных в `datetime.datetime`.

Вызывает исключение, если значение metadata не может быть преобразовано. Если исходное значение является строковым, используется культура по умолчанию из [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_date_time(self):
    ...
```

**Returns:** datetime.datetime: The metadata signature value as a `datetime.datetime`.

## to_date_time {#provider}

Преобразует значение подписи метаданных в `datetime`.

Выбрасывает исключение, если значение метаданных не может быть преобразовано.

```python
def to_date_time(self, provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Поставщик формата данных для использования в операциях преобразования данных. |

**Returns:** datetime: The metadata signature value as a `datetime`.

### См. также
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
