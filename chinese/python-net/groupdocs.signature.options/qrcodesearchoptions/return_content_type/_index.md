---
title: "`return_content_type` 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "在启用 returncontent 属性时，QR-Code 签名返回的图像内容的文件类型。"
type: docs
url: /zh/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/
is_root: false
weight: 2050
---


## return_content_type property

当启用 `return_content` 属性时，QR-Code 签名返回的图像内容的文件类型。

默认情况下，它被设置为 `None`，这会以原始格式返回 QR-Code 图像内容。图像格式在 [`QrCodeSignature.Format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/) 中指定。支持的值有 [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/)、[`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/)、以及 [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/)。如果提供了不受支持的格式，QR-Code 图像内容将以 PNG 返回。

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
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
