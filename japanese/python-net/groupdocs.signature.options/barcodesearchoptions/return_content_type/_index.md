---
title: "return_content_type プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "returncontent プロパティが有効な場合のバーコード署名の返却画像コンテンツのファイルタイプ。"
type: docs
url: /ja/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

`return_content` プロパティが有効な場合のバーコード署名の返却画像コンテンツのファイルタイプです。

デフォルトでは None で、[`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/) で指定された元の形式でバーコード画像が返されます。

サポートされている値は [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/)、[`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/)、[`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/) です。これら以外の値が指定された場合、画像は PNG 形式で返されます。

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
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
