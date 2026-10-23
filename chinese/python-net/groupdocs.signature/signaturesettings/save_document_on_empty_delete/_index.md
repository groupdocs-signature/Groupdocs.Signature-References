---
title: "save_document_on_empty_delete 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "决定当 Delete 方法没有受影响的签名可删除时，是否重新保存源文档的标志。"
type: docs
url: /zh/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/
is_root: false
weight: 2050
---


## save_document_on_empty_delete property

决定当 Delete 方法没有受影响的签名可删除时，是否重新保存源文档的标志。

当设置为 True（默认）时，即使未删除任何签名，文档也会保存带有历史日志（日期和操作类型）；当设置为 False 时，源文档保持不变。

### Definition:
```python
@property
def save_document_on_empty_delete(self):
    ...
@save_document_on_empty_delete.setter
def save_document_on_empty_delete(self, value):
    ...
```

### 另见
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
