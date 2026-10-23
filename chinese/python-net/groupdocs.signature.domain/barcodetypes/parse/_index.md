---
title: "parse 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "返回给定解析类型名称的 BarcodeType 实例。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/barcodetypes/parse/
is_root: false
weight: 1010
---


## parse {#parsing_type}

返回给定解析类型名称的 BarcodeType 实例。

如果条形码名称未知，将抛出异常。

```python
def parse(cls, parsing_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| parsing_type | `str` | 条形码类型名称的源字符串。 |

**Returns:** BarcodeType: BarcodeType instance.

### 另见
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
