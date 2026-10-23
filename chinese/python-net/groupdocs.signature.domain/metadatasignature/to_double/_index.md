---
title: "to_double 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "将元数据签名值转换为浮点数。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/metadatasignature/to_double/
is_root: false
weight: 1130
---


## to_double

将元数据签名值转换为浮点数。

如果元数据值无法转换，将抛出异常。如果原始值为字符串，则使用来自[`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/)的默认文化。

```python
def to_double(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_double {#provider}

转换为双精度。

```python
def to_double(self, provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| provider | `System.IFormatProvider` | 用于数据转换操作的格式化数据提供程序。 |

**Returns:** float: The metadata signature value as a float.

### 另见
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
