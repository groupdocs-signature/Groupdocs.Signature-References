---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a BarcodeSignature object with a signature identifier obtained after a search process."
type: docs
url: /python-net/groupdocs.signature.domain/barcodesignature/__init__/
is_root: false
weight: 10
---


## __init__ {#signature_id}

Initializes a BarcodeSignature object with a signature identifier obtained after a search process. The identifier is used to retrieve additional properties for this signature from the document's signature information layer.

```python
def __init__(self, signature_id):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| signature_id | `str` | Unique signature identifier obtained by the `Sign` or `Search` method of `Signature`. |

### See Also
* class [`BarcodeSignature`](/signature/python-net/groupdocs.signature.domain/barcodesignature/)
