---
title: load_external_resources property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The flag that determines whether the document loads external resources."
type: docs
url: /python-net/groupdocs.signature.options/loadoptions/load_external_resources/
is_root: false
weight: 2020
---


## load_external_resources property

The flag that determines whether the document loads external resources. This property is obsolete; use [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) instead, which has the opposite meaning.

LoadExternalResources = True is equivalent to `SkipExternalResources` = False, and LoadExternalResources = False is equivalent to `SkipExternalResources` = True. The default value is False, meaning external resources are not loaded unless explicitly allowed.

### Definition:
```python
@property
def load_external_resources(self):
    ...
@load_external_resources.setter
def load_external_resources(self, value):
    ...
```

### See Also
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
