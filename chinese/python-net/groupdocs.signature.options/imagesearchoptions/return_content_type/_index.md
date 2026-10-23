---
title: "`return_content_type` 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "当启用 returncontent 属性时，返回的图像内容的文件类型。"
type: docs
url: /zh/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

返回的图像内容的文件类型，当启用 `return_content` 属性时。

如果未设置（默认 `None`），图像内容将以 [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) 定义的原始格式返回。支持的值有 [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/)、[`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/) 和 [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/)。如果提供了不受支持的格式，将返回原始格式。

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
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
