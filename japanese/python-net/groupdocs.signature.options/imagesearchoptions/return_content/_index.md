---
title: "return_content プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "署名の画像コンテンツを返すかどうかを決定するフラグ。"
type: docs
url: /ja/python-net/groupdocs.signature.options/imagesearchoptions/return_content/
is_root: false
weight: 2030
---


## return_content property

署名の画像コンテンツを返すかどうかを決定するフラグ。

True に設定すると、画像署名のコンテンツは [`ImageSearchOptions.return_content_type`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/) で指定された形式の生画像データとして保持されます。デフォルトではこのオプションは無効 (False) です。

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
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
