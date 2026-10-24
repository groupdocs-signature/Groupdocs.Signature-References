---
title: "clone metodu"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "FormField Signature örneğini kopyalar."
type: docs
url: /tr/python-net/groupdocs.signature.domain/textformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

FormField Signature örneğini kopyalar.

```python
def clone(self):
    ...
```

**Returns:** TextFormFieldSignature: Cloned FormField Signature instance.

### Örnek

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    new_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### Ayrıca Bakınız
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
