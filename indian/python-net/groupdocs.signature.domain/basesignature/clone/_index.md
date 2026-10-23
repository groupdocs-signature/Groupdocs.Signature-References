---
title: "clone मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "हस्ताक्षर इंस्टेंस को क्लोन करें।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/basesignature/clone/
is_root: false
weight: 1010
---


## clone

हस्ताक्षर इंस्टेंस को क्लोन करें।

```python
def clone(self):
    ...
```

**Returns:** The cloned `Signature` instance.

### उदाहरण

```python
    from datetime import datetime
    from groupdocs.signature.domain import PdfMetadataSignatures

    # नए मान के साथ एक मेटाडाटा हस्ताक्षर को क्लोन करें
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### संबंधित देखें
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)
