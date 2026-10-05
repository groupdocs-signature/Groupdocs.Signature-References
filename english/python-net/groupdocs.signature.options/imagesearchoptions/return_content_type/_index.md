---
title: return_content_type property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The file type of the returned image content when the returncontent property is enabled."
type: docs
url: /python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

The file type of the returned image content when the `return_content` property is enabled.

If not set (default `None`), the image content is returned in its original format as defined by [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/). Supported values are [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), and [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). If an unsupported format is provided, the original format is returned.

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
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
