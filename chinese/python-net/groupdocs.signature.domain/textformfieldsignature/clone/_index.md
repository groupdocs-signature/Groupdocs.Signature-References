---
title: "clone 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "克隆 FormField Signature 实例。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/textformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

克隆 FormField Signature 实例。

```python
def clone(self):
    ...
```

**Returns:** TextFormFieldSignature: Cloned FormField Signature instance.

### 示例

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    new_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### 另见
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
