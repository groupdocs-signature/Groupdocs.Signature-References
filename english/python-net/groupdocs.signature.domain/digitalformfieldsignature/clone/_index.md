---
title: clone method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Clones FormField Signature instance."
type: docs
url: /python-net/groupdocs.signature.domain/digitalformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

Clones FormField Signature instance.

```python
def clone(self):
    ...
```

**Returns:** DigitalFormFieldSignature: Cloned FormField Signature instance.

### Example

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Clone a metadata signature with a new value
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### See Also
* class [`DigitalFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/digitalformfieldsignature/)
