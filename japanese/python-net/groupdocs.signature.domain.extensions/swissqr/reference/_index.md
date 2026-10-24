---
title: "reference プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "債権者の支払参照。"
type: docs
url: /ja/python-net/groupdocs.signature.domain.extensions/swissqr/reference/
is_root: false
weight: 2070
---


## reference property

債権者の支払参照。

SwissQR IBAN（CHxx30000xxxxxx から CHxx31999xxxxx の範囲の IBAN）では必須です。指定する場合、参照は有効な SwissQR 参照（ISR 参照形式に対応）または ISO 11649（\"RFxxxx\"）に基づく有効な債権者参照のいずれかでなければなりません。どちらも書式設定のためにスペースを含めることができます。

### Definition:
```python
@property
def reference(self):
    ...
@reference.setter
def reference(self, value):
    ...
```

### 関連項目
* class [`SwissQR`](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/)
