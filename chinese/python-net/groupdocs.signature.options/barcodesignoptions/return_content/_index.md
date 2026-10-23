---
title: "`return_content` 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "标志指示是否检索放置在文档页面上的签名的条形码图像内容。"
type: docs
url: /zh/python-net/groupdocs.signature.options/barcodesignoptions/return_content/
is_root: false
weight: 2110
---


## return_content property

标志指示是否检索放置在文档页面上的签名的条形码图像内容。

当设置为 True 时，条形码签名图像内容将以 `return_content_type` 指定的格式保留为原始图像数据。默认情况下，此选项为禁用 (False)。

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
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
