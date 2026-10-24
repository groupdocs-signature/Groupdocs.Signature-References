---
title: "try_parse метод"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Возвращает тип QRCode, соответствующий указанному имени типа разбора, или None, если имя неизвестно."
type: docs
url: /ru/python-net/groupdocs.signature.domain/qrcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

Возвращает тип QRCode, соответствующий указанному имени типа разбора, или None, если имя неизвестно.

```python
def try_parse(cls, parsing_type):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| parsing_type | `str` | Исходная строка имени типа QRCode. |

**Returns:** QrCodeTypes or None: QRCode type instance, or None when the name is not recognized.

### См. также
* class [`QrCodeTypes`](/signature/python-net/groupdocs.signature.domain/qrcodetypes/)
