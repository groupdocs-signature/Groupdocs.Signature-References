---
title: clone method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Clone signature instance."
type: docs
url: /python-net/groupdocs.signature.domain/basesignature/clone/
is_root: false
weight: 1010
---


## clone

Clone signature instance.

```python
def clone(self):
    ...
```

**Returns:** The cloned `Signature` instance.

### Example

```python
    from datetime import datetime
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Clone a metadata signature with a new value
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### See Also
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)
