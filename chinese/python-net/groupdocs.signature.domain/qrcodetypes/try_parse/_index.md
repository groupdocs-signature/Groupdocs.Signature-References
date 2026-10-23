---
title: "try_parse 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "返回与给定解析类型名称匹配的 QRCode 类型，如果名称未知则返回 None。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/qrcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

返回与给定解析类型名称匹配的 QRCode 类型，如果名称未知则返回 None。

```python
def try_parse(cls, parsing_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| parsing_type | `str` | QRCode 类型名称的源字符串。 |

**Returns:** QrCodeTypes or None: QRCode type instance, or None when the name is not recognized.

### 另见
* class [`QrCodeTypes`](/signature/python-net/groupdocs.signature.domain/qrcodetypes/)
