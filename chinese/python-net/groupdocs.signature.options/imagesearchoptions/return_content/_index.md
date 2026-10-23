---
title: "`return_content` 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "决定是否返回签名的图像内容的标志。"
type: docs
url: /zh/python-net/groupdocs.signature.options/imagesearchoptions/return_content/
is_root: false
weight: 2030
---


## return_content property

决定是否返回签名的图像内容的标志。

如果设置为 True，图像签名内容将以原始图像数据的形式保留，格式由 [`ImageSearchOptions.return_content_type`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/) 指定。默认情况下此选项为禁用 (False)。

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
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
