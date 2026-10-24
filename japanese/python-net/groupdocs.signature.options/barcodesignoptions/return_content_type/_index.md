---
title: "return_content_type プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "デフォルトでは `None` に設定されており、これはバーコード画像コンテンツが元の形式で返されることを意味します。画像形式は [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/) で指定されます。サポートされている値は [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/)、[`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/)、および [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/) です。サポートされていない形式が指定された場合、バーコード画像コンテンツは PNG 形式で返されます。"
type: docs
url: /ja/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/
is_root: false
weight: 2120
---


## return_content_type property

`return_content` プロパティが有効な場合のバーコード署名の返却画像コンテンツのファイルタイプです。

ドキュメントページ上の署名領域の左側 X 位置（測定単位：ピクセル、パーセント、またはミリメートル）で表されます。

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
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
