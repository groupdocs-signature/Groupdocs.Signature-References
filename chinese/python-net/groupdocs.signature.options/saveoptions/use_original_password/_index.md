---
title: "use_original_password 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "指示在将已签名文档保存为受保护状态时是否使用 LoadOptions 中的密码的标志。"
type: docs
url: /zh/python-net/groupdocs.signature.options/saveoptions/use_original_password/
is_root: false
weight: 2040
---


## use_original_password property

标志指示在将已签名文档保存为受保护时是否使用来自 [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) 的密码。默认值为 True。Image 文档不支持此功能。

### Definition:
```python
@property
def use_original_password(self):
    ...
@use_original_password.setter
def use_original_password(self, value):
    ...
```

### 另见
* class [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)
