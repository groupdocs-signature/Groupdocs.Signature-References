---
title: "`return_content` 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "用于检索放置在文档页面上的签名的 QR-Code 图像内容的标志。"
type: docs
url: /zh/python-net/groupdocs.signature.options/qrcodesignoptions/return_content/
is_root: false
weight: 2150
---


## return_content property

用于检索放置在文档页面上的签名的 QR-Code 图像内容的标志。

如果设置为 True，QR-Code 签名图像内容将以原始图像数据形式保留，使用由 [`QrCodeSignOptions.ReturnContentType`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/) 指定的格式。默认情况下，此选项是禁用的。

### Definition:
```python
@property
def return_content(self):
    ...
@return_content.setter
def return_content(self, value):
    ...
```

### 另见
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
