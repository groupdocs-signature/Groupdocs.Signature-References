---
title: "ooxml_compliance 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "签署文档的可选 OOXML 合规级别。"
type: docs
url: /zh/python-net/groupdocs.signature.options/wordprocessingsaveoptions/ooxml_compliance/
is_root: false
weight: 2020
---


## ooxml_compliance property

签署文档的可选 OOXML 合规级别。

设置后，将覆盖原始文档的合规性。若为 None（默认），则保留加载文档的合规性。仅在 OOXML 格式（Docx、Docm、Dotx、Dotm、FlatOpc 及其变体）中生效。

### Definition:
```python
@property
def ooxml_compliance(self):
    ...
@ooxml_compliance.setter
def ooxml_compliance(self, value):
    ...
```

### 另见
* class [`WordProcessingSaveOptions`](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/)
