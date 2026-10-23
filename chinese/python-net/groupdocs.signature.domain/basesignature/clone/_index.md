---
title: "clone 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "克隆签名实例。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/basesignature/clone/
is_root: false
weight: 1010
---


## clone

克隆签名实例。

```python
def clone(self):
    ...
```

**Returns:** The cloned `Signature` instance.

### 示例

```python
    from datetime import datetime
    from groupdocs.signature.domain import PdfMetadataSignatures

    # 克隆具有新值的元数据签名
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### 另见
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)
