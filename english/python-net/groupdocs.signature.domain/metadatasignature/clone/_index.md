---
title: clone method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Clones a Metadata Signature instance."
type: docs
url: /python-net/groupdocs.signature.domain/metadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Clones a Metadata Signature instance.

```python
def clone(self):
    ...
```

**Returns:** Returns cloned Metadata Signature instance.

### Example

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Create a new metadata signature based on the predefined AUTHOR signature
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

## clone {#value}

Clone Metadata Signature instance with given value.

```python
def clone(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | `Any` | Value for new cloned object. |

**Returns:** MetadataSignature: Cloned Metadata Signature instance with given value.

### Example

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Clone an existing metadata signature with a new value
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### See Also
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
