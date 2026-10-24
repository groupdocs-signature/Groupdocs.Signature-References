---
title: "return_content_type プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "returncontent プロパティが有効な場合の QR‑Code 署名の返却画像コンテンツのファイルタイプ。"
type: docs
url: /ja/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/
is_root: false
weight: 2160
---


## return_content_type property

`return_content` プロパティが有効な場合に返される QR‑Code 署名の画像コンテンツのファイルタイプです。

既定では `None` で、[`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/) で指定された元の形式で QR‑Code 画像コンテンツを返します。

サポートされている値は [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/)、[`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/)、および [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/) です。サポートされていない形式が指定された場合、コンテンツは PNG 形式で返されます。

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
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
