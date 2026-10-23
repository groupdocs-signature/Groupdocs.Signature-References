---
title: "destination_post_code_and_dps 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "该属性保存带有 DPS 的收货地址邮编，对于内陆地址，其由地区（1‑2 个字符）、区（1‑2 个字符）、段（1 个字符）、单元（2 个字符）以及……组成。"
type: docs
url: /zh/python-net/groupdocs.signature.domain.extensions/mailmark2d/destination_post_code_and_dps/
is_root: false
weight: 2050
---


## destination_post_code_and_dps property

该属性保存带有 DPS 的收货地址邮政编码，对于内陆地址，其由区域（1‑2 个字符）、地区（1‑2 个字符）、区段（1 个字符）、单元（2 个字符）和 DPS（2 个字符）组成，必须符合有效的 PAF® 格式，且最大长度为 9 个字符。

### Definition:
```python
@property
def destination_post_code_and_dps(self):
    ...
@destination_post_code_and_dps.setter
def destination_post_code_and_dps(self, value):
    ...
```

### 另见
* class [`Mailmark2D`](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/)
