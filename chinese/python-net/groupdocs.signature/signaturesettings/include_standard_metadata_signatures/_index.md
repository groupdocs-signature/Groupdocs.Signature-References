---
title: "include_standard_metadata_signatures 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "指示是否在元数据列表中包含标准文档元数据签名（如作者、所有者、创建日期和修改日期）的标志。"
type: docs
url: /zh/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/
is_root: false
weight: 2020
---


## include_standard_metadata_signatures property

指示是否在元数据列表中包含标准文档元数据签名（如作者、所有者、创建日期和修改日期）的标志。

如果设置为 False（默认），GetDocumentInfo 将不包含这些元数据签名。设置为 True 时，文档信息将包含标准元数据签名。

### Definition:
```python
@property
def include_standard_metadata_signatures(self):
    ...
@include_standard_metadata_signatures.setter
def include_standard_metadata_signatures(self, value):
    ...
```

### 另见
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
