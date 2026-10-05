---
title: reference property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The creditor payment reference."
type: docs
url: /python-net/groupdocs.signature.domain.extensions/swissqr/reference/
is_root: false
weight: 2070
---


## reference property

The creditor payment reference.

It is mandatory for SwissQR IBANs (IBANs in the range CHxx30000xxxxxx through CHxx31999xxxxx). If specified, the reference must be either a valid SwissQR reference (corresponding to ISR reference form) or a valid creditor reference according to ISO 11649 ("RFxxxx"). Both may contain spaces for formatting.

### Definition:
```python
@property
def reference(self):
    ...
@reference.setter
def reference(self, value):
    ...
```

### See Also
* class [`SwissQR`](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/)
