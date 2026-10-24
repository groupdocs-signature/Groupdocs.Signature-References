---
title: "return_content_type プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "returncontent プロパティが有効な場合に返される画像コンテンツのファイルタイプです。"
type: docs
url: /ja/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

`return_content` プロパティが有効なときに返される画像コンテンツのファイルタイプです。

設定されていない場合（デフォルトは `None`）、画像コンテンツは [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) で定義された元の形式で返されます。サポートされている値は [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/)、[`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/)、および [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/) です。サポートされていない形式が指定された場合、元の形式が返されます。

### Definition:
```python
@property
def return_content_type(self):
    ...
@return_content_type.setter
def return_content_type(self, value):
    ...
```

### 関連項目
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
