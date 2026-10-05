---
title: add method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Add existing MetadataSignature instance to collection."
type: docs
url: /python-net/groupdocs.signature.options/metadatasignoptions/add/
is_root: false
weight: 1010
---


## add {#metadata_signature}

Add existing MetadataSignature instance to collection.

```python
def add(self, metadata_signature):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| metadata_signature | `MetadataSignature` | The existing MetadataSignature instance to be added. |

**Returns:** The MetadataSignOptions instance.

### Example

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr.Scherlock Holmes"))
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s)")
```

### See Also
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
