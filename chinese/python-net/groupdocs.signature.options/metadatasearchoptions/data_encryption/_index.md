---
title: "data_encryption 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "用于解密此选项集合中所有元数据签名的 IDataEncryption 实现。"
type: docs
url: /zh/python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption/
is_root: false
weight: 2010
---


## data_encryption property

实现了用于解密此选项集合中所有元数据签名的 [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/)。

如果设置，则所有找到的签名默认使用此加密，除非它们已分配自己的 DataEncryption。

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
* class [`MetadataSearchOptions`](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/)
