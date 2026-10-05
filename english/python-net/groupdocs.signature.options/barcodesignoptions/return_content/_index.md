---
title: return_content property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The flag indicating whether to retrieve the barcode image content of a signature placed on a document page."
type: docs
url: /python-net/groupdocs.signature.options/barcodesignoptions/return_content/
is_root: false
weight: 2110
---


## return_content property

The flag indicating whether to retrieve the barcode image content of a signature placed on a document page.

When set to True, the barcode signature image content is retained as raw image data in the format specified by `return_content_type`. By default, this option is disabled (False).

### Definition:
```python
@property
def return_content(self):
    ...
@return_content.setter
def return_content(self, value):
    ...
```

### See Also
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
