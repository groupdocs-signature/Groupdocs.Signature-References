---
title: "get_document_info 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "获取文档页面信息：它们的尺寸、最大页面高度以及具有最大高度的页面的宽度。"
type: docs
url: /zh/python-net/groupdocs.signature/signature/get_document_info/
is_root: false
weight: 1130
---


## get_document_info

获取文档页面信息：它们的尺寸、最大页面高度以及具有最大高度的页面的宽度。

了解有关已签名文档的更多信息 - 文件类型、页数以及许多其他特定格式的属性：
- https://docs.groupdocs.com/display/signaturenet/Get+document+information

```python
def get_document_info(self):
    ...
```

**Returns:** Information about document.

### 示例

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    info = signature.get_document_info()
    print(f"File type: {info.file_type.file_format}")
    print(f"Pages count: {info.page_count}")
    print(f"File size: {info.size} bytes")
    for page in info.pages:
        # page_number 是从 0 开始计数的：0 是第一页
        print(f"Page {page.page_number}: {page.width} x {page.height}")
```

### 另见
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
