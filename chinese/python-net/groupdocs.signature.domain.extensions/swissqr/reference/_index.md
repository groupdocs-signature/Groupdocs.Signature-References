---
title: "reference 属性"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "债权人付款参考。"
type: docs
url: /zh/python-net/groupdocs.signature.domain.extensions/swissqr/reference/
is_root: false
weight: 2070
---


## reference property

债权人付款参考。

对于 SwissQR IBAN（范围为 CHxx30000xxxxxx 到 CHxx31999xxxxx）是强制性的。如果指定，reference 必须是有效的 SwissQR 参考（对应 ISR 参考表格）或符合 ISO 11649（\"RFxxxx\"）的有效债权人参考。两者都可以包含空格用于格式化。

### Definition:
```python
@property
def reference(self):
    ...
@reference.setter
def reference(self, value):
    ...
```

### 另见
* class [`SwissQR`](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/)
