---
title: "`return_content_type` 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "当启用 returncontent 属性时，QR‑Code 签名返回的图像内容的文件类型。"
type: docs
url: /zh/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/
is_root: false
weight: 2160
---


## return_content_type property

当启用 `return_content` 属性时，返回的 QR‑Code 签名图像内容的文件类型。

默认情况下为 `None`，它会返回 QR‑Code 图像内容，使用 [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/) 指定的原始格式。

支持的值有 [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/)、[`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/)、以及 [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/)。如果提供了不受支持的格式，内容将以 PNG 格式返回。

### Definition:
```python
@property
def return_content_type(self):
    ...
@return_content_type.setter
def return_content_type(self, value):
    ...
```

### 另见
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
