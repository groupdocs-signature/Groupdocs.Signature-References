---
title: whitelisted_resources property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The list of address fragments of external resources that are loaded even when LoadOptions.SkipExternalResources is true."
type: docs
url: /python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/
is_root: false
weight: 2060
---


## whitelisted_resources property

The list of address fragments of external resources that are loaded even when [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) is true. The default value is an empty list.

A resource is loaded when its full address contains one of the fragments. The comparison ignores case, and empty fragments are ignored. Prefer long fragments such as `"https://cdn.example.com/images/"`: a short fragment also matches other addresses that happen to contain it.

Setting this property to `None` clears the list. The list has no effect when [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) is false, because then every external resource is loaded.

### Definition:
```python
@property
def whitelisted_resources(self):
    ...
@whitelisted_resources.setter
def whitelisted_resources(self, value):
    ...
```

### See Also
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
