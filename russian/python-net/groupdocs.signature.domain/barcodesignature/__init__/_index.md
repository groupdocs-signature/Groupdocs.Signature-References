---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует объект BarcodeSignature с идентификатором подписи, полученным после процесса поиска."
type: docs
url: /ru/python-net/groupdocs.signature.domain/barcodesignature/__init__/
is_root: false
weight: 10
---


## __init__ {#signature_id}

Инициализирует объект BarcodeSignature с идентификатором подписи, полученным после процесса поиска. Идентификатор используется для получения дополнительных свойств этой подписи из слоя информации о подписи документа.

```python
def __init__(self, signature_id):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| signature_id | `str` | Уникальный идентификатор подписи, полученный методом `Sign` или `Search` класса `Signature`. |

### См. также
* class [`BarcodeSignature`](/signature/python-net/groupdocs.signature.domain/barcodesignature/)
