---
title: "метод to_decimal"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Преобразует значение подписи метаданных в тип Decimal."
type: docs
url: /ru/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/
is_root: false
weight: 1110
---


## to_decimal

Преобразует значение подписи метаданных в тип Decimal.

Генерирует исключение, если значение метаданных не может быть преобразовано. Если исходное значение строковое, информация о культуре по умолчанию будет получена из [`SignatureSettings.DefaultCulture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_decimal(self):
    ...
```

**Returns:** The metadata signature value as Decimal.

## to_decimal {#provider}

Преобразует значение подписи метаданных в тип Decimal.

```python
def to_decimal(self, provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Поставщик формата данных для использования в операциях преобразования данных. |

**Returns:** The metadata signature value as Decimal.

### См. также
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
