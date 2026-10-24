---
title: "Свойство reference"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Ссылка на платеж кредитора."
type: docs
url: /ru/python-net/groupdocs.signature.domain.extensions/swissqr/reference/
is_root: false
weight: 2070
---


## reference property

Ссылка на платеж кредитора.

Это обязательное поле для SwissQR IBAN (IBAN в диапазоне от CHxx30000xxxxxx до CHxx31999xxxxx). Если указано, ссылка должна быть либо действительной ссылкой SwissQR (соответствующей форме ISR), либо действительной ссылкой кредитора согласно ISO 11649 (\"RFxxxx\"). Оба могут содержать пробелы для форматирования.

### Definition:
```python
@property
def reference(self):
    ...
@reference.setter
def reference(self, value):
    ...
```

### См. также
* class [`SwissQR`](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/)
