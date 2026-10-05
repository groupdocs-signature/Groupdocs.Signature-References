---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a new instance of the MetadataSearchOptions class with default values."
type: docs
url: /python-net/groupdocs.signature.options/metadatasearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the MetadataSearchOptions class with default values.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    print(f"Found {len(result.signatures)} metadata signature(s)")
```

### See Also
* class [`MetadataSearchOptions`](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/)
