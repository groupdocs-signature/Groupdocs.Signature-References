---
title: "add 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "将现有的 MetadataSignature 实例添加到集合中。"
type: docs
url: /zh/python-net/groupdocs.signature.options/metadatasignoptions/add/
is_root: false
weight: 1010
---


## add {#metadata_signature}

将现有的 MetadataSignature 实例添加到集合中。

```python
def add(self, metadata_signature):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| metadata_signature | `MetadataSignature` | 要添加的现有 MetadataSignature 实例。 |

**Returns:** The MetadataSignOptions instance.

### 示例

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr.Scherlock Holmes"))
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s)")
```

### 另见
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
