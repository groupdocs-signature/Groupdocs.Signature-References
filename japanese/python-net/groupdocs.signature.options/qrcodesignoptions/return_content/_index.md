---
title: "return_content プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "ドキュメントページに配置された署名の QR コード画像コンテンツを取得するフラグです。"
type: docs
url: /ja/python-net/groupdocs.signature.options/qrcodesignoptions/return_content/
is_root: false
weight: 2150
---


## return_content property

ドキュメントページに配置された署名の QR コード画像コンテンツを取得するフラグです。

True に設定すると、QR-Code 署名画像のコンテンツは、[`QrCodeSignOptions.ReturnContentType`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/) で指定された形式の生画像データとして保持されます。既定では、このオプションは無効になっています。

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
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
