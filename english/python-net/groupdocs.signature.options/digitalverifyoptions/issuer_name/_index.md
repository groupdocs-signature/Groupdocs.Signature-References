---
title: issuer_name property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The issuer name of the certificate to validate."
type: docs
url: /python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name/
is_root: false
weight: 2060
---


## issuer_name property

The issuer name of the certificate to validate.

The value is case sensitive. If this property is set, verification will check if the signature's issuer name contains or equals the passed value.

### Definition:
```python
@property
def issuer_name(self):
    ...
@issuer_name.setter
def issuer_name(self, value):
    ...
```

### See Also
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
