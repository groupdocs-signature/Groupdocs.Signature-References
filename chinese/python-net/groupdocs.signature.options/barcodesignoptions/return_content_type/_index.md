---
title: "`return_content_type` 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "当启用 `return_content` 属性时，条形码签名返回的图像内容的文件类型。"
type: docs
url: /zh/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/
is_root: false
weight: 2120
---


## return_content_type property

当启用 `return_content` 属性时，返回的条形码签名图像内容的文件类型。

默认情况下设置为 `None`，这意味着条形码图像内容以其原始格式返回。图像格式由 [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/) 指定。支持的值有 [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/)、[`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/) 和 [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/)。如果提供了不受支持的格式，条形码图像内容将以 PNG 格式返回。

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
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
