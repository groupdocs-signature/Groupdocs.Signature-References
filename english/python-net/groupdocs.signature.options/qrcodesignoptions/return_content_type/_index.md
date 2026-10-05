---
title: return_content_type property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The file type of the returned image content of the QR‑Code signature when the returncontent property is enabled."
type: docs
url: /python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/
is_root: false
weight: 2160
---


## return_content_type property

The file type of the returned image content of the QR‑Code signature when the `return_content` property is enabled.

By default it is `None`, which returns the QR‑Code image content in its original format as specified by [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/).

Supported values are [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), and [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). If an unsupported format is provided, the content is returned in PNG format.

### Definition:
```python
@property
def return_content_type(self):
    ...
@return_content_type.setter
def return_content_type(self, value):
    ...
```

### See Also
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
