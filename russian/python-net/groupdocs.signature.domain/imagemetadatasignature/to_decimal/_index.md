---
title: "метод to_decimal"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Преобразует в Decimal."
type: docs
url: /ru/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/
is_root: false
weight: 1090
---


## to_decimal

Преобразует в Decimal.

Генерирует исключение, если значение метаданных не может быть преобразовано. Если исходное значение строковое, используется культура по умолчанию из [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_decimal(self):
    ...
```

**Returns:** decimal.Decimal: The Image Metadata Signature value as Decimal.

## to_decimal {#provider}

Преобразует значение подписи метаданных в десятичное число.

Вызывает исключение, если значение метаданных не может быть преобразовано.

```python
def to_decimal(self, provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Поставщик формата данных для использования в операциях преобразования данных. |

**Returns:** float: The metadata signature value as a decimal.

### См. также
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
