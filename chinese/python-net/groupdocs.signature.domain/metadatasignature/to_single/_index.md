---
title: "to_single 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "将元数据签名值转换为浮点数。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/metadatasignature/to_single/
is_root: false
weight: 1160
---


## to_single

将元数据签名值转换为浮点数。

如果元数据值无法转换，则引发异常。如果原始值是基于字符串的，将使用来自 [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) 的默认文化。

```python
def to_single(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_single {#provider}

转换为浮点数。

```python
def to_single(self, provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| provider | `System.IFormatProvider` | 用于数据转换操作的格式化数据提供程序。 |

**Returns:** float: The Metadata Signature value as float.

### 另见
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
