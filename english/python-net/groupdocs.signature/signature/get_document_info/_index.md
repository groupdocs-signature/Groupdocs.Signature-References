---
title: get_document_info method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Gets information about document pages: their sizes, maximum page height, the width of a page with the maximum height."
type: docs
url: /python-net/groupdocs.signature/signature/get_document_info/
is_root: false
weight: 1130
---


## get_document_info

Gets information about document pages: their sizes, maximum page height, the width of a page with the maximum height.

Learn more about signed document - file type, pages count and many other format specific properties:
- https://docs.groupdocs.com/display/signaturenet/Get+document+information

```python
def get_document_info(self):
    ...
```

**Returns:** Information about document.

### Example

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    info = signature.get_document_info()
    print(f"File type: {info.file_type.file_format}")
    print(f"Pages count: {info.page_count}")
    print(f"File size: {info.size} bytes")
    for page in info.pages:
        # page_number is 0-based: 0 is the first page
        print(f"Page {page.page_number}: {page.width} x {page.height}")
```

### See Also
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
