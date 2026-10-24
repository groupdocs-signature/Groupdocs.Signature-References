---
title: "метод clone"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Создайте копию экземпляра подписи FormField."
type: docs
url: /ru/python-net/groupdocs.signature.domain/textformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

Создайте копию экземпляра подписи FormField.

```python
def clone(self):
    ...
```

**Returns:** TextFormFieldSignature: Cloned FormField Signature instance.

### Пример

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    new_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### См. также
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
