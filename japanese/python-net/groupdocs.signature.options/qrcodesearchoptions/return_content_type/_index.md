---
title: "return_content_type プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "returncontent プロパティが有効な場合の QR-Code 署名の返却画像コンテンツのファイルタイプ。"
type: docs
url: /ja/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/
is_root: false
weight: 2050
---


## return_content_type property

`return_content` プロパティが有効な場合の QR-Code 署名の返却画像コンテンツのファイルタイプです。

デフォルトでは `None` に設定されており、元の形式で QR-Code 画像コンテンツを返します。画像形式は [`QrCodeSignature.Format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/) で指定します。サポートされている値は [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/)、[`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/)、および [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/) です。サポートされていない形式が指定された場合、 QR-Code 画像コンテンツは PNG として返されます。

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
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
