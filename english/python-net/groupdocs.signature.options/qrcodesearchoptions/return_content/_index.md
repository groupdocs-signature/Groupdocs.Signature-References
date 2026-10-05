---
title: return_content property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The flag that determines whether QR‑Code image content is returned for each signature on a document page."
type: docs
url: /python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/
is_root: false
weight: 2040
---


## return_content property

The flag that determines whether QR‑Code image content is returned for each signature on a document page. When set to True, the raw image data is kept in the signature’s `content` property using the format specified by `return_content_type`. Disabled by default.

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
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
