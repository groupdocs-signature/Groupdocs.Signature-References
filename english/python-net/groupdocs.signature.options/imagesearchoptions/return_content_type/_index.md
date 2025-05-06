---
title: return_content_type property
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/
is_root: false
weight: 90
---

## return_content_type property


Specifies file type of returned content of the image signature when ReturnContent property is enabled.
By default it set to Null. That means to return image content in original format. 
This image format is specified at [`ImageSignature.format`](/signature/python-net/groupdocs.signature.domain/imagesignature#format)
Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. 
If provided format is not supported than image content in original format will be returned.
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
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions)
