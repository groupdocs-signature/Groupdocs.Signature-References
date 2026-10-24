---
title: "clone メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "このオブジェクトのコピーを取得します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/
is_root: false
weight: 1010
---


## clone

このオブジェクトのコピーを取得します。

```python
def clone(self):
    ...
```

### 例

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignatures

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    # 新しい値でメタデータ署名をクローンする
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    options.signatures.add(author_sig)
```

### 関連項目
* class [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)
