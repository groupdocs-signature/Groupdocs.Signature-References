---
title: return_content_type property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The file type of the returned image content for a Barcode signature when the returncontent property is enabled."
type: docs
url: /python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

The file type of the returned image content for a Barcode signature when the `return_content` property is enabled.

By default it is None, which returns the barcode image in its original format as specified by [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/).

Supported values are [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), and [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). If a value other than these is provided, the image will be returned in PNG format.

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
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
