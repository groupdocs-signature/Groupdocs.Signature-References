---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "事前定義された名前と空の値で Spreadsheet Metadata Signature を初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

事前定義された名前と空の値で Spreadsheet Metadata Signature を初期化します。

```python
def __init__(self, name):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| name | `str` | スプレッドシート メタデータ署名の名前。 |

## __init__ {#name-value}

事前定義された値で Spreadsheet Metadata Signature を初期化します。

```python
def __init__(self, name, value):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| name | `str` | メタデータ署名オブジェクトの名前。 |
| value | `Any` | メタデータ署名の値。 |

### 例

```python
from datetime import datetime
from groupdocs.signature.domain import SpreadsheetMetadataSignature

# スプレッドシート用のメタデータ署名を作成する
author_sig = SpreadsheetMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = SpreadsheetMetadataSignature("DateCreated", datetime.now())
id_sig = SpreadsheetMetadataSignature("DocumentId", 123456)
float_sig = SpreadsheetMetadataSignature("SignatureId", 123.456)
```

### 関連項目
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
