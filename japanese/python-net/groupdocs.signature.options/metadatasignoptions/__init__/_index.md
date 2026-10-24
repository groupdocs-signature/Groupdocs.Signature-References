---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "デフォルト値で MetadataSignOptions クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/metadatasignoptions/__init__/
is_root: false
weight: 10
---


## __init__

デフォルト値で MetadataSignOptions クラスの新しいインスタンスを初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    options.signatures.add(
        WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
    )
    result = signature.sign("signed.docx", options)
```

## __init__ {#signatures}

[`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) の新しいインスタンスをメタデータで初期化します。

```python
def __init__(self, signatures):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| signatures | `Iterable[MetadataSignature]` | メタデータ署名のコレクション `MetadataSignature`。 |

### 例

```python
from datetime import datetime
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

signatures = [
    WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes"),
    WordProcessingMetadataSignature("DateCreated", datetime.now()),
]

options = MetadataSignOptions(signatures=signatures)
```

### 関連項目
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
