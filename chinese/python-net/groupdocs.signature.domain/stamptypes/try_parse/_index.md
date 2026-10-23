---
title: "try_parse 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "返回给定解析类型名称的印章类型。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/stamptypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

返回给定解析类型名称的印章类型。如果印章名称未知，不会抛出异常，方法返回 None。

```python
def try_parse(cls, parsing_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| parsing_type | `str` | 印章类型名称的源字符串。 |

**Returns:** StampType: StampType instance.

### 另见
* class [`StampTypes`](/signature/python-net/groupdocs.signature.domain/stamptypes/)
