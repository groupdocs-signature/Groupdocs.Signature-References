---
title: add_image_signature method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Creates a new ImageMetadataSignature with the given arguments and adds it to the collection."
type: docs
url: /python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/
is_root: false
weight: 1020
---


## add_image_signature {#id-value}

Creates a new ImageMetadataSignature with the given arguments and adds it to the collection.

```python
def add_image_signature(self, id, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| id | `System.UInt16` | Unique identifier for the Image Metadata Signature name. See references for Exif tag specifications for possible id values. |
| value | `Any` | Metadata value. |

**Returns:** ImageMetadataSignature: The newly created signature that was added to the MetadataSignatures collection.

### See Also
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
