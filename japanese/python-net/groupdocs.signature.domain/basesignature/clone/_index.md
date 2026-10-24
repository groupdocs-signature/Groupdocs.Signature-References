---
title: "clone メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "署名インスタンスをクローンします。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/basesignature/clone/
is_root: false
weight: 1010
---


## clone

署名インスタンスをクローンします。

```python
def clone(self):
    ...
```

**Returns:** The cloned `Signature` instance.

### 例

```python
    from datetime import datetime
    from groupdocs.signature.domain import PdfMetadataSignatures

    # 新しい値でメタデータ署名をクローンする
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### 関連項目
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)
