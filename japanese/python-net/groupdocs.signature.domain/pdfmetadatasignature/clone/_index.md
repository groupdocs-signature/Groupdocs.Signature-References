---
title: "clone メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "メタデータ署名インスタンスをクローンします。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/
is_root: false
weight: 1010
---


## clone

メタデータ署名インスタンスをクローンします。

```python
def clone(self):
    ...
```

**Returns:** PdfMetadataSignature: Cloned Metadata Signature instance.

### 例

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    # 新しい値で標準メタデータ署名をクローンする
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

## clone {#value}

指定された値で PDF メタデータ署名インスタンスをクローンします。

```python
def clone(self, value):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| value | `Any` | 新しくクローンされたオブジェクトの値。 |

**Returns:** A cloned metadata signature instance.

### 例

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# 既存のメタデータ署名を新しい値でクローンする
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### 関連項目
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
