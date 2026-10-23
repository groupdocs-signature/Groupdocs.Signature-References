---
title: "clone मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "FormField Signature इंस्टेंस को क्लोन करें।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/textformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

FormField Signature इंस्टेंस को क्लोन करें।

```python
def clone(self):
    ...
```

**Returns:** TextFormFieldSignature: Cloned FormField Signature instance.

### उदाहरण

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    new_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### संबंधित देखें
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
