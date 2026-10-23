---
title: "to_string 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用重写的 ToString 方法将元数据签名值转换为字符串。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

使用重写的 `ToString` 方法将元数据签名值转换为字符串。

将布尔属性转换为 `True` 或 `False`。对于其他数据类型，使用默认的数据格式提供程序。

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

使用指定的格式将元数据签名转换为字符串。

将布尔属性转换为 "True" 或 "False"。

```python
def to_string(self, format, provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| format | `str` | 数据格式字符串。 |
| provider | `System.IFormatProvider` | 用于数据转换操作的格式化数据提供程序。 |

**Returns:** str: The metadata signature value as a string.

### 另见
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
