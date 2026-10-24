---
title: "метод to_date_time"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Преобразует значение подписи метаданных в дату и время."
type: docs
url: /ru/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/
is_root: false
weight: 1090
---


## to_date_time

Преобразует значение подписи метаданных в дату и время.

Если значение метаданных не может быть преобразовано, генерируется исключение. Когда исходное значение является строковым, для преобразования используется культура по умолчанию из [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_date_time(self):
    ...
```

**Returns:** datetime: The metadata signature value as a datetime.

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    for metadata in result.signatures:
        try:
            dt = metadata.to_date_time()
            print(f"{metadata.name} as datetime: {dt}")
        except Exception as e:
            print(f"Could not convert {metadata.name} to datetime: {e}")
```

## to_date_time {#provider}

Преобразует значение подписи метаданных в дату и время.

```python
def to_date_time(self, provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Поставщик формата данных для использования в операциях преобразования данных. |

**Returns:** datetime.datetime: The metadata signature value as a datetime.

Выбрасывает исключение, если значение метаданных не может быть преобразовано.

### См. также
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
