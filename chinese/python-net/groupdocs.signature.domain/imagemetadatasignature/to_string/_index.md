---
title: "to_string 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "将元数据签名值转换为字符串。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/
is_root: false
weight: 1170
---


## to_string

将元数据签名值转换为字符串。

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value.

## to_string {#format}

使用指定的格式将元数据签名值转换为字符串。

将布尔属性转换为 "True" 或 "False"。使用来自 [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) 的默认文化信息。

```python
def to_string(self, format):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| format | `str` | 数据格式字符串。 |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

将转换为具有指定格式的字符串。

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
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
