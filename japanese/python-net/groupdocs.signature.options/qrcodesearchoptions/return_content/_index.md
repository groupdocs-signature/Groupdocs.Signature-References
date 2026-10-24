---
title: "return_content プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "ドキュメントページ上の各署名に対して QR‑Code 画像コンテンツが返されるかどうかを決定するフラグ。"
type: docs
url: /ja/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/
is_root: false
weight: 2040
---


## return_content property

ドキュメントページ上の各署名に対して QR‑Code 画像コンテンツを返すかどうかを決定するフラグです。True に設定すると、生の画像データが `return_content_type` で指定された形式で署名の `content` プロパティに保持されます。デフォルトでは無効です。

### Definition:
```python
@property
def return_content(self):
    ...
@return_content.setter
def return_content(self, value):
    ...
```

### 関連項目
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
