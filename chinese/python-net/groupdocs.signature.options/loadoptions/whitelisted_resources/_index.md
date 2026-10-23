---
title: "whitelisted_resources 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "即使在 LoadOptions.SkipExternalResources 为 true 时，也会加载的外部资源地址片段列表。"
type: docs
url: /zh/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/
is_root: false
weight: 2060
---


## whitelisted_resources property

即使 [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) 为 true，也会加载的外部资源地址片段列表。默认值为空列表。

当资源的完整地址包含其中一个片段时即加载该资源。比较时忽略大小写，空片段会被忽略。建议使用较长的片段，例如 `\"https://cdn.example.com/images/\"`：短片段也会匹配其他恰好包含它的地址。

将此属性设置为 `None` 将清空列表。当 [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) 为 false 时，该列表不产生任何作用，因为此时会加载所有外部资源。

### Definition:
```python
@property
def whitelisted_resources(self):
    ...
@whitelisted_resources.setter
def whitelisted_resources(self, value):
    ...
```

### 另见
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
