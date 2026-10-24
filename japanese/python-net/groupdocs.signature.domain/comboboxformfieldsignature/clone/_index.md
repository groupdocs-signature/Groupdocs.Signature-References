---
title: "clone メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "FormField 署名インスタンスをクローンします。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/comboboxformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

FormField 署名インスタンスをクローンします。

```python
def clone(self):
    ...
```

**Returns:** A cloned FormField signature instance.

### 例

```python
from groupdocs.signature.domain import ComboboxFormFieldSignature

# 元のコンボボックスフォームフィールド署名を作成する
original = ComboboxFormFieldSignature()

# 署名をクローンする
cloned = original.clone()
```

### 関連項目
* class [`ComboboxFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/)
