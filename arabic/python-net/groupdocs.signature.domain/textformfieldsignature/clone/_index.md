---
title: "طريقة clone"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "استنساخ نسخة من FormField Signature."
type: docs
url: /ar/python-net/groupdocs.signature.domain/textformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

استنساخ نسخة من FormField Signature.

```python
def clone(self):
    ...
```

**Returns:** TextFormFieldSignature: Cloned FormField Signature instance.

### مثال

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    new_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### انظر أيضًا
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
