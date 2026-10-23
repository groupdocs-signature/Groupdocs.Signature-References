---
title: "`return_content` 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "确定是否为文档页上的每个签名返回 QR‑Code 图像内容的标志。"
type: docs
url: /zh/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/
is_root: false
weight: 2040
---


## return_content property

标志决定是否为文档页上的每个签名返回 QR‑Code 图像内容。设置为 True 时，原始图像数据会保存在签名的 `content` 属性中，使用 `return_content_type` 指定的格式。默认情况下禁用。

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
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
