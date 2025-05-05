---
title: return_content_type property
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/
is_root: false
weight: 100
---

## return_content_type property


Specifies file type of returned image content of the QR-Code signature when ReturnContent property is enabled.
By default it set to Null. That means to return QR-Code image content in original format. 
This image format is specified at [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature#format)
Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. 
If provided format is not supported than QR-Code image content in original .png will be returned.
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
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype)
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions)
