---
title: "data_encryption 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "IDataEncryption 的实现用于加密此选项集合中的所有元数据签名。"
type: docs
url: /zh/python-net/groupdocs.signature.options/metadatasignoptions/data_encryption/
is_root: false
weight: 2010
---


## data_encryption property

用于加密此选项集合中所有元数据签名的 [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) 实现。

如果设置，此后所有添加的签名将默认使用此加密，除非它们已分配自己的 DataEncryption。

### Definition:
```python
@property
def data_encryption(self):
    ...
@data_encryption.setter
def data_encryption(self, value):
    ...
```

### 另见
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
