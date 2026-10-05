---
title: return_content property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The flag to retrieve QR-Code image content of a signature placed on a document page."
type: docs
url: /python-net/groupdocs.signature.options/qrcodesignoptions/return_content/
is_root: false
weight: 2150
---


## return_content property

The flag to retrieve QR-Code image content of a signature placed on a document page.

If set to True, the QR-Code signature image content is kept as raw image data in the format specified by [`QrCodeSignOptions.ReturnContentType`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/). By default, this option is disabled.

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
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
