---
title: "customer_content プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "顧客が使用できるオプションのスペースです。"
type: docs
url: /ja/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content/
is_root: false
weight: 2020
---


## customer_content property

顧客が使用できるオプションのスペースです。

最大長は `Mailmark2DType` に依存します:

- Type 7: 6 characters
- Type 9: 45 characters
- Type 29: 25 characters

### Definition:
```python
@property
def customer_content(self):
    ...
@customer_content.setter
def customer_content(self, value):
    ...
```

### 関連項目
* class [`Mailmark2D`](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/)
