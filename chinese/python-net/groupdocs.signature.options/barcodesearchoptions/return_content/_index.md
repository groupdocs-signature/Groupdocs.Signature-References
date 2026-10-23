---
title: "`return_content` 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "指示是否检索文档页上签名的条形码图像内容的标志。"
type: docs
url: /zh/python-net/groupdocs.signature.options/barcodesearchoptions/return_content/
is_root: false
weight: 2030
---


## return_content property

指示是否检索文档页上签名的条形码图像内容的标志。

如果设置为 `True`，条形码签名图像内容将以 `return_content_type` 指定的格式保留为原始图像数据。默认情况下禁用。

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
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
