---
title: "add_record メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "指定されたデータ型とデータで新しい HIBCPASRecord を追加します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain.extensions/hibcpasdata/add_record/
is_root: false
weight: 1010
---


## add_record {#data_type-data}

指定されたデータ型とデータで新しい [`HIBCPASRecord`](/signature/python-net/groupdocs.signature.domain.extensions/hibcpasrecord/) を追加します。

```python
def add_record(self, data_type, data):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| data_type | `HIBCPASDataType` | レコードのデータ型。 |
| data | `str` | レコードデータ。 |

## add_record {#record}

新しいレコードを追加します。

```python
def add_record(self, record):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| record | `HIBCPASRecord` | 追加されるレコード。 |

**Returns:** Reference to the instance itself.

### 関連項目
* class [`HIBCPASData`](/signature/python-net/groupdocs.signature.domain.extensions/hibcpasdata/)
