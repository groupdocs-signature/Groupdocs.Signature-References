---
title: "return_content プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "文書ページに配置された署名のバーコード画像コンテンツを取得するかどうかを示すフラグです。"
type: docs
url: /ja/python-net/groupdocs.signature.options/barcodesignoptions/return_content/
is_root: false
weight: 2110
---


## return_content property

文書ページに配置された署名のバーコード画像コンテンツを取得するかどうかを示すフラグです。

True に設定すると、バーコード署名画像のコンテンツは `return_content_type` で指定された形式の生画像データとして保持されます。デフォルトでは、このオプションは無効（False）です。

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
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
