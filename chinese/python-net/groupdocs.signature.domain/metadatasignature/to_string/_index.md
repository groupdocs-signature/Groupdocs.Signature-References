---
title: "to_string 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "将元数据签名转换为字符串。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/metadatasignature/to_string/
is_root: false
weight: 1180
---


## to_string

将元数据签名转换为字符串。

将布尔属性转换为 "True" 或 "False"。对于其他数据类型，将使用默认的数据格式提供程序。

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format}

使用指定的格式将元数据签名转换为字符串。

将布尔属性转换为 "True" 或 "False"。默认文化属性信息将从 SignatureSettings 属性 [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) 中获取。

```python
def to_string(self, format):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| format | `str` | 数据格式字符串。 |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

使用指定格式转换为字符串。

将布尔属性转换为 "True" 或 "False"。

```python
def to_string(self, format, provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| format | `str` | 数据格式字符串。 |
| provider | `System.IFormatProvider` | 用于数据转换操作的格式化数据提供程序。 |

**Returns:** The metadata signature value as a string.

### 另见
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
