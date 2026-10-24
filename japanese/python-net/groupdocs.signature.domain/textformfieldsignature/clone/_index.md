---
title: "clone メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "FormField Signature インスタンスをクローンします。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/textformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

FormField Signature インスタンスをクローンします。

```python
def clone(self):
    ...
```

**Returns:** TextFormFieldSignature: Cloned FormField Signature instance.

### 例

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    new_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### 関連項目
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
