---
title: "clone メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "FormField Signature インスタンスをクローンします。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/digitalformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

FormField Signature インスタンスをクローンします。

```python
def clone(self):
    ...
```

**Returns:** DigitalFormFieldSignature: Cloned FormField Signature instance.

### 例

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# 新しい値でメタデータ署名をクローンする
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### 関連項目
* class [`DigitalFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/digitalformfieldsignature/)
