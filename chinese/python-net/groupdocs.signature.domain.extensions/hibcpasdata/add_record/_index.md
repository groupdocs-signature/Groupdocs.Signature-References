---
title: "add_record 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "添加一个新的 HIBCPASRecord，使用给定的数据类型和数据。"
type: docs
url: /zh/python-net/groupdocs.signature.domain.extensions/hibcpasdata/add_record/
is_root: false
weight: 1010
---


## add_record {#data_type-data}

添加一个新的[`HIBCPASRecord`](/signature/python-net/groupdocs.signature.domain.extensions/hibcpasrecord/)，使用给定的数据类型和数据。

```python
def add_record(self, data_type, data):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| data_type | `HIBCPASDataType` | 记录的数据类型。 |
| data | `str` | 记录数据。 |

## add_record {#record}

添加新记录。

```python
def add_record(self, record):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| record | `HIBCPASRecord` | 待添加的记录。 |

**Returns:** Reference to the instance itself.

### 另见
* class [`HIBCPASData`](/signature/python-net/groupdocs.signature.domain.extensions/hibcpasdata/)
