---
title: "to_date_time 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "将元数据签名值转换为日期时间。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/
is_root: false
weight: 1090
---


## to_date_time

将元数据签名值转换为日期时间。

如果元数据值无法转换，将抛出异常。当原始值为字符串时，将使用来自[`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/)的默认文化进行转换。

```python
def to_date_time(self):
    ...
```

**Returns:** datetime: The metadata signature value as a datetime.

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    for metadata in result.signatures:
        try:
            dt = metadata.to_date_time()
            print(f"{metadata.name} as datetime: {dt}")
        except Exception as e:
            print(f"Could not convert {metadata.name} to datetime: {e}")
```

## to_date_time {#provider}

将元数据签名值转换为日期时间。

```python
def to_date_time(self, provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| provider | `System.IFormatProvider` | 用于数据转换操作的格式化数据提供程序。 |

**Returns:** datetime.datetime: The metadata signature value as a datetime.

如果元数据值无法转换，将抛出异常。

### 另见
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
