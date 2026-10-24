---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "指定された名前と空の値で WordProcessingMetadataSignature を初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

指定された名前と空の値で WordProcessingMetadataSignature を初期化します。

```python
def __init__(self, name):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| name | `str` | WordProcessing Metadata Signature の名前。 |

### 例

```python
from datetime import datetime
from groupdocs.signature.domain import WordProcessingMetadataSignature

# 名前と値でメタデータ署名を作成する
author_sig = WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = WordProcessingMetadataSignature("DateCreated", datetime.now())
id_sig = WordProcessingMetadataSignature("DocumentId", 123456)
float_sig = WordProcessingMetadataSignature("SignatureId", 123.456)
```

## __init__ {#name-value}

事前定義された値で WordProcessing メタデータ署名を初期化します。

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
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### 関連項目
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
