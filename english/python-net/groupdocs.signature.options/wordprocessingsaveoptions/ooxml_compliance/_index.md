---
title: ooxml_compliance property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The optional OOXML compliance level for the signed document."
type: docs
url: /python-net/groupdocs.signature.options/wordprocessingsaveoptions/ooxml_compliance/
is_root: false
weight: 2020
---


## ooxml_compliance property

The optional OOXML compliance level for the signed document.

When set, overrides the original document's compliance. When None (default), the loaded document's compliance is preserved. Only honored for OOXML formats (Docx, Docm, Dotx, Dotm, FlatOpc and FlatOpc variants).

### Definition:
```python
@property
def ooxml_compliance(self):
    ...
@ooxml_compliance.setter
def ooxml_compliance(self, value):
    ...
```

### See Also
* class [`WordProcessingSaveOptions`](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/)
