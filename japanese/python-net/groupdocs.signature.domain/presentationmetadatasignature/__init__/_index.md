---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "指定された名前と空の値で PresentationMetadataSignature を初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/presentationmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

指定された名前と空の値で PresentationMetadataSignature を初期化します。

```python
def __init__(self, name):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| name | `str` | Presentation Metadata Signature の名前。 |

## __init__ {#name-value}

事前定義された値で PresentationMetadataSignature を初期化します。

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
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PresentationMetadataSignature

with Signature("sample.ppsx") as signature:
    options = MetadataSignOptions()
    signatures = [
        PresentationMetadataSignature("Author", "Mr. Sherlock Holmes"),
        PresentationMetadataSignature("DateCreated", datetime.now()),
        PresentationMetadataSignature("DocumentId", 123456),
        PresentationMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.ppsx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### 関連項目
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
