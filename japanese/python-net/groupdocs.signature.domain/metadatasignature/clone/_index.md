---
title: "clone メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "Metadata Signature インスタンスをクローンします。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/metadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Metadata Signature インスタンスをクローンします。

```python
def clone(self):
    ...
```

**Returns:** Returns cloned Metadata Signature instance.

### 例

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# 事前定義された AUTHOR 署名に基づいて新しいメタデータ署名を作成します
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

## clone {#value}

指定された値で Metadata Signature インスタンスをクローンします。

```python
def clone(self, value):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| value | `Any` | 新しくクローンされたオブジェクトの値です。 |

**Returns:** MetadataSignature: Cloned Metadata Signature instance with given value.

### 例

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# 既存のメタデータ署名を新しい値でクローンする
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### 関連項目
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
