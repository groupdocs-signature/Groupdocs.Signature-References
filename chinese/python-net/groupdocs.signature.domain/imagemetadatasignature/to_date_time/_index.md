---
title: "to_date_time 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "将元数据签名值转换为 datetime.datetime。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/
is_root: false
weight: 1070
---


## to_date_time

将元数据签名值转换为 `datetime.datetime`。

如果元数据值无法转换，则引发异常。如果原始值是基于字符串的，将使用来自 [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) 的默认文化。

```python
def to_date_time(self):
    ...
```

**Returns:** datetime.datetime: The metadata signature value as a `datetime.datetime`.

## to_date_time {#provider}

将元数据签名值转换为 `datetime`。

如果元数据值无法转换，将抛出异常。

```python
def to_date_time(self, provider):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| provider | `System.IFormatProvider` | 用于数据转换操作的格式化数据提供程序。 |

**Returns:** datetime: The metadata signature value as a `datetime`.

### 另见
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
