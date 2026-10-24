---
title: "метод clone"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Клонирует экземпляр подписи FormField."
type: docs
url: /ru/python-net/groupdocs.signature.domain/comboboxformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

Клонирует экземпляр подписи FormField.

```python
def clone(self):
    ...
```

**Returns:** A cloned FormField signature instance.

### Пример

```python
from groupdocs.signature.domain import ComboboxFormFieldSignature

# Создать оригинальную подпись поля формы combobox
original = ComboboxFormFieldSignature()

# Клонировать подпись
cloned = original.clone()
```

### См. также
* class [`ComboboxFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/)
