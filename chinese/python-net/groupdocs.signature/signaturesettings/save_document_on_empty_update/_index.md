---
title: "save_document_on_empty_update 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "决定在 Update 方法没有签名可更新时是否重新保存源文档的标志。"
type: docs
url: /zh/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/
is_root: false
weight: 2060
---


## save_document_on_empty_update property

决定当 `Update` 方法没有签名可更新时，是否重新保存源文档的标志。

如果设置为 `True`（默认），即使没有签名被更新，文档也会保存相应的历史处理日志（日期和操作类型）。设置为 `False` 时，源文档根本不被修改。

### Definition:
```python
@property
def save_document_on_empty_update(self):
    ...
@save_document_on_empty_update.setter
def save_document_on_empty_update(self, value):
    ...
```

### 另见
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
