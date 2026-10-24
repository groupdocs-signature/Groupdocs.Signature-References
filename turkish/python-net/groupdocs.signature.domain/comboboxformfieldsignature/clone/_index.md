---
title: "clone metodu"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "FormField imza örneğini kopyalar."
type: docs
url: /tr/python-net/groupdocs.signature.domain/comboboxformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

FormField imza örneğini kopyalar.

```python
def clone(self):
    ...
```

**Returns:** A cloned FormField signature instance.

### Örnek

```python
from groupdocs.signature.domain import ComboboxFormFieldSignature

# Orijinal bir combobox form alanı imzası oluştur
original = ComboboxFormFieldSignature()

# İmzayı kopyala
cloned = original.clone()
```

### Ayrıca Bakınız
* class [`ComboboxFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/)
