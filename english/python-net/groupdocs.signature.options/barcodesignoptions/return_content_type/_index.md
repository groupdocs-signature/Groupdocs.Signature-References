---
title: return_content_type property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The file type of the returned image content of the Barcode signature when the returncontent property is enabled."
type: docs
url: /python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/
is_root: false
weight: 2120
---


## return_content_type property

The file type of the returned image content of the Barcode signature when the `return_content` property is enabled.

By default it is set to `None`, which means the Barcode image content is returned in its original format. The image format is specified by [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/). Supported values are [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), and [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). If a format that is not supported is provided, the Barcode image content will be returned in PNG format.

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
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
