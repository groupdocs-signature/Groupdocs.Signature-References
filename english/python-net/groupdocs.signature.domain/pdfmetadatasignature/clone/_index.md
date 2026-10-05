---
title: clone method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Clone Metadata Signature instance."
type: docs
url: /python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Clone Metadata Signature instance.

```python
def clone(self):
    ...
```

**Returns:** PdfMetadataSignature: Cloned Metadata Signature instance.

### Example

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Clone a standard metadata signature with a new value
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

## clone {#value}

Clones a PDF metadata signature instance with the given value.

```python
def clone(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | `Any` | Value for the new cloned object. |

**Returns:** A cloned metadata signature instance.

### Example

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Clone an existing metadata signature with a new value
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### See Also
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
