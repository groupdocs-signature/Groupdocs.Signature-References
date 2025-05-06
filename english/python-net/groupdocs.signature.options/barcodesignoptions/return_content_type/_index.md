---
title: return_content_type property
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/
is_root: false
weight: 270
---

## return_content_type property


Specifies file type of returned image content of the Barcode signature when ReturnContent property is enabled.
By default it set to Null. That means to return Barcode image content in original format. 
This image format is specified at [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature#format)
Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. 
If provided format is not supported than Barcode image content in .png format will be returned.
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
* module [`groupdocs.signature.options`](../../)
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions)
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype)
