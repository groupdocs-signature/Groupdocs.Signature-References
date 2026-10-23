---
title: "load_external_resources 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "决定文档是否加载外部资源的标志。"
type: docs
url: /zh/python-net/groupdocs.signature.options/loadoptions/load_external_resources/
is_root: false
weight: 2020
---


## load_external_resources property

决定文档是否加载外部资源的标志。此属性已过时；请改用 [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/)，其含义相反。

LoadExternalResources = True 等同于 `SkipExternalResources` = False，LoadExternalResources = False 等同于 `SkipExternalResources` = True。默认值为 False，表示除非明确允许，否则不加载外部资源。

### Definition:
```python
@property
def load_external_resources(self):
    ...
@load_external_resources.setter
def load_external_resources(self, value):
    ...
```

### 另见
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
