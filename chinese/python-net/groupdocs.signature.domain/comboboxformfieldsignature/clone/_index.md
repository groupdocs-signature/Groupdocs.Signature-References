---
title: "clone 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "克隆 FormField 签名实例。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/comboboxformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

克隆 FormField 签名实例。

```python
def clone(self):
    ...
```

**Returns:** A cloned FormField signature instance.

### 示例

```python
from groupdocs.signature.domain import ComboboxFormFieldSignature

# 创建原始的下拉框表单字段签名
original = ComboboxFormFieldSignature()

# 克隆签名
cloned = original.clone()
```

### 另见
* class [`ComboboxFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/)
