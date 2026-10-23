---
title: "to_decimal 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "转换为 Decimal。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/
is_root: false
weight: 1090
---


## to_decimal

转换为 Decimal。

如果元数据值无法转换，将抛出异常。如果原始值为字符串，则使用来自[`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/)的默认文化。

```python
def to_decimal(self):
    ...
```

**Returns:** decimal.Decimal: The Image Metadata Signature value as Decimal.

## to_decimal {#provider}

将元数据签名值转换为十进制数。

如果元数据值无法转换，则抛出异常。

```python
def to_decimal(self, provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| provider | `System.IFormatProvider` | 用于数据转换操作的格式化数据提供程序。 |

**Returns:** float: The metadata signature value as a decimal.

### 另见
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
