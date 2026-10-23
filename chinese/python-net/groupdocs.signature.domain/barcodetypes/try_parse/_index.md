---
title: "try_parse 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "返回与给定解析类型名称匹配的 Barcode 类型。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/barcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

返回与给定解析类型名称匹配的 Barcode 类型。

如果名称未知，方法返回 None 而不是抛出异常。

```python
def try_parse(cls, parsing_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| parsing_type | `str` | 条形码类型名称的源字符串。 |

**Returns:** BarcodeType: The matching BarcodeType instance, or None if not found.

### 另见
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
