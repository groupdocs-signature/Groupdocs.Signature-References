---
title: "add メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "既存の MetadataSignature インスタンスをコレクションに追加します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/metadatasignoptions/add/
is_root: false
weight: 1010
---


## add {#metadata_signature}

既存の MetadataSignature インスタンスをコレクションに追加します。

```python
def add(self, metadata_signature):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| metadata_signature | `MetadataSignature` | 追加する既存の MetadataSignature インスタンス。 |

**Returns:** The MetadataSignOptions instance.

### 例

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr.Scherlock Holmes"))
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s)")
```

### 関連項目
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
